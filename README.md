# Python Seminars 2026

Рабочие материалы с семинаров по Python: код, ноутбуки и датасеты, которые мы
разбирали на занятиях в течение года. Каждая папка названа по дате семинара.

## Содержание

| Дата    | Тема | Файлы |
|---------|------|-------|
| 11.04   | Работа с данными, чтение датасета | `notebook.ipynb`, `dataset.csv`, `input.txt` |
| 18.04   | Обработка текста / NLP на новостях | `news.ipynb`, `news.csv`, `stopwords-ru.txt` |
| 25.04   | Анализ данных по трекам Spotify | `songs.ipynb`, `spotify_data_clean_exJOvg` |
| 23.05   | Titanic: предобработка и модель | `titanic.ipynb`, `train_titanic.csv` |
| 13.06   | Статистика | `statistics.ipynb`, `train_data.csv` |
| 15.06   | FastAPI + SQLModel, SQLite | `main.py`, `university.db` |

В корне также лежат `main.py` (генерация перестановок) и `input.txt`.

## Запуск

Ноутбуки открываются в Jupyter / VS Code. Для семинара 15.06:

```bash
pip install fastapi sqlmodel uvicorn
uvicorn main:app --reload
```
