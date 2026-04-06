# Cognitive Fatigue in LLMs — Project Page

> Central project page for the Cognitive Fatigue research program.

**Live site → [rijumarwah.github.io/llmfatigue](https://rijumarwah.github.io/llmfatigue)**

---

## About

Autoregressive language models degrade during long-horizon generation — producing repetitive text, losing instruction adherence, and exhibiting unstable entropy. This isn't a rare edge case; it's a structural property of how transformer decoders operate over extended sequences.

We formalize this as **cognitive fatigue**: a measurable, within-run deterioration in instruction adherence, representation stability, and predictive calibration. We operationalize it through three lightweight inference-time signals — prompt attention decay, embedding drift, and entropy deviation — and aggregate them into the **Fatigue Index (FI)**, a normalized, model-agnostic diagnostic computable token-by-token at inference time without retraining.

The key insight: fatigue has internal signatures detectable in attention patterns, hidden states, and output distributions *before* text quality visibly degrades. This makes it possible to monitor reliability online and intervene in time.

This research program spans:
- A **full paper** (ICML 2026) formalizing the theory, axioms, and empirical validation across nine models
- An **interactive demo** (AAAI 2026) — Chatsparent — that surfaces fatigue in real time and enables retrain-free interventions

---

## Papers

**[1] Cognitive Fatigue in Autoregressive Transformers: Formalization and Measurement**  
Riju Marwah, Ritvik Garimella, Vishal Pallagani, Atishay Jain, Michael Stewart, Amit Sheth  
*ICML 2026* · [PDF](#) · [arXiv](#)

**[2] Chatsparent: An Interactive System for Detecting and Mitigating Cognitive Fatigue in LLMs**  
Riju Marwah, Vishal Pallagani, Ritvik Garimella, Amit Sheth  
*AAAI 2026 Demo* · [PDF](https://arxiv.org/pdf/2601.11526) · [Demo video](https://www.youtube.com/watch?v=ktqkZyYWDDE)

---

## Authors

| Name | Affiliation |
|------|-------------|
| [Riju Marwah](http://rijumarwah.github.io) | GGSIPU · AIISC |
| [Ritvik Garimella](https://ritvikg.com) | AIISC |
| [Vishal Pallagani](https://vishalpallagani.github.io) | AIISC |
| [Atishay Jain](https://www.linkedin.com/in/atishay-jain-b90268296/) | AIISC · IIT Kanpur |
| [Michael Stewart](https://www.linkedin.com/in/mcs46/) | AIISC |
| [Amit Sheth](https://amit.aiisc.ai) | AIISC |

---

## Repository structure

```
llmfatigue/
├── index.html        # Project page (single-file, no build step)
├── README.md         # This file
├── LICENSE           # MIT
└── CITATION.cff      # Machine-readable citation
```

The project page is a single self-contained `index.html` — no dependencies, no build tools, no frameworks. Push and it works.

---

## Editing the page locally

```bash
git clone https://github.com/rijumarwah/llmfatigue.git
cd llmfatigue
open index.html        # or just drag into a browser
```

Push changes to `main` — GitHub Pages redeploys automatically within ~60 seconds.

---

## Code

Implementation of the Fatigue Index and experiments will be released in a separate repository upon paper publication. This repo is for the project page only.

---

## Citation

```bibtex
@inproceedings{marwah2026cognitivefatigue,
  title     = {Cognitive Fatigue in Autoregressive Transformers:
               Formalization and Measurement},
  author    = {Marwah, Riju and Garimella, Ritvik and
               Pallagani, Vishal and Jain, Atishay and
               Stewart, Michael and Sheth, Amit},
  booktitle = {Proceedings of the International Conference
               on Machine Learning (ICML)},
  year      = {2026}
}

@inproceedings{marwah2026chatsparent,
  title     = {Chatsparent: An Interactive System for Detecting
               and Mitigating Cognitive Fatigue in {LLMs}},
  author    = {Marwah, Riju and Pallagani, Vishal and
               Garimella, Ritvik and Sheth, Amit},
  booktitle = {Proceedings of the AAAI Conference on
               Artificial Intelligence},
  year      = {2026}
}
```

---

## Contact

Riju Marwah — [marwah.riju@gmail.com](mailto:marwah.riju@gmail.com)  
Artificial Intelligence Institute of South Carolina
