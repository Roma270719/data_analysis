**Задание 1** — Из таблицы `customers` выберите клиентов из города Киева (`SELECT * FROM customers WHERE Location = 'Kyiv'`)

Ответ: Найдено **12 клиентов** из Киева.

**Задание 2** — Из таблицы `customers` выберите топ-3 клиента по рейтингу `Spending_Score` (`ORDER BY Spending_Score DESC LIMIT 3`)

Ответ: Топ-3 клиента по рейтингу — **99** (Boryspil), **98** (Kyiv), **94** (Kyiv).

**Задание 3** — Подсчитайте, сколько всего было продано Power Bank (`SUM(Quantity) WHERE Description = 'Power Bank'`)

Ответ: Всего продано **91** Power Bank.

**Задание 4** — Найдите полную сумму заказов, оплаченных с помощью кредитной карты (`SUM(Quantity * UnitPrice * (1 - Discount)) WHERE PaymentMethod = 'credit card'`)

Ответ: Полная сумма заказов, оплаченных кредитной картой — **8187.46**.