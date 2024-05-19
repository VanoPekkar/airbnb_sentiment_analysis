## Описание

Проект выполнялся как часть курса ODS Natural Language Processing course (stream 6, spring 2024)

Мы сравнили две LLM модели (BERT и GPT-3.5) с классическими ML-моделями (логистическая регрессия и наивный Байес) для предсказания тональности (бинарной) отзывов на AirBnB. Подробные детали и результаты можно найти в нашем отчете

## Структура репозитория

```bash
├── Notebooks
│   ├── 1_data_join.ipynb - создание датасета
│   ├── 2_cleaning.ipynb - очистка данных
│   ├── 3_preprocessing.ipynb - предобработка
│   ├── 4_topic_modeling.ipynb - тематическое моделирование
│   ├── 5_top2vec.ipynb - тематическое моделирование
│   ├── 6_naive_bayes.ipynb - обучение наивного байесовского классификатора
│   ├── 7_logistic_regression.ipynb - обучение логистической регрессии
│   ├── 8_BERT.ipynb - обучение BERT
│   └── 9_ChatGPT.ipynb - предсказание про помощи ChatGPT
├── README.md
└── Report.pdf - отчет
```