## Структура репозитория
Проекты из данного репозитория были выполнены в ходе обучения по программе "Аналитик данных" в Яндекс.Практикуме.

| Проект | Описание  | Используемые инструменты|
|:------------- |:---------------| :-------------|
| [Исследование данных сервиса Яндекс.Музыка (Сравнение предпочтений пользователей двух городов)](https://github.com/linapomix/data_analytics/blob/main/yandex_music/ "Перейти к проекту") | Сравнение музыкальных предпочтений пользователей Яндекс.Музыки из Москвы и Петербурга в разное время суток и дни недели|  *Python*, *Pandas* |
|[Исследование надёжности заёмщиков (Анализ банковских данных)](https://github.com/linapomix/data_analytics/blob/main/credit_scoring/ "Перейти к проекту") |Основываясь на датасет кредитной организации выявлены зависимости между целями кредита, семейным положением, количеством детей заёмщика и выполнением обязательств по выплате кредита в срок.     |       *Python*, *Pandas*, предобработка данных  |
| [Продажа квартир в Санкт-Петербурге (Анализ рынка недвижимости)](https://github.com/linapomix/data_analytics/blob/main/realty/ "Перейти к проекту") |Используя данные сервиса Яндекс.Недвижимость определены типичные предложения на рынке и выявлены различия между центром Санкт-Петербурга, его районами и Ленинградской областью.  |     *Python, Pandas, Matplotlib, NumPy, Pymystem3,* исследовательский анализ данных, визуализация данных, предобработка данных |
|[Выбор оптимального тарифа для телеком компании (Статистический анализ поведения пользователей)](https://github.com/linapomix/data_analytics/blob/main/telekom_tariffs/ "Перейти к проекту") |Проанализированы поведения абонентов двух тарифов, проверены гипотезы о различии выручки тарифов, выручки от абонентов из Москвы и регионов. Определен оптимальный тариф для телеком компании     |         *Python, Pandas, Matplotlib, NumPy, SciPy,* описательная статистика, проверка статистических гипотез  |
| [Определение для интернет-магазина предпочтительных видеогир для закупки (Статистический анализ рынка платформ и видеоигр)](https://github.com/linapomix/data_analytics/blob/main/games/ "Перейти к проекту") | Определены ключевые параметры, характерные популярным играм в разных регионах мира. Охарактеризован средний пользователей разных регионов. На основании этого выявлены наиболее привлекательыне для дальнейшей закупки видеоигры.    |       *Python, Pandas, NumPy, Matplotlib,* предобработка данных, исследовательский анализ данных, описательная статистика, проверка статистических гипотез   |
|[Анализ убытков приложения ProcrastinatePRO+ (Анализ рентабельности маркетинговых кампаний)](https://github.com/linapomix/data_analytics/blob/main/marketing_app/ "Перейти к проекту") | Проведен анализ данных мобильного приложения. Проанализирована окупаемость рекламы, построены графики метрик LTV, CAC и ROI. Определены слабые места в маркетинговой кампании. |       *Python, Pandas, Matplotlib, Datetime, Seaborn* когортный анализ, юнит-экономика, продуктовые метрики   |
|[Проверка гипотез по увеличению выручки в интернет-магазине (A/B тестирование)](https://github.com/linapomix/data_analytics/blob/main/ab_online_shop/ "Перейти к проекту") | В проекте приоритизированы гипотезы по фреймворкам ICE и RICE. Далее проведено A/B-тестирование, оценены показатели кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитаны статистические значимости различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа было принято решение остановить тест и зафиксировать отсутствие различий между группами.            |    *Python, Pandas, Matplotlib, SciPy, Datetime, Seaborn,* A/B-тестирование, проверка статистических гипотез   |
|[Исследования рынка общепита в Москве (Анализ точки входа для нового заведения)](https://github.com/linapomix/data_analytics/blob/main/caffees/ "Перейти к проекту") | Исследован рынок общественного питания на основе открытых данных на предмет входа заведения с официантами-роботами, определены наиболее распространенные вида заведений и их характерные черты, построены графики с помощью библиотек python Seaborn, Plotly.express.  По итогам исследования подготовлена презентации для инвесторов.        |      *Python, Pandas, Seaborn, Plotly, Plotly.express, SciPy, Pymystem3, Counter, BytesIO, Requests, Matplotlib,* визуализация данных |
| [Анализ пользовательского поведения в мобильном приложении (A/B тестирование)](https://github.com/linapomix/data_analytics/blob/main/aab_mobile_app/ "Перейти к проекту") | Для приложения по продажи продуктов питания проанализирована воронка событий, построены графики с помощью библиотек python Seaborn, Plotly.express, Plotly.go, сформированы и проверены гипотезы по смене цвета шрифта главной страницы приложения. Проверена точность распределения групп тестирования, принято решение по смене шрифта по результатам A/A/B-теста.        |      *Python, Pandas, Matplotlib, Seaborn, Datetime, Plotly, Plotly.express, Plotly.go, Math, SciPy,* событийная аналитика, продуктовые метрики, A/B-тестирование, проверка статистических гипотез, визуализация данных |
| [Анализ товарного ассортимента интернет-магазина](https://github.com/linapomix/data_analytics/blob/main/ecommerce/ "Перейти к проекту") | Для магазина товаров для дома и сада выделены и проанализированы товарные категории. Выбраны наиболее продаваемые артикулы и рассмотрены общие тенденции среднего чека и выручки. Даны рекомендации по возможному улучшению финансового положения компании.       |      *Python, Pandas, Pymystem3, Scipy, Plotly, Datetime, Counter, Numpy, Matplotlib,*  предобработка данных, проверка статистических гипотез, визуализация данных |
