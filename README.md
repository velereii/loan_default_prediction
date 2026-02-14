# Loan Default Prediction

## Описание
Построение модели логистической регрессии для предсказания кредитного дефолта (Default = 1 / 0) клиента. Для обучения и оценки модели используется открытый датасет с Kaggle: https://www.kaggle.com/datasets/nikhil1e9/loan-default/data

## Подход
• EDA и очистка данных   
• Отбор признаков по Information Value (IV)   
• Target / One-Hot Encoding   
• Проверка линейности признаков (WoE)   
• Logistic Regression (сравнение базовой модели и class_weight='balanced')   

## Результаты
Accuracy 68%   
Recall 70%   
ROC-AUC 0.76   

## Стек
**Python | Pandas | NumPy | Matplotlib | Scikit-learn**
