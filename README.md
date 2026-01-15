# 🔧 Predictive Maintenance: Remaining Useful Life (RUL) Prediction

## 📌 Project Overview

This project focuses on **Predictive Maintenance** using machine learning techniques to estimate the **Remaining Useful Life (RUL)** of industrial equipment. Specifically, we work with multivariate time-series sensor data from turbofan aircraft engines to predict how many operational cycles remain before an engine fails.

The objective is to build a **regression-based predictive model** that can estimate RUL using historical sensor readings, enabling proactive maintenance decisions and preventing unexpected failures.

---

## 🏭 Domain and Field of Study

- **Dataset Domain:** Aerospace Engineering (Aircraft Engine Health Monitoring)
- **Application Area:** Prognostics and Health Management (PHM)
- **Methodology:** Data Science / Machine Learning / Predictive Analytics
- **Use Case:** Predictive Maintenance / Condition-Based Maintenance

---

## 📊 Dataset Description

This project uses the **NASA C-MAPSS Turbofan Engine Degradation Dataset**, which is a standard benchmark dataset in predictive maintenance research.

- Source: NASA
- Link: https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data

The dataset contains:
- Multiple engines
- Each engine has:
  - 3 operational settings
  - 21 sensor measurements
  - A time index called `cycle`
- Each engine runs from a healthy state until failure.

### ⚠️ Important Note About Data Storage

The **full dataset is NOT included in this repository** due to size and good version control practices.

Instead:
- The dataset is linked above.
- A **small sample file** is included for inspection purposes (if required).
- The complete project is **fully reproducible**.



