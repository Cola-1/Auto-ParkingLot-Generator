# Automated Generation of Parking Data Sets for Underground Car Parks

<p align="center">
  <img src="assets/parking_teaser.png" alt="Parking Dataset Teaser" width="70%">
</p>

<p align="center">
  <strong>
    Jiakai Li, Yangle Liu, Zheng Rong
  </strong>
</p>

This repository provides the **open-source scene library, dataset, and generation pipeline** introduced in the paper:

**Automated Generation of Parking Data Sets for Underground Car Parks**  
SAE Technical Paper 2025-01-7191  
https://saemobilus.sae.org/papers/automated-generation-parking-data-sets-underground-car-parks-2025-01-7191

---

## 🔍 Highlights

- Automated generation of **synthetic underground parking datasets**
- Blender-based **high-fidelity virtual parking garage simulation**
- Fully **customizable objects, layouts, and styles**
- Eliminates costly **real-world data collection and manual annotation**
- Designed for **AI training and autonomous parking perception**
- Open-source assets and data for rapid reuse and extension

---

## 🧾 Abstract

Developing robust perception systems for autonomous parking requires large-scale, diverse, and accurately labeled data. However, collecting and annotating real-world data in underground car parks is expensive, time-consuming, and difficult to scale.

This project proposes an **automated synthetic data generation framework** using Blender to simulate underground parking environments. The system enables large-scale generation of high-quality training data with precise annotations, while supporting extensive customization of parking layouts, vehicles, lighting conditions, and object styles. By relying entirely on virtual simulation, the pipeline removes the dependency on real-world data acquisition.

Experimental results reported in the paper demonstrate that perception models trained on the generated synthetic datasets achieve strong performance in automatic parking tasks. To encourage reproducibility and further research, the scene library, dataset, and generation code are released as open source.

---

## 📦 Open Source Data

**Open Source Data for:**  
Automated Generation of Parking Data Sets for Underground Car Parks

**Project Purpose:**  
Provide unlimited and diversified data for AI learning through a customizable data interface. All objects can be styled and configured, enabling rapid generation of highly customized underground garage simulation datasets with multiple combinations.

**Target Users:**  
This project is primarily designed for **AI trainers, researchers, and developers** working on autonomous driving and parking perception systems.

**Download Link:**  
https://drive.google.com/file/d/1vCmuT-fqzME2EmJ8IQdTbZcGJRK32Bpi/view?usp=sharing

---

## 📁 Project Overview

- Virtual underground parking garage scene
- Automated synthetic data generation pipeline
- Configurable parking layouts, vehicles, and environmental elements
- Suitable for training perception models in autonomous parking systems

---

## 🔗 Links

- **SAE Paper:**  
  https://doi.org/10.4271/2025-01-7191

- **Related Code Repository:**  
  https://github.com/Snyard/parkinglot-generator

---

## 📜 Citation

If you find this work useful, please consider citing:

```bibtex
@techreport{li2025automated,
  title={Automated Generation of Parking Data Sets for Underground Car Parks},
  author={Li, Jiakai and Liu, Yangle and Rong, Zheng},
  institution={SAE International},
  number={2025-01-7191},
  year={2025},
  doi={10.4271/2025-01-7191}
}
