# goit-rdb-hw-05

Домашнє завдання №5 з реляційних баз даних.

## Dataset

У роботі використано датасет **Olist Brazilian E-commerce** з Kaggle.

Основні таблиці:
- customers
- orders
- order_items
- products
- sellers

## Що виконано

Дані з CSV спочатку завантажуються у raw-таблиці PostgreSQL, після чого створюється typed-схема з потрібними типами даних і зв'язками між таблицями.

У роботі реалізовано:
- CTE-chain для розрахунку customer-level features;
- RFM, cohort quarter, rolling AOV, cancellation rate та preferred category;
- recursive CTE для referral chain;
- Materialized View та UNIQUE INDEX;
- REFRESH MATERIALIZED VIEW CONCURRENTLY;
- порівняння запитів за допомогою EXPLAIN ANALYZE.

## Запуск

Відкрити notebook `goit_rdb_hw_05_Herasymiuk_Yuliia.ipynb` у Google Colab.

Для коректного запуску використовується runtime version **2026.07**.

Після відкриття notebook виконати всі комірки зверху вниз.
