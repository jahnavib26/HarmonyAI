# HarmonyAI

## Overview

**HarmonyAI** is a machine learning project designed to classify music tracks by genre using advanced algorithms. With the rapid growth of digital music, platforms like Spotify and Apple Music need efficient ways to organize their extensive music libraries. Our project leverages both traditional and deep learning techniques to build a robust genre classification model, focusing on the well-known GTZAN dataset.

## Background

The music industry has evolved with vast libraries of tracks, making manual genre classification impractical. Music Information Retrieval (MIR) uses audio features (rhythm, pitch, timbre) to automatically classify music, significantly improving playlist management and user experience. This project builds on the advancements in MIR, applying models like Convolutional Neural Networks (CNNs) and ensemble learning techniques to improve genre classification accuracy.

## Problem Statement

With increasing complexity in audio data, traditional genre classification methods fall short. Our research focuses on two key questions:

1. **Which machine learning model best classifies music genres on the GTZAN dataset?**  
2. **Can ensemble learning outperform individual models for genre classification?**

## Objectives

1. Develop a high-accuracy genre classification model.
2. Compare traditional ML models (SVM, KNN) with advanced models (CNN, XGBoost).
3. Explore ensemble techniques to improve model accuracy.

## Dataset

**GTZAN Dataset**  
The GTZAN dataset includes 9990 tracks across 10 genres (blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae, and rock). Key features such as Mel-frequency Cepstral Coefficients (MFCC), chroma features, and spectral contrast are extracted for training the models.

## Methodology
1. **Data Preprocessing**  
   - Normalization with Min-Max scaling and genre encoding.
   - Feature extraction: MFCC, chroma features, spectral roll-off.

2. **Model Development**  
   - Baseline models: SVM, KNN, Random Forest, Logistic Regression.
   - Advanced models: CNN and XGBoost, Neural Network.
   - Ensemble learning with a Voting Classifier combining multiple models.

3. **Evaluation**  
   - Metrics: accuracy, precision, recall, F1-score, ROC AUC.
   - Final model selection based on comparative performance.
