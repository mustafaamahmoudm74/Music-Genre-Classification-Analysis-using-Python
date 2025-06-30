🎵 **SPOTIFY MUSIC GENRE CLASSIFICATION & ANALYSIS**

---

### 🌟 **Overview**

This project presents a comprehensive analysis and classification of Spotify music tracks based on their audio features. Leveraging the Spotify dataset, we aim to understand the relationship between musical attributes and genres, clean and preprocess the data, conduct exploratory analysis, and build predictive models to classify tracks by genre.

---

### 🎯 **Objectives**

The key questions addressed in this project include:

* 🎵 How do musical features vary by genre?
* 🎼 What are the trends in track popularity and energy over the years?
* 🔍 Can we classify songs accurately into genres using machine learning models?
* ✨ Which model provides the best performance in predicting genre?

---

### 🔧 **Tools and Technologies**

* **Python** 🦖: pandas, numpy, seaborn, matplotlib, scikit-learn
* **PyCaret**: Low-code ML model comparison and evaluation
* **LightGBM** and **SVM**: High-performance classification models
* **Jupyter Notebook**: Data analysis and visualization environment
* **Joblib / Pickle**: Model persistence

---

### 📂 **Project Structure**

#### 1. **Data Cleaning & Preprocessing** 🧹

* Removed duplicate and null values
* Dropped non-essential columns (IDs, names)
* Converted release dates into years and filtered by range (1985-2020)
* Normalized numerical features using MinMaxScaler
* Encoded categorical genres and subgenres numerically

#### 2. **Exploratory Data Analysis (EDA)** 🔍

* Distribution of popularity across genres
* Relationship between acoustic features (e.g., tempo, energy, valence)
* Year-wise trends in energy and valence
* Heatmaps, scatter plots, boxplots, and cluster maps used for visual insights

#### 3. **Feature Engineering**

* Standardized numerical attributes
* Created genre and subgenre mappings
* Removed outliers and non-popular tracks

#### 4. **Model Training & Evaluation** 🏋️‍♂️

* Trained and compared various classifiers:

  * Random Forest
  * Naive Bayes
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors
  * Gradient Boosting
  * LightGBM
* Used accuracy, precision, recall, and F1-score to evaluate model performance
* Best model: **SVM** (Highest accuracy on test data)

#### 5. **Deployment**

* Saved best models using `joblib` and `pickle`
* Final model is ready for inference on new songs

---

### 🔑 **Key Findings**

* 🌹 **Dance pop and hip hop** are the most frequent subgenres in the dataset.
* 🌟 **Track popularity** tends to increase with energy and valence (happy, upbeat songs).
* ⏳ **Energy and valence** increased over time, reflecting changing music trends.
* 🎵 **Genre characteristics** are distinguishable using acoustic features, aiding classification.
* ✨ **SVM** and **LightGBM** provided the best predictive power for classifying genres.

---

### 📊 **Dataset Description**

* Source: Spotify audio dataset (csv format)
* Key attributes:

  * Audio features: tempo, loudness, danceability, energy, etc.
  * Track details: name, artist, release year
  * Popularity scores
  * Playlist genre and subgenre

---

### 🚀 **Future Enhancements**

* 🧰 Add deep learning models (LSTM or CNN on audio waveforms)
* 📊 Incorporate lyrical sentiment analysis
* ⏳ Deploy web app using Streamlit or Flask for real-time prediction
* 🤖 Create Spotify API integration for live track classification

---

### 📧 **Contact**

**Mustafa Mahmoud**

* 📢 Email: \[[mustafaamahmoud0774@gmail.com](mailto:mustafaamahmoud0774@gmail.com)]
* 👥 LinkedIn: \[[https://www.linkedin.com/in/mustafamahmoudm74/](https://www.linkedin.com/in/mustafamahmoudm74/)]

---

### 🙏 **Acknowledgments**

Thanks to Spotify for dataset availability and to open-source contributors for the tools and libraries used in this project.
