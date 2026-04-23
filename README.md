# 🧬 Genetic Disorder Prediction using Machine Learning

A multi-class classification pipeline that predicts genetic disorder categories from patient clinical data — built with TensorFlow/Keras and scikit-learn.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-latest-blue?logo=scikit-learn&logoColor=white)
![Accuracy](https://img.shields.io/badge/Accuracy-90%25-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Overview

This project builds an end-to-end ML pipeline to classify patients into one of three genetic disorder categories based on clinical features such as symptoms, blood test results, parental gene information, and medical history.

**Target classes:**
- `0` — Mitochondrial genetic inheritance disorders
- `1` — Multifactorial genetic inheritance disorders
- `2` — Single-gene inheritance diseases

---

## 📊 Dataset

| Property | Value |
|---|---|
| Total records | 22,083 patients |
| Raw features | 45 columns |
| Features after preprocessing | 38 |
| Train / Test split | 80% / 20% |

**Key features used:**
- Patient age, gender, symptoms (1–5)
- Blood cell count, white blood cell count
- Blood test results
- Maternal/paternal gene presence
- Family history, birth defects, IVF history
- Respiratory rate, heart rate

---

## 🏗️ Project Structure
