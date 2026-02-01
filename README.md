# AV-Multimodal-Anomaly-Detection

A multimodal deep learning project for anomalous event detection that combines **spatio-temporal video signals** with **acoustic patterns** to flag irregular events in surveillance / monitoring-style environments.  
(Repo focus: audio-visual fusion for anomaly detection; code is notebook-based.)

---

## Why this matters
Most anomaly detection pipelines rely on vision alone, which can miss events that are **audible but visually subtle** (or visually ambiguous). This project uses **audio + video** to increase signal coverage and reduce false alarms in noisy real-world scenes.

---

## What’s inside

### Key ideas
- **Video stream** → spatio-temporal representation (frame sampling, motion/temporal context)
- **Audio stream** → time-frequency representation (e.g., log-mel spectrogram)
- **Fusion** → combines both modalities to produce an **anomaly score** (or class prediction)
- **Evaluation** → compare predicted anomaly scores vs labels, visualize failure cases

### Repository structure
- `Codings/`  
  Notebooks for preprocessing, feature extraction, training, and evaluation.
- `Initial Reports/`  
  Early planning / experiments / iterations.
- `Final Report and PPT/`  
  Final writeup + presentation material.

---
Maintained by **DHARKIVE STUDIO**
conda activate av-anomaly
pip install -r requirements.txt
