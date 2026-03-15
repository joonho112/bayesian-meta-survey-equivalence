# Structural Equivalence of Bayesian Meta-Analysis and Bayesian Survey Inference

**Complete Mathematical Theory**

JoonHo Lee | March 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19024818.svg)](https://doi.org/10.5281/zenodo.19024818)

---

**Read the book online:** [joonho112.github.io/bayesian-meta-survey-equivalence](https://joonho112.github.io/bayesian-meta-survey-equivalence/)

## Overview

This book proves that Bayesian meta-analysis with dependent effect sizes and Bayesian survey inference with clustered observations are structurally equivalent under five exactness conditions. The two frameworks share the same likelihood, posterior, sandwich variance, and design-effect diagnostic — they are a single mathematical object expressed in two notational systems.

## Contents

| Part | Chapters | Topic |
|:-----|:---------|:------|
| **I** | 1–3 | Foundations: notation, models, exactness conditions |
| **II** | 4–6 | Core equivalence: likelihood isomorphism, sandwich equivalence, posterior & CCC equivalence |
| **III** | 7–9 | Design Effect Ratios: DER framework, conservation law, boundary behavior |
| **IV** | 10–12 | Extensions: observation-level covariates, CHE model, regularity conditions, interpretation |
| **V** | 13 | Discussion and conclusions |

## Main Results

- **Theorem 1 (Likelihood Isomorphism):** The meta-analytic and survey log-likelihoods differ by a parameter-free constant.
- **Theorem 2 (Sandwich Equivalence):** The sandwich variance estimators are numerically identical across frameworks.
- **Corollary 1 (Posterior Equivalence):** The two posteriors are identical as probability measures.
- **Corollary 2 (CCC Equivalence):** Cholesky-corrected posterior draws are identical in distribution.
- **Theorem 3 (DER Transfer):** Design Effect Ratios transfer from survey inference to meta-analysis, with a conservation law: DER_mu + DER_theta = DEFF.

## Companion Papers

- Lee, J.-H. (2026a). A Bayesian hierarchical hurdle beta-binomial model for survey-weighted bounded counts and its application to childcare enrollment. arXiv preprint. [doi:10.48550/arXiv.2603.02611](https://doi.org/10.48550/arXiv.2603.02611)
- Lee, J.-H. (2026b). Design effect ratios for Bayesian survey models: A diagnostic framework for identifying survey-sensitive parameters. arXiv preprint. [doi:10.48550/arXiv.2603.07791](https://doi.org/10.48550/arXiv.2603.07791)

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Citation

Click the **"Cite this repository"** button on GitHub, or use:

```bibtex
@book{Lee2026theory,
  author    = {Lee, JoonHo},
  title     = {Structural Equivalence of {Bayesian} Meta-Analysis and {Bayesian} Survey Inference: Complete Mathematical Theory},
  year      = {2026},
  doi       = {10.5281/zenodo.19024818},
  url       = {https://doi.org/10.5281/zenodo.19024818}
}
```
