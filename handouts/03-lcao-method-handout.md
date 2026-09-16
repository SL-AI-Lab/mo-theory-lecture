# Handout 03: The LCAO Method — Detailed Notes

## The Variational Principle

For a trial wavefunction ψ, the expectation value of the energy is an upper
bound to the true ground-state energy:

```
E = ⟨ψ|H|ψ⟩ / ⟨ψ|ψ⟩  ≥  E_0
```

This justifies optimizing the coefficients in an LCAO expansion.

## LCAO Expansion

Approximate a molecular orbital as a linear combination of atomic orbitals:

```
ψ = c_1 φ_1 + c_2 φ_2 + …  + c_N φ_N
```

For a diatomic using two AOs (φ_a on atom A, φ_b on atom B):

```
ψ = c_a φ_a + c_b φ_b
```

## Setting Up the Secular Equation

Minimizing the energy with respect to c_a and c_b leads to the secular
equations. Define integrals:

- **Coulomb integral** (on atom a):
  `α_a = ∫ φ_a* H φ_a dτ`
- **Resonance (bond) integral**:
  `β = ∫ φ_a* H φ_b dτ`
- **Overlap integral**:
  `S = ∫ φ_a* φ_b dτ`

For a **homonuclear** diatomic (α_a = α_b = α), the secular determinant is:

```
| α − E      β − E S |
| β − E S    α − E   |  =  0
```

Solving gives two roots:

```
E_+ = (α + β) / (1 + S)        (bonding, lower)
E_− = (α − β) / (1 − S)        (antibonding, higher)
```

## Bonding vs Antibonding

- **Bonding MO** (energy below the AOs): constructive interference, electron
  density between the nuclei. Stabilization ~ β.
- **Antibonding MO** (energy above the AOs): destructive interference, a nodal
  plane between the nuclei. Destabilization slightly larger than the bonding
  stabilization (because of the 1 − S denominator).

## Normalization and Overlap

If we ignore overlap for a rough calculation (S = 0), the normalized orbitals are:

```
ψ_bond  = (φ_a + φ_b) / √2
ψ_anti  = (φ_a − φ_b) / √2
```

The exact bonding orbital accommodates more density between nuclei, which is
why the overlap integral S < 1 raises the antibonding level more than it lowers
the bonding level.

## σ and π Orbitals

### σ orbitals

- Cylindrically symmetric about the internuclear (z) axis
- Formed from s–s, s–p_z, p_z–p_z head-on overlap

### π orbitals

- Density above and below the axis; a nodal plane contains the axis
- Formed from p_x–p_x or p_y–p_y side-on overlap
- π overlap is weaker than σ overlap (less density along the axis)

## Conditions for Strong Combination

1. Similar energy (small α_a − α_b)
2. Good overlap (large S)
3. Matching symmetry (nonzero β)

If the symmetry or energy match is poor, the combination may produce near-
**nonbonding** MOs.

## Worked Example: H2+ minimal model

**Problem.** Using the LCAO with two 1s orbitals and S = 0, write the normalized
bonding and antibonding MOs of H2+.

**Solution.**
- Bonding: `ψ_+ = (1s_A + 1s_B)/√2`
- Antibonding: `ψ_− = (1s_A − 1s_B)/√2`

Each is normalized: ∫|ψ|²dτ = (1/2)(1 + 1 ± 2S) = 1 when S = 0.

## Practice Problems

1. Why is the antibonding MO destabilized more than the bonding MO is stabilized?
2. Which combination produces an antibonding MO: same-phase or opposite-phase?
3. A molecule has α = −10 eV and β = −2 eV with S = 0. Find E_+ and E_−.
4. Why is π overlap generally weaker than σ overlap?

### Solutions

1. The overlap integral appears in the denominator (1 − S) for the antibonding
   orbital, and S > 0, so the antibonding level is pushed up more than bonding is lowered.
2. Opposite-phase (subtraction) combination yields an antibonding MO (node between nuclei).
3. E_+ = −10 + (−2) = −12 eV; E_− = −10 − (−2) = −8 eV.
4. π overlap places less electron density along the internuclear axis and has a nodal
   plane containing the axis, so the overlap S and resonance β are smaller.

## Reading

- Levine: molecular orbital method / LCAO chapter.
- Atkins & de Paula: H2+ treatment in quantum chemistry section.
