## Анализ данных E-commerce

Проект направлен на анализ данных о покупках, чтобы понять поведение пользователей, эффективность доставки заказов и частоту покупок товаров, выявление сегментов аудитории и понимание причин потери клиентов.

## Используемые Инструменты и Библиотеки

<p>
  <kbd>Python</kbd>
  <kbd>Pandas</kbd>
  <kbd>Jupyter</kbd>
  <kbd>Matplotlib</kbd>
  <kbd>NumPy</kbd>
  <kbd>Seaborn</kbd>
  <kbd>requests</kbd>
</p>

## Описание Проекта

Решены следующие задачи:

1. Подсчет пользователей, совершивших только одну покупку.
2. Среднее количество недоставленных заказов в месяц с разбивкой по причинам.
3. Определение самого популярного дня недели для покупки каждого товара.
4. Среднее количество покупок в неделю на одного пользователя (по месяцам).
5. Когортный анализ пользователей и выявление когорты с наибольшим удержанием на 3-й месяц.
6. RFM-сегментация пользователей для оценки аудитории.

## Датасет

Датасет состоит из следующих файлов:

- `olist_customers_dataset.csv`: информация о клиентах.
- `olist_orders_dataset.csv`: информация о заказах.
- `olist_order_items_dataset.csv`: информация о товарных позициях в заказах.

## Результаты
- Пользователи с одной покупкой: 90,557 пользователей совершили только одну покупку.

- Не доставленные заказы:
   - Среднее количество заказов в месяц, не доставленных по причине "canceled": 26.0
   - Среднее количество заказов в месяц, не доставленных по причине "unavailable": 25.0

- Когорта с высоким retention:
   - Когорта: 2017-06
   - Retention на 3-й месяц: 0.39%

- RFM-сегментация пользователей:
   - Давние клиенты, спящие и недавние пользователи были выделены по давности покупок.
   - Пользователи классифицированы по частоте (редкие, нечастые, частые) и сумме покупок (малая, средняя, большая).

- Топ-5 сегментов покупателей:
   - 211 - спящие: редкие и малые покупки.
   - 311 - многообещающие: недавние пользователи с одной недорогой покупкой.
   - 111 - бездействующие: одна недорогая покупка и отсутствие повторных покупок.
   - 312 - нуждаются во внимании: недавние пользователи, средняя выручка.
   - 212 - нуждаются во внимании: недавние пользователи, средняя выручка.
     
Подробные выводы и визуализации доступны в Jupyter Notebook.
