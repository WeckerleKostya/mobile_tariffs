# mobile_tariffs
Клиентам предлагают два тарифных плана:
    «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, **какой тариф приносит больше денег**.
    Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов. В вашем распоряжении данные 500 пользователей «Мегалайна»:
    кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод, какой тариф более выгодно рекламировать.
    
**Основные инструменты:** `Python`, `Pandas`, `Matplotlib`

**Направление деятельнсоти:** `Маркетинг-аналитик`, `Fraud-аналитик`, `Data Analyst`

# ВЫВОД

Из формального теста следует, что средняя выручка с абонента тарифа "Ультра" выше. На первый взгляд этого вывода может быть достаточно для того, чтобы направить деньги на рекламу именно на тариф "Ультра". В среднем абонент тарифа "Ультра" приносит больше выручки, чем абонент тарифа "Смарт", но вероятнее всего и привлечь абонента тарифа "Ультра" будет сложнее (например, потому что просто нет много людей способных оплачивать такой дорогой тариф). Таким образом, для принятия окончательного решения нужно понимать не только сколько принесет новый абонент тарифа, но и сколько средств необходимо потратить на его привлечение. Если мы исходим из предположения, что на одну и ту же сумму рекламного бюджета мы привлечем одинаковое количество абонентов любого из двух тарифов, то однозначно надо вкладывать в рекламу тарифа "Ультра", но есть опасения, что привлекать такого абонента дороже (т. е. за одну и ту де сумму рекламного бюджета мы привлечем абонентов тарифа "Ультра" намного меньше, чем абонентов тарифа "Смарт").

Таким образом, при условии равной эффективности рекламных кампаний с точки зрения количества привлеченных клиентов можно сделать вывод, что стоит вкладываться в рекламу тарифа "Ультра".
