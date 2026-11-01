# Практическая работа №4 — Линейная регрессия (Вариант B)

**Студент:** Ашымбеков Акыл  
**Дисциплина:** Машинное обучение  
**Датасет:** Auto MPG

## Что сделано

- Проверка мультиколлинеарности
- Две модели LinearRegression в Pipeline
- Метрики MAE, MSE, RMSE, R²
- Коэффициенты модели
- Графики остатков и предсказаний

## Основные результаты

- Полная модель: MAE 2,467, RMSE 3,072, R² 0,824
- Модель на 3 признаках: MAE 2,460, RMSE 3,068, R² 0,825
- Главные признаки: weight и model_year

## Структура проекта

```text
ML_Practice_4/
├── data/
│   └── mpg.csv
├── notebooks/
│   └── practice_4.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Как запустить

1. Создать и активировать виртуальное окружение:

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Установить библиотеки:

```bash
pip install -r requirements.txt
```

3. Открыть `notebooks/practice_4.ipynb` в VS Code или Jupyter и выполнить **Restart & Run All**.

## Технологии

Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, Jupyter Notebook.
