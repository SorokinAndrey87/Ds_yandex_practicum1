# Исследование объявлений о продаже квартир

**Задачи проекта** 

Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир

**Описание проекта**

На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости отудаленности от центра. Проведена предобработка данных. Добавлены новые данные.Построены гистограммы, боксплоты, диаграммы рассеивания.

**Навыки и инструменты**

`Matplotlib`, `Pandas`, `Python`, `визуализация данных`, `исследовательский анализ данных`, `предобработка данных`

**Вывод**
* Мы обработали архив данных, посчитав цену квадратного метра, вывев дни недели, месяца и года из дат размещения объявлений и добавив категории этажей квартир.
* Мы выявили, что большинство объявлений снимаются с размещения до 60 дней и не могут считаться датами продажи. Средние значения продажи квартир составляют от 1 до 500 дней.
* На стоимость квадратного метра больше всего влияют количество комнат, этаж и близость к центру, незначительно - дата, месяц, год и общая площадь размещения. В 2016-2017 стоимость квартир была ниже на 10-20%, после чего начала постоянно расти, начиная с 2018.

**Статус**

Завершен
