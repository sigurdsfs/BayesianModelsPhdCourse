# Bayesian Models: Minds, Brains & Behavior 🧠📊

Welcome to the course materials for **Bayesian Models of Minds, Brains, & Behavior**, hosted at Hvidovre Hospital / Copenhagen, May 2025.

This repository contains interactive notebooks, Quarto slides, and Binder support to help you learn Bayesian modeling in a hands-on and intuitive way.

---

## 🚀 Launch in Binder

Click below to launch an interactive Jupyter environment (no installation required):

[![Launch on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/main?urlpath=lab)

> Replace `YOUR_GITHUB_USERNAME/YOUR_REPO_NAME` with your actual GitHub info.

---

## 📂 Folder Structure

```
/notebooks/
    beta_distribution_demo.ipynb   ← interactive demo with sliders
/slides/
    lecture2.qmd                   ← Quarto Reveal.js slides
/images/
    uniform_theta.png              ← any image assets
environment.yml                    ← Binder environment config
README.md                          ← this file
```

---

## 📦 Dependencies

All dependencies are handled automatically via Binder using the provided `environment.yml` file.

To run locally:

```bash
conda env create -f environment.yml
conda activate bayesian-models
jupyter lab
```

---

## 📚 Contents

- **Lecture 2**: Basics of Bayesian Analysis
- Estimating hidden variables (e.g., cognitive ability)
- Visualizing beliefs using Beta distributions
- Updating priors with data using Bayes' Rule
- Interactive visualizations (via `ipywidgets`)
- Intro to MCMC and analytic solutions

---

## ✍️ Author

**Ollie Hulme**  
Senior Researcher, Copenhagen University Hospital, Amager & Hvidovre  
Associate Professor, University of Copenhagen  
[olliehulme.net](https://olliehulme.net) • [@olliehulme](https://twitter.com/olliehulme)

---

## ❤️ License

This material is free to use and adapt under a Creative Commons Attribution license (CC-BY 4.0).
