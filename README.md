# Классификация обращений в службу поддержки

## Задача
Многоклассовая классификация текста: по `Document` предсказать `Topic_group`.
8 категорий: Hardware, Access, Miscellaneous, HR Support, Purchase, Internal Project, Storage, Administrative rights.

## Датасет
`all_tickets_processed_improved_v3.csv` — колонки `Document`, `Topic_group`. Классы несбалансированы.

## Запуск
1. Установить зависимости: `pip install -r requirements.txt`
2. Запустить ноутбук: `jupyter notebook support_tickets.ipynb`
3. Посмотреть результаты в MLflow: `mlflow ui --backend-store-uri sqlite:///mlflow.db`

## Результаты
См. сводную таблицу в ноутбуке.
