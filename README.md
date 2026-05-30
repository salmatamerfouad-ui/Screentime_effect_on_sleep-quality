# Screentime_effect_on_sleep-quality
Predicts sleep quality in Egyptian university students using semi-supervised learning on merged IEEE &amp; survey datasets, with Logistic Regression, Random Forest, SVM, Decision Tree, and Naive Bayes classifiers.

# Sleep Quality Predictor

Predicts sleep quality in Egyptian university students based on screen time and sleep habits.

## Data
Two datasets merged: an IEEE social media addiction dataset + a custom student survey. Features: age, gender, academic level, daily screen time, and sleep hours.

## How It Works
1. Cleans and aligns both datasets
2. Uses a semi-supervised approach — trains on labeled data, then assigns confident pseudo-labels to unlabeled records
3. Trains and compares 5 classifiers: Logistic Regression, Random Forest, SVM, Decision Tree, and Naive Bayes
