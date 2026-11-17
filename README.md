# 🌦️ Historical Climate Analytics: England

An interactive, dark-themed exploratory data analysis (EDA) and Streamlit web application examining historical weather patterns, temperature extremes, seasonal cycles, and atmospheric correlations across England (2006–2017).

---

## 🚀 Live Demo & Access
* **GitHub Repository:** [anumhb](https://github.com/anumhb)
* **Local Execution:** Follow the instructions below to run the dashboard locally.

---

## 📊 Key Features & Analytical Workflow
1. **Univariate Analysis:** Explores individual distributions of temperature, humidity, and wind speed.
2. **Bivariate Relationships:** Analyzes the near-perfect correlation between actual and apparent temperature ($r = 0.99$) and the inverse relationship between temperature and humidity ($r = -0.63$).
3. **Seasonal Trends:** Tracks predictable annual temperature cycles, identifying July as the warmest month (~22.96°C) and January as the coldest (~0.81°C).
4. **Interactive Filtering:** Dynamic sidebar controls allowing slice-and-dice exploration by region/place and custom date ranges.
5. **Dark Theme UI:** Custom CSS-injected dark interface with zero top header whitespace and clean, modular question-by-question layout.

---

## 🛠️ Project Structure
```text
Weather_Data_Analysis/
│
├── Climate of England _ Professional Reforms.csv  # Dataset
├── app.py                                         # Main Streamlit Dashboard application
├── requirements.txt                               # Project dependencies
├── README.md                                      # Project documentation
└── Weather_Data_Analysis.ipynb                    # Exploratory Data Analysis notebook