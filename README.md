# MLAFP-XN: Leveraging neural network model for development of antifungal peptide identification tool

> **"A neural network-based approach for identifying active antifungal peptides with high precision using multi-feature fusion and SHAP interpretation."**

📄 **Published in**: *Heliyon (Cell Press, Elsevier)*  
📅 **Year**: 2024  
🔗 **DOI**: [10.1016/j.heliyon.2024.e37820](https://doi.org/10.1016/j.heliyon.2024.e37820)  
🌐 **Journal Homepage**: [Heliyon - Cell Press](https://www.cell.com/heliyon)  
🖥️ **Live Demo Web Server**: [Launch Tool](https://immediate-rash-hire.anvil.app/)

---

## 🧠 Abstract

Infectious fungi have become an increasing global concern. Antifungal peptides (AFPs) offer a promising, selective, and low-toxicity mechanism for eliminating fungal pathogens. To support effective drug development, precise identification of therapeutic AFPs is essential.

This work proposes **MLAFP-XN**, a deep learning-based strategy for classifying active antifungal peptides from sequence data. It leverages eight advanced feature extraction techniques and applies **Extreme Gradient Boosting (XGB)** for selecting the top 500 features. After evaluating 24 machine learning classifiers, we selected the four most effective models based on rigorous performance benchmarks. Notably, the MLAFP-XN framework achieved up to **99.48% accuracy** on independent test sets. We also developed an interactive web server to support community access and utilized **SHAP** for interpreting feature importance in a biologically meaningful way.

---

## 🧪 Key Contributions

1. 📊 **Comprehensive Feature Engineering**: Applied **eight sequence-based feature extraction methods** on a non-redundant, expanded dataset of 8,743 sequences.
2. ⚙️ **Feature Selection**: Leveraged **XGBoost** to select the top **500 informative features** based on importance ranking.
3. 🧠 **Deep Learning Classification**: Developed the **MLAFP-XN** neural network model for robust and high-accuracy AFP classification.
4. 🌐 **Web Tool Deployment**: Built a fully functional **web server** to demonstrate AFP prediction in real time: [Try the Model](https://immediate-rash-hire.anvil.app/)

---

## 📁 Repository Structure
MLAFP-XN-main/
├── Antifp_DS1, 2, 3(main).zip     # Zipped dataset
├── D1 dataset code.ipynb          # Jupyter notebook for dataset 1
├── d1_fungal.ipynb                # Another notebook for dataset 1
├── d2 code.ipynb                  # Notebook for dataset 2
├── dataset 3 main.ipynb           # Notebook for dataset 3
├── README.md                      # Existing README


conda create -n mlaffp-xn python=3.10
conda activate mlaffp-xn
pip install -r requirements.txt
