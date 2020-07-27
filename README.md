# Проекты выполненные в рамках обучения на ЯндексПрактикум по направлению "Аналитик данных"   
**1. Исследование надёжности заёмщиков (тема Предобработка данных)  --------------------------------- `Notebook_Sprint_2_Credit_score`**  
**2. Исследование объявлений о продаже квартир  (тема Исследовательский анализ данных) ------------ `Notebook_Sprint_3_real_estate`**   
**3. Определение перспективного тарифа для телеком компании  (тема Статистический анализ данных) -- `Notebook_Sprint_4_telecom`**  
**4. Сборный проект (два файла - с разными временными отрезками анализа 10 и 5 лет)  -------------- `Notebook_Sprint_5_games`**   
**5. Исследование данных авиакомпании (сбор и хранение данных, части по SQL нет в ноутбуке)  ------ `Notebook_Sprint_6_fly_company`**

### Notebook_Sprint_2_Credit_score.
** 1. Предобработка данных. Исследование надёжности заёмщиков на основе статистики о платёжеспособности клиентов банка.** 
•	Подготовка данных для построения модели кредитного скоринга банка. 
•	Исследование влияния семейного положение и количества детей на факт возврата кредита в срок.
Потребовалось много внимания уделить предобработке данных, заполнению пропусков и категоризации данных. В одной из частей проекта применялась лемматизация (библиотека PyMystem3) для категоризации целей кредита. 
Применяемый стек технологий: Python, Pandas, PyMystem3.

2. Исследовательский анализ данных. Исследование объявлений о продаже квартир в Санкт-Петербурге - анализ рынка недвижимости.  
•	Определение ключевых параметров для отслеживания системой аномалий и мошеннической деятельности.
•	Определение рыночной стоимости объектов недвижимости и типичных параметров квартир.
В этом проекте, помимо стандартных процедур подготовки данных, требовалось:
•	определить какие данные можно считать «выбросами»;
•	очертить границы исследований по заданным параметрам;
•	проанализировать влияние различных параметров квартир на их стоимость.
В работе необходимо было использовать визуализацию данных для проведения анализа.
Применяемый стек технологий: Python, Pandas, Matplotlib.

3. Статистический анализ данных. Определение перспективного тарифа для телеком-компании на основе данных клиентов.
•	Анализ поведения клиентов.
•	Определение оптимального тарифного плана.
В дополнение к стандартным процедурам подготовки данных, необходимо было сделать предварительный анализ тарифов по небольшой выборке клиентов:
•	описать поведение клиентов – объем потраченных минут разговора, сообщений, интернет-трафика, дополнительных затрат на услуги связи;
•	определить для этих данных статистические  величины (среднее, дисперсию, стандартное отклонение);
•	построить гистограммы и описать распределения;
•	проверить две гипотезы о равенстве средней выручки для  разных тарифов и регионов.
Применяемый стек технологий: Python, Pandas, Matplotlib, Seaborn, NumPy, SciPy, описательная статистика, проверка статистических гипотез.

4. Сборный проект. Изучение рынка компьютерных игр на основе данных о продажах за 30 лет и оценок пользователей и экспертов.
•	 Анализ закономерностей определяющих коммерческую успешность игр для планирования ассортимента продаж и проведения рекламных кампаний.
Задача была определить актуальный период для исследования, закономерности успешности платформ и игр в разных жанрах. Также требовалось проверить гипотезы о равенстве средних пользовательских рейтингов разных платформ и жанров.
Применяемый стек технологий: Python, Pandas, Matplotlib, Seaborn, NumPy, SciPy, исследовательский анализ данных, предобработка данных, описательная статистика, проверка статистических гипотез.

5. Исследование данных авиакомпании
•	Выгрузка и подготовка данных авиакомпаний с помощью SQL.
•	Проверка гипотез о различии среднего спроса на билеты во время различных событий. 
•	Определение интенсивности использования самолетов компании.
•	Анализ распределения рейсов по городам России и определение ТОП-10 городов по количеству принимаемых рейсов.
Применяемый стек технологий: Python, Pandas, Matplotlib, Seaborn,	SQL, SciPy, проверка статистических гипотез.
