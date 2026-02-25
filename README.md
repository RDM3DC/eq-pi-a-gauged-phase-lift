# πₐ-Gauged Phase-Lift (adaptive unwrap + invariants)

**ID:** `eq-pi-a-gauged-phase-lift`  
**Tier:** derived  
**Score:** 61  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
\theta_R(t_k) = \theta(t_k) + 2\pi_a(t_k)\,m_k,\quad w_a[\gamma]:=\sum_k m_k,\quad b_a[\gamma]=(-1)^{w_a}
$$

## Description

Generalizes Phase-Lift unwrapping from fixed 2π to adaptive 2πₐ: sheet jumps happen in units of the local identification length. Derives πₐ-gauged winding w_a and ℤ₂ shadow parity b_a. Novel: the unit of winding is no longer constant, coupling topology to a geometry field.

## Assumptions

- z(t) ≠ 0 along the path (no singularity crossings).
- π_a(t) > 0 everywhere (positive phase-period field).
- Nearest-sheet rule is unambiguous (no exact midpoints between sheets).

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
