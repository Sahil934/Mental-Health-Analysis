# Multimodal Depression Detection Models

This repository contains four Jupyter notebooks implementing depression detection using different modalities: facial expressions, text transcripts, voice features, and a multimodal fusion approach.

All models are trained and evaluated on the following datasets:

* **DAIC-WOZ Dataset**
* **Extended DAIC Dataset**

These datasets are widely used multimodal corpora for depression detection, collected from clinical interviews.

---

## Models Overview

### Text Model (`TEXT_MODEL.ipynb`)

* **Final Model Selected**: TF-IDF Ensemble
* **Accuracy**: 0.6364
* **F1 Score**: 0.7361

---

### Voice Model (`VOICE_MODEL.ipynb`)

* **Final Model Selected**: Ensemble
* **Accuracy**: 0.7273
* **F1 Score**: 0.7273

---

### Facial Model (`FACIAL_MODEL.ipynb`)

* **Final Model Selected**: Ensemble
* **Accuracy**: 0.7143
* **F1 Score**: 0.7100

---

### Fusion Model (`FUSION_MODEL.ipynb`)

* **Final Model Selected**: Attention-Based Fusion
* **Accuracy**: 0.8636
* **F1 Score**: 0.8600
