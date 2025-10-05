# 🪐 Astro Zeter: AI-Based Exoplanet Detection Using NASA Kepler and TESS Data  

# [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

---

## 🌌 Project Overview  

This project leverages Artificial Intelligence (AI) and Machine Learning (ML) to automatically identify exoplanets — planets orbiting stars beyond our solar system — using real datasets from NASA’s Kepler and TESS missions.  

The system combines two approaches:  
1. Machine Learning (Random Forest) – trained on tabular data containing orbital and stellar parameters.  
2. Deep Learning (1D Convolutional Neural Network) – trained on light curve data (flux variations over time) fetched via the *Lightkurve* library.  

By detecting characteristic dips in star brightness (transits), the model can accurately predict whether a given observation corresponds to a true exoplanet or a false positive.  

---

## 🚀 Key Features  

- Uses open-source datasets from NASA Exoplanet Archive  
- Automated data cleaning and preprocessing pipeline  
- Random Forest for feature-based classification  
- 1D CNN for time-series (light curve) analysis  
- Visualization of confirmed vs. false positive signals  
- Accuracy evaluation and confusion matrix plots  

---

## 🧠 How It Works  

1. Dataset Collection:  
   - Downloaded confirmed and candidate exoplanet data from the NASA Exoplanet Archive.  
   - Extracted key features like koi_period, koi_depth, and koi_disposition.  

2. Light Curve Processing:  
   - Used Lightkurve to fetch real telescope data.  
   - Cleaned, normalized, and phase-folded light curves.  

3. Model Training:  
   - Random Forest for tabular data classification.  
   - CNN for detecting periodic brightness dips in light curves.  

4. Evaluation:  
   - Compared predictions, plotted confusion matrices, and visualized example curves.  

---

## 🧩 Tools and Technologies  

- Language: Python  
- Libraries: TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib, Lightkurve  
- Environment: Google Colab (GPU-accelerated)  
- Data Source: [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu)  

---

## 🌍 Impact  

This project demonstrates how AI can accelerate scientific discovery by analyzing large-scale astronomical data. It reduces manual effort, increases accuracy, and provides a scalable framework for identifying new exoplanets from future missions.  

---

## 🤖 AI Tool Usage Declaration  

AI tools (specifically ChatGPT – GPT-5) were used to assist in drafting project documentation, structuring the development workflow, and creating explanation text.  
All code implementation, model design, and data analysis were performed manually by the project developer.  

---

## 🧑‍💻 Team Members

Abhinav V R  
B.Tech in Computer Science Engineering  
NSS College of Engineering, Palakkad  
[LinkedIn](https://www.linkedin.com/in/abhinavvr) | [GitHub](https://github.com/abhinav-v-r)  

Beneeta Justice
MSc. Statistics  
K.E. College Kottayam  
[LinkedIn](https://www.linkedin.com/in/beneeta-justice) | [GitHub](https://github.com/Beneeta-Justice)  

Sreepadh I S
8th Std
Vidyodaya School Thevakkal, Ernakulam
[GitHub](https://github.com/coolsreepadh)  

---

## ⭐️ Acknowledgments  

- NASA Exoplanet Archive for open datasets  
- Lightkurve Project for providing access to Kepler/TESS light curves  
- Google Colab for computational support  
