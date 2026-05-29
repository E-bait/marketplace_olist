
# Анализ сроков доставки и их влияние на клиентский опыт

Реальные данные бразильского маркетплейса Olist: ~100 тысяч заказов за 2016–2018 годы.

## Анализ в Jupyter Notebook

https://github.com/E-bait/marketplace_olist/blob/main/marketplace_olist.ipynb

## Что сделано

Разобрался, как соблюдение сроков доставки влияет на оценки покупателей. Нашёл регионы, где опоздания случаются чаще всего

## Как устроен проект

1. Загрузил данные в PostgreSQL — четыре таблицы: заказы, клиенты, отзывы и платежи
2. Проверил дубликаты, пропуски, типы
3. Разбил заказы на две группы: доставленные вовремя и с опозданием
4. Сравнил средние оценки
5. Посмотрел на ситуацию по штатам, наложил на карту выручки

## Стек

Python, Pandas, SQL, Matplotlib, Superset

## Данные

[Датасет Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) Kaggle


## Дашборд

<img width="1888" height="683" alt="olist-marketplace-2026-05-29T13-01-04 416Z" src="https://github.com/user-attachments/assets/93057cf5-d5af-4096-a124-f2e6070ee28d" />


