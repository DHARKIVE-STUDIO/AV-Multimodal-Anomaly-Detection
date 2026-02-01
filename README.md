# AV Multimodal Anomaly Detection (Autonomous Vehicle)

Multimodal anomaly detection for **autonomous driving scenes** using **camera video + audio** signals to identify unusual, risky, or out-of-distribution events (e.g., unexpected objects, abnormal driving contexts, near-miss patterns, rare acoustic cues like sirens/horns, etc.).  
This repo focuses on **audio-visual fusion** and evaluation workflows for AV anomaly scoring.

> Goal: improve robustness beyond vision-only detection by leveraging **complementary audio cues** and fusion strategies.

---

## Why multimodal for autonomous vehicles?
Autonomous driving isn’t just about what you can see. Audio provides early or complementary signals:
- Sirens/horns often matter **before** visual confirmation
- Visual cues can be occluded (traffic, weather, glare), while audio may still carry signal
- Fusion can reduce false alarms in visually ambiguous scenes and improve sensitivity to rare events

---

## What this project does
- Builds a pipeline to ingest and align **video clips + audio** (paired in time)
- Extracts features from both modalities:
  - **Video**: frame/clip-based features (spatio-temporal context)
  - **Audio**: time-frequency features (e.g., log-mel spectrogram)
- Learns an **anomaly score** (or anomaly class) using unimodal baselines + multimodal fusion
- Evaluates results with quantitative metrics and qualitative failure-case review

---

## Repository structure
- `Codings/`  
  Notebooks for preprocessing, feature extraction, training, and evaluation.
- `Initial Reports/`  
  Early experiment notes and iterations.
- `Final Report and PPT/`  
  Final write-up and presentation materials.
  
---

Maintained by **DHARKIVE STUDIO**
