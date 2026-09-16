# Handout 02: Atomic Orbitals Review — Detailed Notes

## The Four Quantum Numbers

The state of an electron in a hydrogen-like atom is specified by four quantum
numbers arising from the solutions of the Schrödinger equation.

| Quantum number | Symbol | Allowed values | Physical meaning |
|----------------|--------|----------------|------------------|
| Principal      | n      | 1, 2, 3, …     | Energy (shell), size |
| Azimuthal      | l      | 0 … (n−1)      | Orbital angular momentum (subshell, shape) |
| Magnetic       | m_l    | −l … +l        | Orientation of orbital |
| Spin           | m_s    | ±½             | Orientation of electron spin |

## The Hydrogen Atom Wavefunction

The spatial wavefunction factors as a radial and an angular part:

```
ψ_nlm(r, θ, φ) = R_nl(r) · Y_l^m(θ, φ)
```

- `R_nl(r)`: radial function, determines radial nodes and size
- `Y_l^m(θ, φ)`: spherical harmonic, determines angular shape/orientation

## Shapes and Nodes

### s orbitals (l = 0)

- Spherically symmetric
- `n − 1` radial nodes, **0** angular nodes
- e.g., 1s (no nodes), 2s (one radial node), 3s (two radial nodes)

### p orbitals (l = 1)

- Dumbbell shaped; three orientations: p_x, p_y, p_z
- **1** angular node (a plane through the nucleus)
- `n − 2` radial nodes

### d orbitals (l = 2)

- Five orientations: d_xy, d_xz, d_yz, d_x²−y², d_z²
- Cloverleaf (4 lobes) for d_xy, d_xz, d_yz, d_x²−y²; d_z² has two lobes + torus
- **2** angular nodes
- `n − 3` radial nodes

### f orbitals (l = 3)

- Seven orientations
- **3** angular nodes
- `n − 4` radial nodes

## Node Counting Rule

```
Total nodes   = n − 1
Radial nodes  = n − l − 1
Angular nodes = l
```

## Orbital Energies

- **Hydrogen (one electron)**: E_n = −13.6 eV / n²  → energy depends only on n.
- **Multielectron atoms**: penetration and shielding split (n, l) energies:
  - s < p < d < f within a shell (on average)
  - Aufbau order: 1s 2s 2p 3s 3p 4s 3d 4p …

## Why Shape Determines Bonding

Bond strength depends on **orbital overlap**. For two AOs to combine strongly:

1. **Energy match** — similar AO energies
2. **Symmetry match** — compatible nodal properties
3. **Good overlap** — favorable spatial orientation and distance

Head-on (σ) overlap is generally stronger than side-on (π) overlap because
density accumulates along the internuclear axis.

## Worked Example: Nodes in a 3p Orbital

**Problem.** How many radial and angular nodes does a 3p orbital have?

**Solution.**
- n = 3, l = 1
- Angular nodes = l = 1
- Radial nodes = n − l − 1 = 3 − 1 − 1 = 1
- Total nodes = n − 1 = 2 ✓ (1 radial + 1 angular)

## Practice Problems

1. Give the four quantum numbers for a 2p_y electron.
2. How many radial nodes has a 4d orbital?
3. Which subshells exist for n = 3, and how many orbitals total?
4. Arrange by increasing energy for a multielectron atom: 3s, 3p, 3d, 4s.

### Solutions

1. n = 2, l = 1, m_l = −1, 0, or +1 (a specific p_y choice, e.g. m_l = 0 if p_y is the m_l=0 lobe along y), m_s = ±½. (Any valid m_l within −1…+1 and either spin is acceptable.)
2. 4d: n = 4, l = 2 → radial nodes = 4 − 2 − 1 = 1.
3. n = 3: subshells 3s (1 orbital), 3p (3 orbitals), 3d (5 orbitals). Total = 1 + 3 + 5 = 9 orbitals.
4. 3s < 3p < 3d < 4s (in most multielectron atoms, 4s fills before 3d).

## Reading

- Atkins & de Paula: atomic structure chapter.
- Levine: hydrogen atom and angular momentum chapters.
