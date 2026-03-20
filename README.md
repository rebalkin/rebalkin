# Hi, I'm Reuven!

I'm a theoretical physicist finishing a postdoc at **UC Santa Cruz** (PhD from TU Munich), working on **AI/ML research** and quantitative modeling. My background is in mathematical modeling, analytical derivations, and large-scale numerical methods, with projects in ML theory, natural language processing, and financial modeling.

I'm currently seeking **AI/ML research and quantitative research roles** in the Bay Area.

Publications: [INSPIRE](https://inspirehep.net/authors/1657351?ui-citation-summary=true) · [Google Scholar](https://scholar.google.com/citations?user=W6hH4GAAAAAJ&hl=en)

---

## 🤖 AI / ML Projects

### [Neural Network Theory](https://github.com/rebalkin/ML/tree/main/superposition)
- Analytical and numerical study of **loss landscapes and phase transitions** in toy models of superposition (inspired by Elhage et al., *Toy Models of Superposition*)
- Derived closed-form conditions for transitions between dedicated-dimension and superposition representations in ReLU networks; validated numerically

### [Automatic Keyword Tagging for hep-ph Papers](https://github.com/rebalkin/ML/tree/main/hep_ph_keyword_tagging)
- Multilabel classification of hep-ph abstracts predicting INSPIRE-style keywords
- Built end-to-end pipeline: data collection via the INSPIRE API, label normalization, TF-IDF feature extraction, One-vs-Rest logistic regression, threshold tuning on a dedicated CV set
- Evaluated with micro- and macro-averaged F1; peak micro-F1 ~0.48; systematic analysis of label imbalance and sparsity

---

## 📈 Quantitative Finance

### [Heston Stochastic Volatility Model](https://github.com/rebalkin/Quant-portfolio/blob/main/notebooks/heston.ipynb)
- Implemented the full Heston model pipeline: Monte Carlo simulation, semi-analytic pricing via characteristic functions, and calibration to live market option chain data (AMZN, GOOG, AMD)
- Validated MC convergence against analytic prices; relative pricing error reaches 10^-3 to 10^-4 at 10^5 paths, consistent with expected 1/sqrt(N) scaling; calibrated parameters with separate fits for short- and long-dated expiries
- Built modular library (`black_scholes`, `heston`, `heston_calib`) for reusable pricing and calibration workflows

More projects in [Quant-portfolio](https://github.com/rebalkin/Quant-portfolio). Background includes the Erdos Institute quant finance bootcamp and independent study in derivatives pricing.

---

## 🔭 Physics Research

My research focuses on **beyond the Standard Model (BSM) phenomenology**: collider signatures of new physics, effective field theories, dark matter, and Higgs physics. Work involves analytical calculations, large-scale Monte Carlo simulations, and statistical analysis pipelines extracting rigorous conclusions from complex simulation outputs.

### Selected Research Repos
- [ALPs-in-kaon-decays](https://github.com/rebalkin/ALPs-in-kaon-decays) - Mathematica code for ALP phenomenology in kaon decays ([paper](https://link.springer.com/article/10.1007/JHEP02(2026)011))
- [B-and-D-decays-in-FASER-and-CHARM](https://github.com/rebalkin/B-and-D-decays-in-FASER-and-CHARM) - Signal predictions for B and D meson decays at FASER and CHARM ([paper](https://link.springer.com/article/10.1007/JHEP04(2025)071))

---

## 🛠️ Technical Stack

`Python` · `PyTorch` · `NumPy / SciPy` · `Mathematica` · `C++` · `LaTeX` · `Git`

---

## 📬 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/reuven-balkin-261848170/)
