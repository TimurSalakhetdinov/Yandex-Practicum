# Yandex-Practicum
Данный репозиторий содержит проекты, которые я выполнил во время обучения на курсе Data Scientist в Yandex Practicum.

**Список проектов:**

[**1. Кредитный скоринг для банка**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/01.%20Credit%20score)

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, 
которая оценивает способность потенциального заёмщика вернуть кредит банку.

[**2. Исследование объявлений о продаже квартир**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/02.%20Real%20estate)

В распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Необходимо определить рыночную стоимость объектов недвижимости. Задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

[**3. Определение перспективного тарифа для телеком-компании**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/03.%20Telecom%20project)

Клиентам предлагают два тарифных плана компании «Мегалайна»: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.

Необходимо сделать предварительный анализ тарифов на небольшой выборке клиентов. В распоряжении данные 500 пользователей «Мегалайна»: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Необходимо проанализировать поведение клиентов и сделать вывод — какой тариф лучше.

[**4. Анализ данных о компьютерных играх магазина Steam**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/04.%20Games%20project%20)

Интернет-магазин «Стримчик» продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

[**5. Построение модели классификации для выбора наилучшего тарифа**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/05.%20ML%20mobile%20tariff)

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В нашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф.

[**6. Отток клиентов**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/06.%20Beta-Bank%20)

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Нам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Построим модель с предельно большим значением F1-меры - нужно довести метрику до 0.59. Потом проверим F1-меру на тестовой выборке.

Дополнительно измерим AUC-ROC, сравнивайте её значение с F1-мерой.

Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

[**7. Выбор локации для скважины**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/07.%20Oil%20well%20Rosneft)

Проект предназначен для добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину.

Нам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Построим модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализируем возможную прибыль и риски техникой Bootstrap.

[**8. Восстановление золота из руды**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/08.%20Gold%20processing)

Подготовим прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В нашем распоряжении данные с параметрами добычи и очистки.

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

[**9. Защита данных клиентов страховой компании**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/09.%20Insurance%20company%20data)

Нужно защитить данные клиентов страховой компании «Хоть потоп». Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. 

Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. 

[**10. Определение стоимости автомобилей**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/10.%20Autos%20cost%20estimation)

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В нашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Нам нужно построить модель для определения стоимости.

Заказчику важны:
* качество предсказания;
* скорость предсказания;
* время обучения.

[**11. Прогнозирование заказов такси**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/11.%20Time%20series%20forecast%20)

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Построим модель для такого предсказания.

[**12. Проект для Викишоп**](https://github.com/TimurSalakhetdinov/Yandex-Practicum/tree/main/12.%20Project%20for%20Wikishop%20)

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

Обучим модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок.