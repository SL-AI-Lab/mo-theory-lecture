# Handout 10: Applications & Limitations — Detailed Notes

## Applications of MO Theory

### 1. Magnetic properties
- Correctly predicts paramagnetic O2 (triplet) and NO (doublet)
- Explains diamagnetism of N2, CO, F2
- Directly connects to spin multiplicity and magnetic susceptibility

### 2. Bond order and molecular stability
- Bond order → relative bond length, strength
- Explains why He2/He2+ type species are unstable or weakly bound
- Rationalizes the very strong N≡N triple bond

### 3. Spectroscopy
- Electronic transitions occur between MOs (HOMO → LUMO, etc.)
- Ionization energies relate to orbital energies (Koopmans' theorem
  approximation)
- Basis for interpreting UV–Vis, photoelectron, and absorption spectra

### 4. Reactivity and frontier orbitals
- HOMO (highest occupied) = electron donor
- LUMO (lowest unoccupied) = electron acceptor
- Fukui's frontier orbital theory: reactivity dominated by HOMO/LUMO
- HOMO–LUMO gap → kinetic stability, color, excitation energy

### 5. Computational chemistry
- MO/LCAO is the foundation of Hartree–Fock (HF) and DFT
- Basis sets expand the MO in AO-like functions
- Semiempirical, ab initio, and DFT methods all build on MO concepts

### 6. Solid state
- Band theory = MO theory in the infinite- N limit
- Explains conductors, semiconductors, insulators

## Limitations

### Neglect of electron correlation
- Simple MO (HF) treats each electron in the average field of the others
- This **neglects instantaneous electron correlation**
- Consequences:
  - Systematically too-high total energies
  - Errors in bond dissociation energies
  - Cannot correctly describe bond breaking to atoms (unrestricted/ multireference needed)

### Quantitative issues
- Qualitative energy ordering (s–p mixing) can be ambiguous
- Open-shell systems require careful treatment (spin contamination, multireference)

### Computational cost
- High-accuracy methods (CCSD(T), full CI) scale steeply with system size
- Large molecules need approximations or DFT

### Extension limits
- Periodic systems require band/DFT formalisms, not just a single molecule's diagram
- Relativistic effects become important for heavy elements

## Remedies / Beyond Simple MO

| Method | Adds | Use case |
|--------|------|----------|
| HF (SCF) | mean-field | baseline, large systems |
| DFT | correlation via functional | broad use, moderate cost |
| MP2/CCSD(T) | correlation | accurate ground-state energetics |
| CI / multireference (CASSCF) | excited/multireference states | bond-breaking, excited states, open-shell |
| Periodic DFT | infinite systems, k-points | solids, surfaces |

## Practice Problems

1. Give one property MO theory predicts that Lewis/VB theory cannot, and explain.
2. What is the primary physical effect neglected by simple (HF) MO theory?
3. Define HOMO and LUMO and state their role in reactivity.
4. Which computational method should one choose for an accurate bond-dissociation
   curve of a single breaking bond? Why is plain HF insufficient?

### Solutions

1. Paramagnetism of O2 (unpaired electrons in degenerate π* orbitals).
2. Electron correlation (instantaneous Coulomb repulsion beyond the mean field).
3. HOMO = highest occupied MO (donor); LUMO = lowest unoccupied (acceptor);
   reactivity governed by the HOMO–LUMO interaction.
4. A multireference method (e.g., CASSCF) is needed for accurate bond breaking;
   single-determinant HF cannot describe the transition from molecule to two atoms.

## Reading

- Atkins & de Paula: applications and scope of MO theory.
- Levine: introduction to electron correlation and post-HF methods.
- Szabo & Ostlund, *Modern Quantum Chemistry* (advanced, optional).
