# Hacktiv8 Phase 1: Non Graded Challenge 1

Non-Graded Assignment ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada konsep Logistic Regression.

---

By [Rifky Aliffa](https://github.com/Penzragon)

## Dataset

Dataset yang digunakan dalam project ini adalah dataset stroke yang berisi 5110 baris dengan 12 kolom yang diantaranya adalah id, gender, age, hypertension, heart_disease, ever_married, work_type, residence_type, avg_glucose_level, bmi, smoking_status, dan stroke. Dataset dapat dilihat di [Kaggle](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

Keterangan kolom pada dataset ini adalah:

| Feature           | Description                                                                            |
| ----------------- | -------------------------------------------------------------------------------------- |
| id                | unique identifier                                                                      |
| gender            | "Male", "Female" or "Other"                                                            |
| age               | age of the patient                                                                     |
| hypertension      | 0 if the patient doesn't have hypertension, 1 if the patient has hypertension          |
| heart_disease     | 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease |
| ever_married      | "No" or "Yes"                                                                          |
| work_type         | "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"                   |
| Residence_type    | "Rural" or "Urban"                                                                     |
| avg_glucose_level | average glucose level in blood                                                         |
| bmi               | body mass index                                                                        |
| smoking_status    | "formerly smoked", "never smoked", "smokes" or "Unknown"                               |
| stroke            | 1 if the patient had a stroke or 0 if not                                              |

## Objectives

- Lakukan cleaning dan preprocessing terhadap data yang akan dipakai.
- Buat sebuah classification model dengan menggunakan Logistic Regression dengan stroke prediction sebagai target.
