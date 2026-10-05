# Monte Carlo Methods — Numerical Methods

Group project for **Numerical Methods** (iMAT, ICAI, Universidad Pontificia Comillas, 2025/26).
Authors (Group 4): Javier Martínez Montelongo, **Ignacio Mascarell Agúndez**, Juan Tabuyo Castell, Jaime Tuesta de Simón, Yago Vallarino Fernández-Cavada.

Study and implementation of Monte Carlo integration and its numerical behaviour:

- Integration as an expected value; run-to-run variability, sample mean and variance.
- Empirical convergence: error vs. *n* on log-log scale, order ≈ **O(n^-1/2)**.
- Acceptance–rejection (hit-or-miss) sampling.
- **Importance sampling** for peaked integrands and comparison of proposal densities.
- Comparison with deterministic quadrature (rectangle rule) in 1D and 2D; behaviour in higher dimension.
- Application (report): pricing a **European call option** by simulation, validated against the **Black–Scholes** closed form, with importance sampling for variance reduction on out-of-the-money strikes.

## Files

- `monte_carlo.ipynb` — implementations and experiments (exercises 1–20).
- `report/informe.pdf` — full report with results, figures and conclusions (Spanish).

## Run

```bash
pip install numpy scipy matplotlib
jupyter notebook monte_carlo.ipynb
```
