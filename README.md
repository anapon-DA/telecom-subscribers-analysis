# Определение перспективного тарифа сотовой связи на основании анализа поведения абонентов и показателей выручки

[Ссылка на проект](https://nbviewer.org/github/anapon-DA/projects/blob/main/Telecom%20Subscriber%20Data%20Analysis/telecom-subscriber-data-analysis.ipynb) :point_left:

Клиентам оператора сотовой связи предлагаются два тарифных плана. Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов.

Предоставлены данные:

- `users.csv` — информация о пользователях (включает возраст, дату подключения, название тарифа, город абонента);
- `calls.csv` — информация о звонках;
- `messages.csv` — информация о сообщениях;
- `internet.csv` — информация об интернет-сессиях;
- `tariffs.csv` — информация о тарифах.

| [Рендер проекта на `nbviewer`](https://nbviewer.org/github/anapon-DA/projects/blob/main/Telecom%20Subscriber%20Data%20Analysis/telecom-subscriber-data-analysis.ipynb) | [Проект на `github`](https://github.com/anapon-DA/projects/blob/main/Telecom%20Subscriber%20Data%20Analysis/telecom-subscriber-data-analysis.ipynb) |
| --- | --- |
| **корректный переход по внутренним ссылкам в оглавлении проекта** | статичный вариант |

# Выводы

- несмотря на то, что пользователи "Смарт" чаще превышают лимиты своего тарифного пакета и чаще доплачивают за услуги сверх него, больше выручки генерируют пользователи тарифа "Ультра";
- cредняя выручка пользователей тарифа "Ультра" оказалась статистически значимо больше средней выручки пользователей тарифа "Смарт" — 2070 рублей против 1244 рублей;
- cтатистически значимых различий между выручкой пользователей из Москвы и других регионов выявлено не было, она в среднем равна 1500 рублям;
- при разработке новых тарифных планов следует учесть, что большое количество пользователей используют свыше 30 Гб интернета в месяц, практически все абоненты при этом укладываются в 1000 минут и 125 смс в месяц.

# Статус проекта

:white_check_mark: Завершен

# Инструменты

`Matplotlib`
`Pandas`
`Python`
`SciPy`
