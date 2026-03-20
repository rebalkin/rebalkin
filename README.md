# Hi, I'm Reuven 👋

I'm a theoretical physicist finishing a postdoc at **UC Santa Cruz** (PhD from TU Munich), actively building toward **AI/ML research** and **quantitative finance**. I have a strong publication record in high-energy theory and phenomenology, and growing interests across ML theory, LLMs, and neural network representations.

Publications: [INSPIRE](https://inspirehep.net/authors/1657351?ui-citation-summary=true) · [Google Scholar](https://scholar.google.com/citations?user=W6hH4GAAAAAJ&hl=en)

---

## 🔭 Physics Research

My research focuses on **beyond the Standard Model (BSM) phenomenology** - collider signatures of new physics, effective field theories, dark matter, and Higgs physics.

Recently, my interests have shifted toward **machine learning research** broadly - including LLMs, the mathematical foundations of deep learning, how neural network representations form, and what phase transitions in toy models reveal about generalization.

### Selected Research Repos
- [ALPs-in-kaon-decays](https://github.com/rebalkin/ALPs-in-kaon-decays) - Mathematica code for ALP phenomenology in kaon decays
- [B-and-D-decays-in-FASER-and-CHARM](https://github.com/rebalkin/B-and-D-decays-in-FASER-and-CHARM) - Signal predictions for B and D meson decays at FASER and CHARM

---

## 🤖 AI / ML Projects

### Neural Network Theory
- Analytical study of **loss landscapes and phase transitions** in toy models of superposition (inspired by Elhage et al., *Toy Models of Superposition*)
- Derived closed-form conditions for transitions between dedicated-dimension and superposition representations in ReLU networks
- Manuscript in preparation

### Automatic Keyword Tagging for hep-ph Papers
- Multilabel classification of hep-ph papers using title and abstract as input, predicting keywords from a curated vocabulary derived from INSPIRE-HEP metadata
- Built a full pipeline: data collection via the INSPIRE API, label cleaning and vocabulary construction, TF-IDF feature extraction, and SGD-based logistic regression with One-vs-Rest
- Systematic sweep over regularization strength and decision thresholds; evaluated with micro- and macro-averaged F1

### Implementation Projects
- Working through Karpathy's *Zero to Hero* series - implementing backpropagation, batch norm gradients, and character-level MLPs from scratch in PyTorch
- Focus on building ground-up understanding of the mechanics of modern deep learning

---

## 📈 Quantitative Finance

I completed the **Erdos Institute quant finance bootcamp** and have been doing independent study in derivatives pricing and stochastic volatility modeling. Projects in my [Quant-portfolio](https://github.com/rebalkin/Quant-portfolio) repo include:

### Heston Stochastic Volatility Model
- Implemented the full Heston model pipeline: Monte Carlo simulation, semi-analytic pricing via characteristic functions, and calibration to live market option chain data (AMZN, GOOG, AMD)
- Validated MC convergence against analytic prices; calibrated parameters using `scipy.optimize.least_squares` with separate fits for short- and long-dated expiries
- Built modular library (`black_scholes`, `heston`, `heston_calib`) for reusable pricing and calibration workflows

---

## 🛠️ Tools & Skills

`Python` · `PyTorch` · `NumPy / SciPy` · `Mathematica` · `C++` · `LaTeX` · `Git`

Physics methods: EFT · perturbation theory · RG flow · Monte Carlo · path integrals

---

## 📬 Get in Touch

Open to AI/ML research and quantitative research roles in the Bay Area.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/YOUR_HANDLE)
