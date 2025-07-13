# Credit Default Prediction (GiveMeSomeCredit)

Проект по предсказанию вероятности дефолта клиента с использованием данных Kaggle.

## 📁 Данные

- `GiveMeSomeCredit-training.csv`: обучающая выборка
- `GiveMeSomeCredit-test.csv`: тестовая выборка (без таргета)

## 📌 Цель

Построить модель (Logistic Regression), которая предсказывает вероятность дефолта (`SeriousDlqin2yrs`).

## 🚀 Технологии

- Python 3.10+
- pandas, scikit-learn, matplotlib
- ROC AUC, cross-validation

## 📊 Метрика

- CV ROC AUC: **0.851**

## 📂 Структура

- `notebooks/`: ноутбук с основными шагами
- `src/`: функции для предобработки
- `submission/`: финальный сабмит
