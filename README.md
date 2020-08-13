## Проекты выполненные в рамках обучения по направлению "Аналитик данных"   
**1. Предобработка данных. 	
Исследование надёжности клиентов банка**    
[`Notebook_Sprint_2_Credit_score`][2]  

**2. Исследовательский анализ данных. Анализ рынка недвижимости**     
[`Notebook_Sprint_3_real_estate`][3]

**3. Статистический анализ данных. Определение перспективного тарифа для телеком-компании**    
[`Notebook_Sprint_4_telecom`][4] 

**4. Сборный проект. Изучение рынка компьютерных игр на основе данных о продажах за 30 лет**    
[`Notebook_Sprint_5_games`][5]   

**5. Cбор и хранение данных. Исследование данных авиакомпании**    
[`Notebook_Sprint_6_fly_company`][6]


**6. Анализ бизнес-показателей. Оптимизации маркетинговых затрат для компании агрегатора услуг**    
[`Notebook_Sprint_7_web_service`][7]

[2]: https://github.com/petrushkoam/education_praktikum/tree/master/Notebook_Sprint_2_Credit_score
[3]: https://github.com/petrushkoam/education_praktikum/tree/master/Notebook_Sprint_3_real_estate
[4]: https://github.com/petrushkoam/education_praktikum/tree/master/Notebook_Sprint_4_telecom
[5]: https://github.com/petrushkoam/education_praktikum/tree/master/Notebook_Sprint_5_games
[6]: https://github.com/petrushkoam/education_praktikum/tree/master/Notebook_Sprint_6_fly_company
[7]: https://github.com/petrushkoam/education_praktikum/tree/master/Notebook_Sprint_7_web_service

### [1. Предобработка данных. Исследование надёжности заёмщиков на основе статистики о платёжеспособности клиентов банка.][2]
-	Подготовка данных для построения модели кредитного скоринга банка. 
    - предобработка данных, заполнению пропусков и категоризация данных; 
    - применение лемматизации (библиотека PyMystem3) для категоризации целей кредита;
-	Исследование влияния семейного положение и количества детей на факт возврата кредита в срок.     
***Cтек технологий: Python, Pandas, PyMystem3.***
- Результаты анализа:    
Зависимость на возврат кредита от наличия детей, семейного положения, уровня дохода, цели кредита минимальна и колеблется в пределах 2% от общего объема задолженностей 8,8%

### [2. Исследовательский анализ данных. Исследование объявлений о продаже квартир в Санкт-Петербурге - анализ рынка недвижимости.][3]  
- Определение ключевых параметров для отслеживания системой аномалий и мошеннической деятельности.
- Определение рыночной стоимости объектов недвижимости и типичных параметров квартир.
- Анализ влияния различных параметров квартир на их стоимость.
- Построение диаграмм для проведения анализа.       
***Cтек технологий: Python, Pandas, Matplotlib.***

- Результаты анализа
	- Основная масса объявлений с площадью 30-100 кв.м. 
	- Выявлены уровни зависимости цен на квартиры от площади, расстояния от центр и других параметров.
	- Больше всего объявлений, в Санкт-Петербурге. 
	- Радиус объявлений "центра города" определен как 5 км.   

### [3. Статистический анализ данных. Определение перспективного тарифа для телеком-компании на основе данных клиентов.][4]
- Анализ поведения клиентов по выборке:
    -	описание поведения клиентов – объем потраченных минут разговора, сообщений, интернет-трафика, дополнительных затрат на услуги связи;
    -	определение для этих данных статистических  величин (среднее, дисперсия, стандартное отклонение);
    -	построение гистограмм и описание распределения;
- Определение оптимального тарифного плана.
- Проверка гипотез о равенстве средней выручки для  разных тарифов и регионов.      
***Cтек технологий: Python, Pandas, Matplotlib, Seaborn, NumPy, SciPy, описательная статистика, проверка статистических гипотез.***

- Результаты анализа
	- Больше выручки приносит массовый дешевый тариф за счет дополнительных услуг.
	- Клиенты "дорого" тарифа практически не пользуются дополнительными услугами.
	- Анализ гипотез:
		1. Подтвердилась гипотеза: "Средняя выручка пользователей обоих тарифов 
		2. Не подтвердилась гипотеза: "Средняя выручка пользователей из Москвы отличается от выручки пользователей из других регионов".

### 4. [Сборный проект. Изучение рынка компьютерных игр на основе данных о продажах за 30 лет и оценок пользователей и экспертов (два файла - с разными временными отрезками анализа 10 и 5 лет).][5]  
- Анализ закономерностей определяющих коммерческую успешность игр для планирования ассортимента продаж и проведения рекламных кампаний.
- Определение актуального периода для исследования, закономерности успешности платформ и игр в разных жанрах. 
- Проверка гипотез о равенстве средних пользовательских рейтингов разных платформ и жанров.         
***Cтек технологий: Python, Pandas, Matplotlib, Seaborn, NumPy, SciPy, исследовательский анализ данных, предобработка данных, описательная статистика, проверка статистических гипотез.***

- Результаты анализа
	- Характерный "срок жизни" более менее успешных платформ - 10 лет(+/-2 года)
	- Актуальный период для исследования - 2007-2016 гг. 
	- Влияние отзывов критиков и пользователей на продажи есть.
	- Лучшие продажи - игры в жанре "Action" 
	- Самые популярные платформы (топ-5) - X360 - Wii - PS3 - DS - PS4
	- Самые популярные жанры (топ-5) - Action - Shooter - Sports - Misc - Role-Playing / Racing  
	- Проверка гипотез
		1. Гипотеза "Средние пользовательские рейтинги платформ Xbox One и PC одинаковые" не подтвердилась.	
		2. Гипотеза "Средние пользовательские рейтинги жанров Action и Sports разные" верна.

### [5. Исследование данных авиакомпании  (части по SQL нет в ноутбуке)][6]   
- Выгрузка и подготовка данных авиакомпаний с помощью SQL.
- Проверка гипотез о различии среднего спроса на билеты во время различных событий. 
- Определение интенсивности использования самолетов компании.
- Анализ распределения рейсов по городам России и определение ТОП-10 городов по количеству принимаемых рейсов.        
***Cтек технологий: Python, Pandas, Matplotlib, Seaborn, SQL, SciPy, проверка гипотез.***

- Результаты анализа:
    - Компания работает по двум направлениям - бизнес перелеты и регулярные рейсы.
    - Регулярные рейсы преимущественно малой и средней дальности. 
    - Чаще всего используется Sukhoi SuperJet-100.
    - Регулярные перелеты в 101 город России.
    - В ТОП-10 по количеству рейсов вошли Москва, Санкт_Петербург, Новосибирск и другие крупные города, промышленные центры крупных регионов и Сочи.


### [6. Анализ бизнес-показателей. Оптимизации маркетинговых затрат для компании агрегатора услуг][7]   
- Определение сценария использования продукта (сайта) - длительность сессий, конверсия, частота переходов с разных источников, количество посещений, повторные обращения.
- Определение типичного сценария совершения покупки.
- Расчет среднего чека и количества совершенных покупок за период.
- Расчет выручки с каждого клиента.
- Определение срока окупаемости затрат на клиента, стоимости привлечения клиента из каждого рекламного источника.
Все расчеты проводились в том числе с использования когортного анализа.

***Cтек технологий: Python, Pandas, Matplotlib, Seaborn, когортный анализ, визуализация результатов, Retetion Rate, LTV, CAC, ROI.***

- Результаты анализа:
    - В среднем каждый пользователь пользуется сервисом 1 раз в день/неделю/месяц. За шесть месяцев средний покупатель делает покупки 7 раз.
    - Лояльные пользователи обращаются к сервису чаще - 2-4 раза в месяц. 
    - Конверсия сайта 16%. 
    - Типичная длительность сессии или покупки - 1 мин.
    - Затраты на привлечение пользователя окупаются в среднем за шесть месяцев.
    - Рекомендации: 
    	- перераспределить расходы на источники привлечения (отказаться от бесполезных, оптимизировать затраты на работающие);
		- контролировать уровень расходов, основываясь на целевых показателях ROMI за 6 месяцев.