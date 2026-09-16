# The LCAO Method — Handout

## 1. The Variational Principle

The variational principle states that for any trial wavefunction $\Phi$:

$$E[\Phi] = \frac{\langle \Phi | \hat{H} | \Phi \rangle}{\langle \Phi | \Phi \rangle} \geq E_0$$

where $E_0$ is the exact ground-state energy. Minimizing $E[\Phi]$ with respect to the coefficients yields the best approximation within the chosen basis set.

## 2. The Secular Equations

Substituting the LCAO ansatz into the Schrödinger equation and applying the variational principle leads to the secular determinant:

$$\det(H_{\mu\nu} - ES_{\mu\nu}) = 0$$

where $H_{\mu\nu} = \langle \phi_\mu | \hat{H} | \phi_\nu \rangle$ (Hamiltonian matrix elements) and $S_{\mu\nu} = \langle \phi_\mu | \phi_\nu \rangle$ (overlap integrals).

## 3. Symmetry Considerations

Atomic orbitals can only combine effectively when they have:

1. **Similar energies** — energy match is essential for strong mixing
2. **Significant overlap** — spatial proximity matters
3. **Compatible symmetry** — orbitals must transform according to the same irreducible representation

## 4. Homonuclear Diatomic Molecules

### H₂

- Two 1s atomic orbitals combine to form $\sigma_g$ (bonding) and $\sigma_u^*$ (antibonding)
- Ground state: $(\sigma_g)^2$, bond order = 1

### N₂

- Valence configuration involves $2s$ and $2p$ orbitals
- Ordering: $\sigma_{2s} < \sigma_{2s}^* < \pi_{2p} < \sigma_{2p} < \pi_{2p}^* < \sigma_{2p}^*$
- Bond order = 3 (triple bond)

### O₂

- Same ordering as N₂ but with more electrons
- Ground state has two unpaired electrons in $\pi_{2p}^*$ orbitals
- Predicts **paramagnetism** — a key success of MO theory over VB theory

## 5. Exercises

1. Construct the MO diagram for Li₂ and predict its bond order.
2. Explain why He₂ does not form a stable molecule using MO theory.
3. For CO, discuss how heteronuclear character affects orbital energies.

---

_Draft status:_ Placeholder content. Full derivations to be added in SVA-70.
