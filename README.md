# Exohub Matrix 🌌

**Astronomy Club Summer Project '25**

Welcome to the **Exohub Matrix** repository! This project explores the intersection of astronomy, spectroscopy, and advanced machine learning to analyze planetary atmospheres and predict the habitability of distant exoplanets.

## 📑 Table of Contents
- [Overview](#overview)
- [Key Features & Modules](#key-features--modules)
- [Datasets](#datasets)
- [Results](#results)
- [Team](#team)

## 🔭 Overview
Exohub Matrix aims to apply modern data science and deep learning techniques to astronomical data. The project is divided into three major learning and application phases:
1. **Atmospheric Composition Spectroscopy:** Utilizing mathematical models (Beer-Lambert Law, Rydberg Equation) to understand spectral fingerprints.
2. **Deep Learning for Computer Vision:** Building a Convolutional Neural Network (CNN) from scratch for facial emotion recognition to master data preprocessing, augmentation, and neural network architectures.
3. **Planetary Ranking System:** Leveraging ensemble machine learning models to calculate the **Earth Similarity Index (ESI)** of exoplanets observed by the Kepler and TESS missions.

## 🚀 Key Features & Modules

### 1. Spectroscopy Analysis
- **Pipeline:** Built in Python using `scipy.signal.find_peaks`.
- **Functionality:** Stitches blue/red arm spectrograph data, inverts flux, detects atmospheric absorption lines, and matches them against the NIST Atomic Spectra Database to calculate elemental abundance.

### 2. CNN for Facial Emotion Recognition
- **Architecture:** Custom Deep CNN (Conv2D, MaxPooling, Dropout, Dense) with ~2.34M trainable parameters built using **TensorFlow/Keras**.
- **Data Augmentation:** Implemented `RandomHorizontalFlip`, `RandomRotation`, and `ColorJitter` to handle class imbalances and improve model generalization.
- **Classification:** Categorizes images into 7 distinct emotional states.

### 3. Exoplanet Ranking System (ESI)
- **Modeling:** Implemented **Random Forest Regressor** and Support Vector Regressor (SVR) using `scikit-learn`.
- **Features:** Trained on planetary radius, orbital period, equilibrium temperature, and stellar host characteristics.
- **Performance:** The Random Forest model achieved an outstanding **$R^2$ score of >0.99**.

## 📊 Datasets
- **PEPSI / PIRANGA Projects:** Exoplanet transit survey data for spectral analysis.
- **Facial Emotion Dataset:** Grayscale 48x48 pixel images categorized into 7 emotion classes.
- **Kepler & TESS Datasets:** Verified planetary and stellar parameters used for mapping habitability.

## 🏆 Results
Using our optimized Random Forest pipeline, we predicted the ESI for confirmed exoplanets. The top identified Earth-like candidates include:
* **Kepler-296 e** (ESI: ~0.922)
* **TRAPPIST-1 e** (ESI: ~0.892)
* **Kepler-1512 b** (ESI: ~0.892)

## 👥 Team

**Mentors:**
* Rishabh Kumar
* Rishabh Verma
* Toshika Kamble
* Mayank Pattnaik

**Mentees:**
* Tanmay Shukla
* Aman Pal
* Astha Yadav
* Abhinav Bhardwaj
* Dalima
* Harshit Pandey
* Haryashva Gupta
* Ishaan Dasgupta
* Mahi Mittal
* Lalit Meena
* Mayank Agrawal
* Mihir Tejaswi
* Mishthi Sharma
* Nikhil Patel
* Saket Garg
* Pranjali Deshpande
* Tripti Kushwaha
