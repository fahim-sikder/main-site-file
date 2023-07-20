---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Welcome to Todays Meeting"
summary: ""
authors: ["Md Fahim Sikder"]
tags: ["fairness", "bengali", "computer vision"]
categories: ["Research"]
date: 2023-07-14T18:03:27+02:00
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # theme = black, white, league, beige, sky, night, serif, simple, solarized
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  #   Available highlight themes listed in: https://highlightjs.org/static/demo/
  #   Use lower case names and replace space with hyphen '-'
  highlight_style: github-light

  diagram: true
  diagram_options:
    # Mermaid diagram themes include: default,base,dark,neutral,forest
    theme: base

  # RevealJS slide options.
  # Options are named using the snake case equivalent of those in the RevealJS docs.
  reveal_options:
    controls: true
    progress: true
    slide_number: c/t  # true | false | h.v | h/v | c | c/t
    center: true
    rtl: false
    mouse_wheel: true
    transition: fade  # none/fade/slide/convex/concave/zoom
    transitionSpeed: default  # default/fast/slow
    background_transition: slide  # none/fade/slide/convex/concave/zoom
    touch: true
    loop: false
    menu_enabled: true
---

# Welcome to todays Meeting

Deep Dream Group


---

## Agenda

1. Text Classification Tasks!
2. Possible ICCIT!
3. Fair Data Generation Project!
4. Explainable Audio Classification!
---

## Text Classification Task

1. Finished part of Introduction
2. Finished abstract
3. Finished all the experiments
4. Need to write all the remaining parts

---

# Fair Bengali Handwritten Character Generation

Presented by: **Md Fahim Sikder**

Deep Dream Group

---

## Motivation

1. Data Fairness is needed!
2. Trustworthy AI!
3. Not much research has been done in Bengali!

---

## Research Problem

1. How can we create an Image dataset for Bengali domain?
2. How we can generate fair generative models?

---

## Data Fairness

1. Real world data is full of bias
   1. COMPAS case in the USA
<!-- ![alt text](racial.png) -->

---

## Data Fairness

<!-- ![alt text](racial.png) -->
<img src="racial.png"  width="60%" height="30%">

---

## Bangla Sensitive Dataset

<img src="dataset1.jpg"  width="60%" height="30%">

---

## Bangla Sensitive Dataset

<img src="sensitive-bangla.jpg"  width="70%" height="40%">

---
## Generative Models

1. GAN-based
2. Diffusion-based

---

## Possible Contribution

1. Bangla Sensitive datasets
2. Generative model
3. Interpretability / Explainability

---

## Related Works

See zotero library.

---

## Explainable Audio Classification

---

## Idea

1. Train an audio classifier (preferably cnn/transformers based)
2. Explain the results
3. Compare different explainable techniques

---

## Possible Contribution

1. Unique model
2. Explainability

---

## Datasets

1. https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess
2. https://github.com/Jakobovski/free-spoken-digit-dataset/tree/master

---

## Related Works

See zotero library.