# SheBalance-A-PCOS-Detector

**SheBalance** is a smart, AI-powered tool that detects the likelihood of **Polycystic Ovary Syndrome (PCOS)** using personal health metrics and provides **wellness guidance** including yoga, diet, and daily tips. Built with ❤️ to empower women with early insights and holistic care.


##  Try It Instantly on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Purnika19
SheBalance-A-PCOS-Detector/blob/main/pcos_detector.ipynb)

##  Key Features

*  **PCOS Risk Prediction** using ML model
*  **Interactive Health Visualizations**
*  Personalized **Yoga & Diet Tips**
*  **Cycle Tracker** to estimate next period
*  **Downloadable Health Summary**
*  **Motivational Quotes** and Daily Tips

---

##  Machine Learning Model

The prediction engine is powered by a **Random Forest Classifier**, trained on a synthetic medical dataset with features including:

* Age
* Weight
* BMI
* Pulse
* LH/FSH Hormonal Ratio
* Follicle Count (Right Ovary)

###  Why Random Forest?

* Handles non-linear relationships
* Robust to noise and overfitting
* High accuracy in classification problems

The model achieves an **accuracy of \~98% on training data**, using **standardized feature scaling** with `StandardScaler`.

##  Tech Stack

* `Python`, `NumPy`, `pandas`
* `scikit-learn` (RandomForestClassifier)
* `Gradio` for UI
* `Plotly` for radar charts
* `Lottie` for animation
* `streamlit-lottie` (optional future use)


##  Run Instructions

Simply run the notebook on Google Colab:

```bash
!pip install gradio scikit-learn pandas numpy plotly streamlit-lottie
```

Or use the **"Open in Colab"** button above 

---

##  How to Use

1. Open the notebook in Google Colab
2. Run all cells (`Runtime > Run all`)
3. Input your health details and symptoms
4. Click **Predict PCOS** to view prediction
5. Explore personalized tips and health summary
6. Use the cycle tracker for next period prediction

---

##  Sample Inputs

| Field            | Range / Type |
| ---------------- | ------------ |
| Age              | 18–40        |
| BMI              | 18.0–40.0    |
| LH/FSH Ratio     | 0.5–2.5      |
| Follicle Count   | 1–30         |
| Symptoms         | Checkboxes   |
| Last Period Date | YYYY-MM-DD   |

---

##  Outputs Provided

* PCOS risk prediction (Yes / No)
* Confidence probability
* Suggested remedy & lifestyle tip
* Yoga pose & diet advice
* Health radar chart
* Motivational quote
* Downloadable summary

---

##  Contributing

Want to improve this wellness assistant?

* Fork the repo
* Add features (e.g. history tracker, multilingual support, deep learning)
* Submit a pull request 

---

## 👩‍💻 Created With Purpose

Built by **Purnika & Pallika** to spread awareness, promote early detection, and empower every woman through tech.

---



Let me know when you've uploaded your notebook to GitHub so I can replace the Colab badge link with your actual repo URL!

```



