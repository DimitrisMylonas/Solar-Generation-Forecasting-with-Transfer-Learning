# 🌞 Solar Generation Forecasting with Transfer Learning  


## 🔍 Introduction
The **global energy demand** is steadily increasing, leading to an urgent need for **renewable energy** adoption. Solar energy, though abundant, is highly dependent on **weather conditions** and remains **difficult to predict**. 

To address this challenge, this thesis explores the use of **deep learning models trained on large datasets** to **transfer knowledge** and improve solar energy predictions, even in **regions with limited data**.

---

## 🛠️ Project Description
The main objective of this project is:
- **Development of pretrained Convolutional Neural Networks (CNNs)**
- **Fine-tuning models for time-series forecasting**
- **Comparison of deep learning models with statistical baselines**
- **Performance evaluation based on RMSE & MAE metrics**

The project is structured as follows:
1. **Data preprocessing**: Cleaning, normalizing, and structuring time-series energy and weather data.
2. **Model construction**: Designing **deep learning architectures** using **CNNs**.
3. **Transfer learning**: Training models on **large-scale datasets** and testing on **unseen data**.
4. **Performance evaluation**: Comparing **pretrained models** with statistical baselines.

---

## 📊 Dataset & Preprocessing
The dataset consists of two main sources:
1. **Weather Data**: Hourly temperature and solar radiation measurements from **2015-2019**.
2. **Solar Generation Data**: Hourly solar energy generation data from various **European countries**.

### 🏗️ Preprocessing Steps:
✔️ Handling **missing values** using interpolation and statistical techniques.  
✔️ **Feature selection** & normalization of numerical values.  
✔️ Application of **windowing methods** for time-series forecasting.  
✔️ **Country selection** based on data quality and diversity.

---

## ⚙️ Methodology
The following machine learning models were implemented:

### **🔹 Pretrained Deep Learning Models**
- **Three CNN architectures** trained on multiple European countries.
- Hyperparameter optimization using **Optuna framework**.
- **Dropout & BatchNormalization** layers for better generalization.
- Fine-tuning techniques to **improve learning rate & training efficiency**.

### **🔹 Baseline Models**
- **Exponential Smoothing**
- **Theta Method**
- **Naïve Mean & Naïve Drift**
- **Simple CNN trained per country**

Pretrained models were tested on:
- **Countries in the training set**
- **Completely unknown countries**

**📌 Results showed that pretrained models significantly outperform traditional methods when trained on large-scale data.**

---

## 📈 Results & Findings
Key takeaways from the experiments:

✔️ **Pretrained deep learning models** performed significantly better than models trained individually per country.  
✔️ **Error reduction** of up to **300%** compared to statistical baselines.  
✔️ **Deep architectures generalize better** and make **more accurate predictions** for **both known and unknown datasets**.  
✔️ **Residual layers & Dropout** improved performance, but training time remained high.  
✔️ **Predictions for unknown countries** were promising but require further optimization. 

## 🔮 Future Work
The next steps for further improvement: ✔️ Fine-tune models per country using freezing techniques.
✔️ Incorporate weather forecasts as additional features.
✔️ Optimize training time & improve model efficiency.
✔️ Test additional deep learning architectures (LSTMs, Transformers, N-BEATS).
