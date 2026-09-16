# Handout 09: Band Theory Overview — Detailed Notes

## From Discrete MOs to Continuous Bands

Consider a chain of N atoms, each contributing one s orbital. Bonding and
antibonding combinations spread into a ladder. With N atoms there are N
delocalized MOs. As N → ∞ the discrete levels merge into a **continuous band**.

```
Energy
  ^      band of N states
  |      ...•••••...     increasing N => quasi-continuous
  |
  v
```

## Bloch Picture

In a periodic crystal, wavefunctions take the Bloch form:

```
ψ_k(x) = e^{ikx} u_k(x)
```

- k = crystal momentum (wavevector)
- E(k) dispersion relation defines the band structure
- Number of energy levels in a band = number of unit cells

## Band Filling and the Fermi Level

- Each band can hold 2 electrons per unit cell (spin × states)
- **Fermi level E_F**: highest occupied level at T = 0
- Bands filled up to E_F determine conductivity

## Metals, Semiconductors, Insulators

### Metals
- A band is only **partially filled** (e.g., ns¹ for alkali metals)
- Empty states immediately above E_F → easy promotion → high conductivity
- Alternatively a filled band overlaps an empty band (e.g., some d metals)

### Semiconductors
- Full valence band, small gap (≤ ~3 eV) to conduction band
- Thermal/optical excitation promotes electrons across the gap
- Conductivity rises with temperature (intrinsic) or doping (extrinsic)

### Insulators
- Full valence band, large gap
- Thermal energy insufficient → negligible intrinsic conduction
- Gap > ~3–4 eV generally

## Connection to MO/σ–π Picture

- s and p_z orbitals (σ symmetry) produce σ bands
- p_x, p_y (π symmetry) produce π bands
- Each atomic orbital per unit cell → one band
- Band **width** ~ 4|β| (related to LCAO resonance/overlap integral)
- Larger overlap → wider band → more mobile electrons

## Practice Problems

1. Why is sodium a metal? Use a band-filling argument.
2. What distinguishes a semiconductor from an insulator?
3. How does the LCAO resonance integral relate to band width?
4. Two atoms per unit cell → how many electrons max per band?

### Solutions

1. Sodium is 3s¹: the 3s band is half filled → empty states just above E_F → metal.
2. Gap size: semiconductors have a small gap (~≤3 eV), insulators a large one.
3. Band width ≈ 4|β|: stronger overlap (larger β) → wider band.
4. Two electrons per state; with two atoms per cell there are 2 states per band
   (→ 4 electrons max per band).

## Reading

- Atkins & de Paula: band theory chapter (extended systems).
- Levine: molecular orbitals to bands discussion.
