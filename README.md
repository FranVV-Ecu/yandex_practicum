# Проекты Яндекс Практикум 



Краткое описание проектов реализованных по  образовательной программе на яндекс практикум 

## 1. Переработка данных : [Исследование надёжности заёмщиков](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/01%20Предобработка%20данных/01%20Предобработка%20данных%20.ipynb) 

Задача: Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## 2. Исследовательский анализ данных: [Исследование объявлений о продаже квартир](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/02%20Исследовательский%20анализ%20данных/02%20Исследовательский%20анализ%20данных.ipynb)

Задача: В  распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно определять рыночную стоимость объектов недвижимости. Задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

## 3. Статистический анализ данных: [Определение перспективного тарифа для телеком компании](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/03%20Статистический%20анализ%20данных/03%20Статистический%20анализ.ipynb)

Задача: «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.
Сделан  предварительный анализ тарифов на небольшой выборке клиентов. В вашем распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Проанализирован поведения клиентов и чтобы сделать вывод — какой тариф лучше.

## 4.  Сборный проект: [Исследования данных игр](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/04%20Сборный%20проект%201/04%20Сборный%20проект%201.ipynb)

Задача: Интернет-магазине «Стримчик» продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности, которая  позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
Данные до 2016 года. Представим, что сейчас декабрь 2016 г., и  планируется кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируется ли  продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.
В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

## 5. Введение в машинное обучение: [Рекомендация тарифов](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/05%20Введение%20в%20машинное%20обучение/05%20Введение%20в%20машинное%20обучение.ipynb)

Задача: Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Задача  построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
В  распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта  «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится уже проведенна.
Построенно  модель с максимально большим значением accuracy. Чтобы считать модкль приемлем нужно достичь долю правильных ответов по крайней мере до 0.75. 

## 6. Обучение с учителем: [Пргноз оттока клиентов банка](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/06%20Обучение%20с%20учителем/06%20Обучение%20с%20учителем.ipynb)

Задача: Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно строить прогноз, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.
Построен модель с предельно большим значением F1-меры. Чтобы считеть модель успешен, нужно довести метрику до 0.59..
Дополнительно измеряем AUC-ROC, сравниваем её значение с F1-мерой.
Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

## 7. Машинное обучение в бизнесе: [Определение региона, где добыча принесёт наибольшую прибыль ](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/07%20Машинное%20обучение%20в%20бизнесе/07%20Машинное%20обучение%20в%20бизнесе.ipynb)

Задача:  Постройть модель для определения региона, где добыча принесёт  Нужно решить, где бурить новую скважину.
Шаги для выбора локации обычно такие:
В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
Строят модель для предсказания объёма запасов в новых скважинах;
Выбирают скважины с самыми высокими оценками значений;
Определяют регион с максимальной суммарной прибылью отобранных скважин.
Педоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Нужно проанализировать возможную прибыль и риски техникой Bootstrap.

## 8. Сборный проект: [Модель прогноза коэффициента восстановления золота из золотосодержащей руды](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/08%20Сборный%20проект%202/08%20Сборный%20проект%202.ipynb)

Задача: Подготовить прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В  распоряжении данные с параметрами добычи и очистки.
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.
Нужно:
Подготовить данные;
Провести исследовательский анализ данных;
Построить и обучить модель.

## 9. Линейная Алгебра: [Разработка метода преобразования данных](https://nbviewer.jupyter.org/github/FranVV-Ecu/yandex_practicum/blob/master/09%20Линейная%20Алгебра/09%20Линейная%20алгебра.ipynb)

Задача: Нужно защитить данные клиентов страховой компании «Хоть потоп». Разработаем метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуем корректность его работы.

Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.
