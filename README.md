# Hi, I'm Majid Ghandali

**Independent Researcher in Computational Number Theory**  
Tehran, Iran  
ORCID: [0009-0001-1097-1770](https://orcid.org/0009-0001-1097-1770)

> Exact structural mechanisms in recursive sequences over finite fields:  
> half-period involutions, rank-block scalar propagation, character-sum cancellation,  
> and arithmetic identities linking Fibonacci/Lucas sums to CM elliptic curves.

---

### Research Program

My work develops a unified structural framework for quadratic character sums attached to Fibonacci and Lucas sequences. The central objects are:

- The companion matrix \( A \in \mathrm{GL}_2(\mathbb{F}_p) \)
- The rank of apparition \( z(p) \) and the rank index \( i_p \)
- Half-period involutions \( A^{T/2} \equiv -I \)
- Rank-block scalar propagation via the multiplier \( \Lambda \)
- Exact cancellation of full-period character sums \( S_p \)

The program systematically connects these mechanisms to Frobenius traces of CM elliptic curves and to classical Jacobsthal sums.

---

### Core Research Series

#### 1. CM Elliptic Curves and Trace Identities
**Repository:** [fibonacci-cm-elliptic](https://github.com/Majid-Ghandali/fibonacci-cm-elliptic)  
**Manuscript:** *Quadratic Residuosity in Fibonacci Sequences: Arithmetic Structure via CM Elliptic Curves and Twisted Character Sums*  
**Software DOI:** [10.5281/zenodo.18764803](https://doi.org/10.5281/zenodo.18764803)

Main identity: for primes inert in \( \mathbb{Q}(\sqrt{5}) \),
\[ S_p = \sum_{n=1}^{p+1} \chi_p(F_n) = -a_p(E), \]
where \( E: y^2 = x^3 - 4x \).

---

#### 2. Half-Period Involutions in Inert Lucas Sequences
**Repository:** [half-period-involutions-in-inert-lucas-sequences](https://github.com/Majid-Ghandali/half-period-involutions-in-inert-lucas-sequences)  
**Manuscript DOI:** [10.5281/zenodo.22149586](https://doi.org/10.5281/zenodo.22149586)  
**Software DOI:** [10.5281/zenodo.22118430](https://doi.org/10.5281/zenodo.22118430)

Two exact cancellation mechanisms:
1. Half-period translation induced by the central involution \( A^{T/2} \equiv -I \)
2. Scalar propagation across rank blocks via the rank multiplier \( \Lambda \)

---

#### 3. Rank Index Two and Jacobsthal Sums
**Repository:** [fibonacci-character-sums-index-two](https://github.com/Majid-Ghandali/fibonacci-character-sums-index-two)  
**Manuscript DOI (v1.0.2):** [10.5281/zenodo.23339521](https://doi.org/10.5281/zenodo.23339521)  
**Software DOI:** [10.5281/zenodo.23263041](https://doi.org/10.5281/zenodo.23263041)

Explicit evaluation of
\[ S(p) = \sum_{j=1}^{z(p)} \chi_p(F_j) \]
in the rank-index-two case \( i_p = 2 \), reduced to classical Jacobsthal sums in both split and inert regimes.

---

#### 4. Full Rank of Apparition
**Repository:** [fibonacci-character-sum-full-rank](https://github.com/Majid-Ghandali/fibonacci-character-sum-full-rank)

Closed-form sign evaluation of the Fibonacci character sum for primes with full rank of apparition, via primitive-root parametrization.

---

#### 5. Even-Rank Reflection and Rank-Block Phenomena
**Repositories:**  
- [fibonacci-even-rank-reflection-selection](https://github.com/Majid-Ghandali/fibonacci-even-rank-reflection-selection)  
- [fibchar-rank-blocks](https://github.com/Majid-Ghandali/fibchar-rank-blocks)

Character-twisted reflection in even-rank Fibonacci blocks, index-dependent weighted reflection, surviving midpoint fixed points, and scalar collapse under rank-block decomposition.

---

### Ongoing & Next Directions

- **Density formulae** for specific rank-index classes (especially inert index-two primes), building on GRH-conditional frameworks (Roskam–Chen) and exact structural constraints already established.
- Extension of half-period and rank-block mechanisms to broader families of Lucas sequences.
- Systematic comparison of cancellation thresholds across different arithmetic regimes (doubly-inert, singly-inert, split).

---

### Technical Approach

All mathematical claims are proved in the manuscripts.  
Repositories supply:
- Pure-Python / Numba verification pipelines
- Exact-arithmetic diagnostics
- Full evidence archives with SHA-256 checksums
- Zenodo-archived releases for long-term reproducibility

**Stack:** Python · Numba · SymPy · NumPy · LaTeX · GitHub Actions · Zenodo

---

### Contact

- Email: [majid.ghandali@gmail.com](mailto:majid.ghandali@gmail.com)
- ORCID: [0009-0001-1097-1770](https://orcid.org/0009-0001-1097-1770)
- Zenodo: [Search “Majid Ghandali”](https://zenodo.org/search?q=Majid%20Ghandali)

---

<div align="center">

*Exact structures first. Numerics second. Reproducibility always.*

</div>