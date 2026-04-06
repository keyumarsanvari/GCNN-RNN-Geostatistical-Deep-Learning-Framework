<img width="378" height="133" alt="image" src="https://github.com/user-attachments/assets/2544dd74-8d22-48d5-9fe9-b33ff55347f4" />

# Hybrid Geostatistical–Deep Learning (GCNN–RNN) Framework for Geochemical Prediction

**Author:** Keyumars Anvari  
**Supervisor:** Professor Jörg Benndorf  
**Affiliation:** Department of Mine Surveying and Geodesy, TU Bergakademie Freiberg

---

## 📄 Overview

This repository demonstrates the **GCNN–RNN Hybrid Framework** developed for the paper:

> **Hybrid Geostatistical and Deep Learning Framework for Geochemical Characterization in Historical Mine Tailings**
> , Scientific Reports, Nature Publishing Group, 2025.
DOI: 10.1038/s41598-025-19441-5

We combine **classical geostatistics** (spatial covariance modeling via ordinary kriging) with **deep learning** (convolutional and recurrent neural networks) to produce **accurate, robust, and spatially-aware predictions of geochemical properties** in mining environments, even under sparse or noisy data conditions.

The framework is **modular, flexible, and adaptable** to geospatial prediction tasks where spatial correlation and limited samples present challenges.

---

## 🛠️ Key Features

✅ **End-to-End Workflow:** From data preparation and geostatistical feature extraction (variogram, covariance) to deep learning model training and prediction.  
✅ **Hybrid Architecture:** Integrates kriging-derived spatial structures within a neural network (Conv1D + BiLSTM layers).  
✅ **Flexible Input:** Compatible with 2D or 3D spatial datasets and continuous properties (e.g., metal concentrations).  
✅ **Reproducible Demo:** Includes a documented code template with synthetic data for easy experimentation.  
✅ **Visualization:** Scripts for exploratory data analysis, prediction visualization, and model evaluation.

---

## 📚 Requirements

Please install the following Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy tensorflow
```

---

## 🚀 Getting Started

1️⃣ **Clone the repository:**

```bash
git clone https://github.com/keyumarsanvari/GCNN-RNN-Geostatistical-Deep-Learning-Framework.git
cd GCNN-RNN-Geostatistical-Deep-Learning-Framework
```

2️⃣ **Replace demo data** in the main script with your own dataset (coordinates and geochemical concentrations).

3️⃣ **Adjust variogram parameters and neural network hyperparameters** as appropriate for your spatial context.

4️⃣ **Run the pipeline** to preprocess data, train the GCNN–RNN model, predict, and visualize geochemical distributions.

---

## 📝 Citation

If you use this framework in your research, please cite:

Anvari, K., Benndorf, J., Gerber, G. et al. Hybrid geostatistical and deep learning framework for geochemical characterization in historical mine tailings. Sci Rep 15, 35004 (2025). https://doi.org/10.1038/s41598-025-19441-5

---

## 📬 Contact

For questions, collaborations, or contributions, please contact:

**Keyumars Anvari**  
Department of Mine Surveying and Geodesy  
TU Bergakademie Freiberg

📧 [keyumarsanvari@gmail.com](mailto:keyumarsanvari@gmail.com)  
📧 [Keyumars.Anvari@doktorand.tu-freiberg.de](mailto:Keyumars.Anvari@doktorand.tu-freiberg.de)

---

## ⭐ Contributing

Contributions and enhancements are welcome! If you find bugs or wish to extend functionalities (e.g., additional variogram models, new network layers), please open an issue or submit a pull request.






