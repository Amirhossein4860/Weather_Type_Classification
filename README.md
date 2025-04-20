# Weather_Type_Classification
This notebook demonstrates weather type classification using only NumPy and Matplotlib. It covers the complete workflow, including downloading and preprocessing the dataset, and applying label encoding for categorical variables like location and weather type. The goal is to predict weather conditions such as Sunny, Rainy, and Snowy.

## 📌 Project Overview
This project focuses on predicting weather types based on various meteorological features using machine learning techniques. The goal is to prepare data for potential classification models while employing only basic libraries, such as **NumPy** and **Matplotlib**, for preprocessing and visualization tasks.

By exploring the relationships between weather features and types, this project highlights how preprocessing techniques like **Label Encoding** and visualization can help in weather type classification. It serves as a foundation for future machine learning applications in weather prediction.

## 📂 Dataset
The dataset used in this project contains multiple features related to weather conditions. The key attributes are:

| Column Name           | Description |
|-----------------------|-------------|
| `Temperature`         | Temperature in degrees |
| `Humidity`            | Humidity percentage |
| `Wind Speed`          | Speed of wind (km/h) |
| `Precipitation (%)`   | Precipitation level (%) |
| `Cloud Cover`         | Cloud coverage description (e.g., clear, partly cloudy) |
| `Atmospheric Pressure`| Atmospheric pressure (hPa) |
| `UV Index`            | UV Index |
| `Season`              | Season of the year (Spring, Summer, Autumn, Winter) |
| `Visibility (km)`     | Visibility in kilometers |
| `Location`            | Location (e.g., inland, coastal) |
| `Weather Type`        | Target variable, representing different weather conditions (Rainy, Cloudy, Sunny, Snowy) |

## 🔎 Data Processing Workflow

### 1️⃣ **Data Preprocessing**
- The dataset is loaded and cleaned, where categorical variables such as `Location` and `Weather Type` are encoded using **Label Encoding**.
- Non-numeric columns are transformed to ensure the dataset is entirely numeric for machine learning models.

### 2️⃣ **Exploratory Data Analysis (EDA)**
- Visualizing the relationships between features like `Temperature`, `Humidity`, and `Wind Speed` with weather types.
- Analyzing the distribution of features and target variable (`Weather Type`).

### 3️⃣ **Visualization**
- Creating visualizations using **Matplotlib** to better understand the data.
- Plots include distributions, bar charts, and scatter plots that reveal key patterns in weather data.

### 4️⃣ **Preparing Data for Modeling**
- The final dataset is ready for machine learning models, with categorical features encoded and all data transformed into numeric format.
- The workflow focuses on preparing the data rather than applying machine learning models directly in the notebook.

## 🚀 How to Run the Project

### **1️⃣ Clone the Repository**
```sh
$ git clone https://github.com/yourusername/Weather-Type-Classification.git
$ cd Weather-Type-Classification
```

### **2️⃣ Install Dependencies**
```sh
$ pip install numpy matplotlib
```

### **3️⃣ Run the Jupyter Notebook**
```sh
$ jupyter notebook
```
Open the Weather_Type_Classification.ipynb file and execute the cells to explore the data, preprocess it, and visualize the weather patterns.

## 📊 Results
- The notebook prepares the data for weather type classification, ensuring that categorical variables are encoded and the dataset is in a suitable format for machine learning models.
- Visualizations help in understanding the key relationships between features such as Temperature, Humidity, and Wind Speed with weather types.

## 📌 Future Improvements
- 🔹 Implementing machine learning models for actual weather type classification (e.g., Decision Trees, Random Forest).
- 🔹 Integrating real-time weather data for dynamic predictions.
- 🔹 Enhancing visualizations with interactive plots using Plotly or Seaborn.

## 🔚 Conclusion
This project provides an effective framework for preparing and visualizing weather data for classification tasks. Using only NumPy and Matplotlib, it demonstrates how to preprocess and analyze meteorological data, with future plans to apply machine learning algorithms for accurate weather type predictions.


