# Advanced Multi-Architecture Deep Learning Framework for BIRADS-Based Mammographic Image Retrieval

This repository contains the official implementation for the paper:

**Advanced Multi-architecture Deep Learning Framework for BIRADS-Based Mammographic Image Retrieval: Comprehensive Performance Analysis with Super-Ensemble Optimization**

**Authors:**  
MD Shaikh Rahman, Feiroz Humayara, Syed Maudud E. Rabbi, Muhammad Mahbubur Rashid

📄 **Journal:** Journal of Imaging Informatics in Medicine  
🔗 **Springer:** https://link.springer.com/article/10.1007/s10278-025-01770-6  
📘 **arXiv:** https://arxiv.org/abs/2508.04790

---

## 🔍 Overview

This work presents a comprehensive deep learning–based mammographic image retrieval framework for **5-class BIRADS classification**, featuring:

- Multiple CNN backbones (DenseNet121, ResNet50, VGG16)
- Advanced fine-tuning strategies
- FAISS-based similarity indexing
- Test-Time Augmentation (TTA)
- Learned and super-ensemble optimization
- Patient-exclusive evaluation protocol
- Statistical significance testing and confidence intervals

The repository provides the full experimental pipeline used in the paper.

---

## 📁 Repository Structure

├── notebooks/ # Main experiment notebook
├── data/ # Dataset instructions (no images included)
├── reports/ # Paper-ready tables, figures, and logs
├── model_weights/ # Optional pretrained weights (external download)

---

## 🧠 Dataset

The study uses the **TCIA CDD-CESM** mammographic dataset.

Due to data licensing and patient privacy, images are **not included** in this repository.

See [`data/README.md`](data/README.md) for:

- Download instructions
- Expected folder structure
- Annotation file format

---

## ⚙️ Installation

Create a Python environment and install dependencies:

```bash
pip install -r requirements.txt

```

Recommended environment

Python 3.9 or higher

PyTorch (CPU or CUDA-enabled GPU)

FAISS (CPU or GPU version depending on setup).

## Outputs and Results

The repository includes paper-aligned experimental artifacts, such as:

Retrieval performance tables (CSV / LaTeX)

Model comparison figures

Precision–recall curves

Statistical test results

Ensemble performance summaries

These files are organized under:

reports/tables/
reports/figures/

## Citation

@article{rahman2025birads,
title={Advanced Multi-architecture Deep Learning Framework for BIRADS-Based Mammographic Image Retrieval: Comprehensive Performance Analysis with Super-Ensemble Optimization},
author={Rahman, MD Shaikh and Humayara, Feiroz and Rabbi, Syed Maudud E. and Rashid, Muhammad Mahbubur},
journal={Journal of Imaging Informatics in Medicine},
year={2025},
doi={10.1007/s10278-025-01770-6}
}

## Disclaimer

This repository is intended strictly for research and educational purposes.

The methods and results presented here are not approved for clinical diagnosis or decision-making.

## License

This project is licensed under the MIT License.
See the LICENSE file for full details

## Contact

For questions, issues, or collaboration inquiries
Email: shaikhrahman25@gmail.com
