# Hi, I'm Reuven!

I'm a theoretical physicist finishing a postdoc at **UC Santa Cruz** (PhD from TU Munich), transitioning into **AI/ML research**. I have a strong publication record in high-energy theory and phenomenology, and growing interests across ML theory, LLMs, and neural network representations.

Publications: [INSPIRE](https://inspirehep.net/authors/1657351?ui-citation-summary=true) · [Google Scholar](https://scholar.google.com/citations?user=W6hH4GAAAAAJ&hl=en)

---

## 🤖 AI / ML Projects

### [Neural Network Theory](https://github.com/rebalkin/ML/tree/main/superposition)
- Analytical study of **loss landscapes and phase transitions** in toy models of superposition (inspired by Elhage et al., *Toy Models of Superposition*)
- Derived closed-form conditions for transitions between dedicated-dimension and superposition representations in ReLU networks
- Manuscript in preparation

### [Automatic Keyword Tagging for hep-ph Papers](https://github.com/rebalkin/ML/tree/main/hep_ph_keyword_tagging)
- Multilabel classification of hep-ph papers using title and abstract as input, predicting keywords from a curated vocabulary derived from INSPIRE-HEP metadata
- Built a full pipeline: data collection via the INSPIRE API, label cleaning and vocabulary construction, TF-IDF feature extraction, and SGD-based logistic regression with One-vs-Rest
- Systematic sweep over regularization strength and decision thresholds; evaluated with micro- and macro-averaged F1

---

## 📈 Quantitative Finance

I completed the **Erdos Institute quant finance bootcamp** and have been doing independent study in derivatives pricing and stochastic volatility modeling. Projects in my [Quant-portfolio](https://github.com/rebalkin/Quant-portfolio) repo include:

### [Heston Stochastic Volatility Model](https://github.com/rebalkin/Quant-portfolio/blob/main/notebooks/heston.ipynb)
- Implemented the full Heston model pipeline: Monte Carlo simulation, semi-analytic pricing via characteristic functions, and calibration to live market option chain data (AMZN, GOOG, AMD)
- Validated MC convergence against analytic prices; calibrated parameters using `scipy.optimize.least_squares` with separate fits for short- and long-dated expiries
- Built modular library (`black_scholes`, `heston`, `heston_calib`) for reusable pricing and calibration workflows

---

## 🔭 Physics Research

My research focuses on **beyond the Standard Model (BSM) phenomenology** - collider signatures of new physics, effective field theories, dark matter, and Higgs physics.

### Selected Research Repos
- [ALPs-in-kaon-decays](https://github.com/rebalkin/ALPs-in-kaon-decays) - Mathematica code for ALP phenomenology in kaon decays ([paper](https://link.springer.com/article/10.1007/JHEP02(2026)011))
- [B-and-D-decays-in-FASER-and-CHARM](https://github.com/rebalkin/B-and-D-decays-in-FASER-and-CHARM) - Signal predictions for B and D meson decays at FASER and CHARM ([paper](https://link.springer.com/article/10.1007/JHEP04(2025)071))

---

## 🛠️ Tools & Skills

`Python` · `PyTorch` · `NumPy / SciPy` · `Mathematica` · `C++` · `LaTeX` · `Git`

---

## 📬 Get in Touch

Open to AI/ML research and quantitative research roles in the Bay Area.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/reuven-balkin-261848170/)
