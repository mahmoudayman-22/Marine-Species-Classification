# Marine Species Classification & OOD Detection

A computer vision pipeline for underwater organism classification and **Out-of-Distribution (OOD) Detection** using the **FathomNet** dataset with **PyTorch**.

---

##  Project Overview
This project addresses multi-class image classification of marine life while integrating a safety mechanism to identify novel, unseen species in real-world underwater applications using threshold-based OOD detection.

---

##  Key Features
- **Custom vs. Transfer Learning:** Built a custom 3-block CNN from scratch and benchmarked it against pre-trained **ResNet** and **MobileNet** backbones.
- **Fine-Tuning Strategies:** Conducted systematic evaluations across **Feature Extraction**, **Partial Fine-Tuning**, and **Full Fine-Tuning** regimes.
- **Out-of-Distribution (OOD) Detection:** Designed a threshold-based score mechanism to detect and flag previously unobserved marine species.
- **Evaluation:** Analyzed classification performance using precision, recall, and detection accuracy metrics.

---

##  Tech Stack & Tools
- **Framework:** PyTorch
- **Core Libraries:** Torchvision, Albumentations, NumPy, Matplotlib, Scikit-learn
- **Dataset:** FathomNet Underwater Dataset
- **Language:** Python

---

##  Author
**Mahmoud Ayman Zaki**
- **Email:** mahmoudayman340@gmail.com
- **GitHub:** [@mahmoudayman-22](https://github.com/mahmoudayman-22)
