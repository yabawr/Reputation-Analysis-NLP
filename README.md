# Reputation-Analysis-NLP

## Описание проекта
Этот проект анализирует новостные статьи и оценивает их влияние на репутацию бизнеса. 
Используются методы обработки естественного языка (NLP) и машинного обучения (ML) для определения тональности публикаций и извлечения ключевых тем.

## Структура проекта
- **reputation_analysis_nlp.ipynb** – Jupyter Notebook с анализом данных и демонстрацией модели.
- **requirements.txt** – список зависимостей для установки.
- **labelled_newscatcher_dataset.csv** – исходными данными, используемые в проекте.

## Установка зависимостей
Перед запуском убедитесь, что у вас установлен Python 3.7+ и Jupyter Notebook.

1. Установите необходимые библиотеки:
   ```bash
   pip install -r requirements.txt
   ```

2. Загрузите модель Spacy для обработки текста:
   ```bash
   python -m spacy download en_core_web_sm
   ```

3. Запустите Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Используемые технологии
- **Python** (pandas, numpy, matplotlib, seaborn) – для анализа данных.
- **NLP** (spacy, nltk, yake, vaderSentiment) – для работы с текстом.
- **ML** (scikit-learn, RandomForestClassifier) – для моделирования.

## Как использовать проект
1. Откройте `notebook.ipynb` в Jupyter Notebook.
2. Запустите все ячейки, чтобы загрузить данные, обработать их и запустить анализ.
