# Handout 04: Homonuclear Diatomics — Detailed Notes

## MO Diagram Construction: General Recipe

1. List the atomic orbitals on each atom (from electron configurations).
2. Determine MO symmetry labels (σ or π, bonding/antibonding).
3. Arrange MOs by energy.
4. Fill electrons (Aufbau + Hund's rule).
5. Compute bond order.

## H2

Two H atoms → two 1s AOs → two MOs: σ(1s) and σ*(1s).

- Electrons: 2
- Fill: σ(1s)²
- Bond order = (2 − 0)/2 = 1
- Stable, diamagnetic ✓

**MO configuration:** (σ1s)²

## He2

Each He: 1s² → four electrons.

- Fill: σ(1s)² σ*(1s)²
- Bond order = (2 − 2)/2 = 0
- **Predicted not bound**; He2 is indeed not a stable ground-state diatomic.
- (Weakly bound He2 van der Waals complexes exist, but no chemical bond.)

## Second-Row Diatomics: Electron Configurations

Core 1s orbitals are usually treated as doubly occupied and nonbonding for the
valence picture; we focus on valence (2s, 2p) configurations.

### B2 (5 e⁻/atom → 10 valence total, but 6 valence in 2s/2p shell counting)

Boron: [He]2s²2p¹ → two atoms: (2s²2p¹)×2 = 8 valence electrons... let's count:
B2 total valence = 2s²2p¹ per atom ×2 → 6 electrons in 2s+2p.

- Fill: σ(2s)² σ*(2s)² π(2p_x)¹ π(2p_y)¹
- (With s–p mixing, case A ordering applies)
- Bond order = (4 − 2)/2 = 1 (some treatments: 1)
- **Paramagnetic** (two unpaired π electrons) ✓ observed

### C2

Carbon: 2s²2p² ×2 → 8 valence electrons.

- Fill: σ(2s)² σ*(2s)² π(2p_x)² π(2p_y)²
- Bond order = (6 − 2)/2 = 2
- **Diamagnetic** in the standard simple treatment

### N2 (10 valence electrons)

- Fill: σ(2s)² σ*(2s)² π(2p_x)² π(2p_y)² σ(2p_z)²
- Bond order = (8 − 2)/2 = 3 → **triple bond**
- **Diamagnetic** ✓
- Very short, very strong bond (~942 kJ/mol)

### O2 (12 valence electrons)

- Fill (case B, no mixing): σ(2s)² σ*(2s)² σ(2p_z)² π(2p_x)² π(2p_y)² π*(2p_x)¹ π*(2p_y)¹
- Bond order = (8 − 4)/2 = 2 → **double bond**
- **Paramagnetic** (two unpaired electrons) ✓ — the famous case

### F2 (14 valence electrons)

- Fill (case B): σ(2s)² σ*(2s)² σ(2p_z)² π(2p)⁴ π*(2p)⁴
- Bond order = (8 − 6)/2 = 1 → **single bond**
- **Diamagnetic** ✓

## Bond Order Formula

```
Bond order = (n_bonding − n_antibonding) / 2
```

## Trends

| Molecule | Valence e⁻ | Bond order | Bond length (pm) | Bond energy (kJ/mol) |
|----------|-----------|-----------|------------------|----------------------|
| N2       | 10        | 3         | ~109.8           | ~942                 |
| O2       | 12        | 2         | ~120.7           | ~498                 |
| F2       | 14        | 1         | ~141.2           | ~159                 |

Higher bond order → shorter bond, higher bond energy (with suitable pairing;
O2's paramagnetism adds no covalent order beyond 2).

## Practice Problems

1. Write the valence MO configuration of N2 and compute its bond order.
2. Predict whether O2 is paramagnetic or diamagnetic, citing the MO reasoning.
3. Why is He2 not a stable molecule?
4. Compare the bond order of B2 and C2.

### Solutions

1. N2: σ(2s)² σ*(2s)² π(2p_x)² π(2p_y)² σ(2p_z)²; bond order = (8−2)/2 = 3.
2. O2: last two electrons occupy degenerate π*(2p) orbitals singly (Hund's rule)
   → two unpaired electrons → paramagnetic.
3. Fill σ(1s)² σ*(1s)² → bonding and antibonding cancel → bond order 0.
4. B2 bond order = (4−2)/2 = 1; C2 bond order = (6−2)/2 = 2.

## Reading

- Atkins & de Paula: molecular orbital description of homonuclear diatomics.
- Levine: homonuclear diatomic molecules chapter.
