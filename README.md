# NASA Near-Earth Objects (NEO) — Naive Bayes Classifier

A statistical machine learning project classifying whether Near-Earth Objects are potentially hazardous using a Naive Bayes model built from scratch and validated against scikit-learn.

## 📊 Results

| Model | Accuracy |
|-------|----------|
| Naive Bayes (Scratch) | **95.42%** |
| Naive Bayes (sklearn) | 94.56% |

> Note: Accuracy is inflated due to class imbalance (~84% not hazardous). Recall is a more meaningful metric here.

## 📁 Files

| File | Description |
|------|-------------|
| `NASA_NEO_NaiveBayes3.ipynb` | Main notebook with EDA, model training & evaluation |
| `Stats-Project_report.docx` | Full written report |
| `NEO Presentation.pdf` | Slide deck |
| `Results.json` | Model results summary |

## 🔍 Features Used

Absolute Magnitude, Estimated Diameter, Relative Velocity, Miss Distance, Minimum Orbit Intersection, Orbit Uncertainty, Eccentricity, Semi Major Axis, Inclination, Orbital Period

## 🗑️ Features Removed

Correlated/duplicate-unit columns removed to reduce independence assumption violations: Jupiter Tisserand Invariant, Asc Node Longitude, Perihelion Distance, Perihelion Arg, Aphelion Dist, Mean Anomaly, Mean Motion.

## 🛠️ Tools

Python · NumPy · pandas · scikit-learn · Jupyter Notebook

## Dataset
[NASA Near-Earth Objects dataset](https://www.kaggle.com/datasets/shrutimehta/nasa-asteroids-classification) — 4,687 samples

[NASA Near-Earth Objects dataset](https://www.kaggle.com/datasets/shrutimehta/nasa-asteroids-classification) — 4,687 samples
