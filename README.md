# 🚀 Machine Learning Portfolio: Forecasting & Classification

Сборник проектов по машинному обучению, охватывающий задачи регрессии, анализа временных рядов и классификации в условиях дисбаланса классов.

---

### 🔫 1. CS:GO Case Price Predictor (Regression)
**Задача:** Прогнозирование стоимости игровых предметов для долгосрочных инвестиций.
* **Цель:** Предсказать цену на 180 дней вперед, используя исторические данные Steam.
* **Key Feature:** Глубокое проектирование признаков (лаги до полугода), сравнение XGBoost vs CatBoost.
* **Результат:** MAPE **11.69%**.

### 🛒 2. M5 Walmart Forecasting (Time Series)
**Задача:** Прогноз ежедневных продаж в ритейле (Big Data).
* **Цель:** Оценка спроса на 28 дней для оптимизации логистики.
* **Key Feature:** Оптимизация памяти для 59 млн строк, расчет скользящих средних, LightGBM.
* **Результат:** RMSE **1.8629**.

### 🏦 3. Bank Fraud Detection (Classification)
**Задача:** Выявление мошеннических транзакций.
* **Цель:** Создание модели классификации с упором на минимизацию ложных блокировок клиентов.
* **Key Feature:** Работа с сильным дисбалансом классов (ADASYN, class weights), тюнинг порога вероятности (Threshold Tuning).
* **Результат:** F1-Score **0.9131**.

---

## 🛠 Технический стек
* **Languages:** Python
* **Models:** CatBoost, LightGBM, XGBoost, Scikit-learn
* **Data Ops:** Pandas, NumPy, Memory Downcasting
* **Visualization:** Matplotlib, Seaborn

---
