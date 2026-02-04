# Titanic EDA and sklearn Pipeline

Небольшой проект по разведочному анализу данных и построению ML‑пайплайна на датасете Titanic.

## Что внутри
- Короткий EDA с базовыми визуализациями.
- Feature engineering: `NameLen`, `FamilySize`, `IsAlone`, `Title`.
- Пайплайн `sklearn` с обработкой пропусков и one‑hot кодированием.
- Оценка качества на holdout и 5‑fold cross‑validation.

## Файлы
- `titanic_pipeline.ipynb` — основной ноутбук.

## Как запустить
1. Установить зависимости:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

2. Запустить ноутбук:

```bash
jupyter notebook sem04_visualization_task.ipynb
```

## Метрика
В качестве основной метрики используется `accuracy` — доля правильных предсказаний.
