[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/j3les-0/DDoS-XAI-Detection/blob/main/XAI_DDoS.ipynb)

# XAI_DDoS – Explainable AI for DDoS Detection

This repository contains the code and experiments associated with the article **“Explainable Artificial Intelligence for DDoS Detection in Next-Generation Networks”**.  

The work investigates the use of **Explainable Artificial Intelligence (XAI)** techniques applied to the **detection of Distributed Denial of Service (DDoS) attacks**, with a focus on **5G networks**.  

The experiments were designed to be executed in **Google Colab**, requiring minimal setup effort.  

---

## Objectives

- Evaluate the performance of different Machine Learning algorithms for DDoS detection.  
- Apply **XAI methods** (e.g., LIME) to interpret the models and understand the contribution of features in the decision-making process.  
- Provide a **reproducible pipeline** for researchers interested in cybersecurity for next-generation networks.  

---

## Repository Structure

```
.
├── XAI_DDoS.ipynb     # Main notebook with experiments
└── README.md          # Project documentation
```

---

## Environment and Dependencies

This project is intended to be executed in **Google Colab**.  
Most dependencies can be installed directly within the notebook.  

Main libraries:  
- pandas, numpy, scikit-learn  
- matplotlib, seaborn  
- lime  

```

---

## Running the Experiments in Google Colab

1. Open the notebook in Google Colab:  
   - Upload `XAI_DDoS.ipynb` to your Google Drive.  
   - Right-click the file → Open with → Google Colaboratory.  

2. Ensure runtime is set to **Python 3**.  

3. Execute the cells in order to:  
   - Load the dataset 
   - Train and evaluate ML models  
   - Visualize results and explanations with LIME  

---

## Results

The experiments include:  
- Comparative evaluation of classifiers for DDoS detection.  
- Metrics: **Accuracy, Precision, Recall, F1-Score, Specificity**.  
- Confusion matrices and visualization of model performance.  
- Interpretability analysis with **LIME**, highlighting the most relevant features influencing predictions.  

---

## Scientific Contributions

- Demonstrates the applicability of **XAI to cybersecurity**, improving model transparency.  
- Provides a critical discussion on model interpretability in network traffic scenarios.  
- Proposes a **reproducible experimental pipeline** for researchers, easily accessible via Google Colab.  

---

## References

- Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). *“Why Should I Trust You?”: Explaining the Predictions of Any Classifier (LIME)*. KDD.  
- Official docs: [LIME](https://github.com/marcotcr/lime)  

---

## License

This project is released under the **MIT License**. See the `LICENSE` file for details.  
