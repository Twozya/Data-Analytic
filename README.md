# Портфолио: аналитик данных
## Обо мне
Привет! Меня зовут Станислав, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
## Контактная информация
* **Email:** twozya@gmail.com
* **LinkedIn:** https://www.linkedin.com/in/stanislav-analyst/
## Навыки и технологии
* Инструменты анализа данных: SQL, Excel, Google Sheets
* Языки программирования и библиотеки: Python, C/C++, Delphi
* Системы управления базами данных: PostgreSQL, MySQL
* Средства визуализации данных: PowerBI
## Проекты:
* [Проект 1: Калькулятор юнит-экономики онлайн-школы](https://github.com/Twozya/Data-Analytic#%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82-1-%D0%BA%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80-%D1%8E%D0%BD%D0%B8%D1%82-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B8-%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D1%88%D0%BA%D0%BE%D0%BB%D1%8B)

* [Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра](https://github.com/Twozya/Data-Analytic#%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82-2-%D0%BA%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80-%D1%8E%D0%BD%D0%B8%D1%82-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B8-%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D0%BA%D0%B8%D0%BD%D0%BE%D1%82%D0%B5%D0%B0%D1%82%D1%80%D0%B0)

* [Проект 3: Распределение и планирование нагрузки учителей онлайн-школы](https://github.com/Twozya/Data-Analytic#%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82-3-%D1%80%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B8-%D0%BF%D0%BB%D0%B0%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BD%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B8-%D1%83%D1%87%D0%B8%D1%82%D0%B5%D0%BB%D0%B5%D0%B9-%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D1%88%D0%BA%D0%BE%D0%BB%D1%8B)

* [Проект 4: A/B-тестирование по принятию решения изменения дизайна](https://github.com/Twozya/Data-Analytic/edit/main/README.md#%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82-4-ab-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE-%D0%BF%D1%80%D0%B8%D0%BD%D1%8F%D1%82%D0%B8%D1%8E-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B4%D0%B8%D0%B7%D0%B0%D0%B9%D0%BD%D0%B0) 

### <b>Проект 1: Калькулятор юнит-экономики онлайн-школы</b>

Что нужно было сделать:
* <b>Задача №1. Настроить в калькуляторе учёт корректировок планов маркетинга.</b>

Для решения было сделано следующее:
1) Добавил в список параметров калькулятора показатель "Поправочный коэффициент на привлечение".
2) Установил значение этого показателя по умолчанию как 100% и добавил возможность изменять этот показатель для расчётного периода 05.21-04.22 по аналогии с другими - через столбец "Изменение".
3) Настроил динамический расчёт количества новых студентов за период 05.21-04.22 с поправкой на этот коэффициент. Если для 05.21-04.22 он равен 120%, то в каждый месяц этого периода рассчётное значение количества новых студентов должно быть больше на 20%.
4) Просчитал сценарий, при котором планы маркетинга будут увеличены на 12% (настройки остальных показателей не изменял).

* <b>Задача №2. Пересчитать план найма преподавателей.</b>

Для решения было сделано следующее:
1) Добавил в калькулятор "Найма преподавателей" возможность изменять входные параметры: Пропускную способность преподавателей и Retention преподавателей - с помощью дополнительного столбца с процентными изменениями.
2) Сделал поправку в расчёте общей пропускной способности - изменил формулу так, чтобы отразить, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя, задаваемой параметром.
3) Обновил прогнозное количество уроков, добавив новые значения из Задачи 1 (полученные после поправки на планы маркетинга).
4) Просчитал сценарий, при котором Пропускная способность преподавателей увеличится на 15%, а Retention преподавателей упадёт на 2%.
5) С помощью "Поиска решений" составил новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей.

> [Калькулятор юнит-экономики онлайн-школы](https://github.com/Twozya/Data-Analytic/blob/main/%D0%9A%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80%20%D1%8E%D0%BD%D0%B8%D1%82-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B8%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D1%88%D0%BA%D0%BE%D0%BB%D1%8B.xlsx)

<b>Итог по задачи 1</b> - Обновлённый лист с калькулятором, новое расчётное количество студентов на 04.2022.

<b>Итог по задачи 2</b> - Обновлённый план по найму - с количеством новых преподавателей по месяцам за период с 05.2021 по 04.2022.


### <b>Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</b>

Что нужно было сделать:
* <b>Задача №1. Решить задачи, связанные с исследованием аудитории и расчётов метрик, которые помогут оценить динамику изменения просмотров на нашей платформе. Выполнить задания на развитие навыков командной работы.</b>

Для решения был произведён расчёт следующих метрик:
1. Количество подписок в каждый месяц.
2. Количество просмотров в каждый месяц.
3. Количество уникальных просматривающих пользователей в каждый месяц.
4. Дата первого просмотра для каждого юзера.
5. Кол-во первых просмотров для пользователя в каждый месяц.
6. Среднее кол-во просмотров на одного юзера в каждом месяце.

Так же на основе анализа предоставленных данных была выявлена динамика пользовательской активности на платформе, опираясь на все рассчитанные метрики.

* <b>Задача №2. Ответить руководству на вопрос: насколько используемая бизнес-модель эффективна с точки зрения финансовой составляющей?</b>

Для решения был произведён расчёт следующих метрик:
1. Количество повторных оплат в каждом месяце.
2. Retention для каждого месяца.
3. Среднее геометрическое Retention.
4. Лайфтайм.
5. LTR.
6. CAC.
7. Маржинальность.

* <b>Задача №3. Презентовать новую бизнес-модель работы кинотеатра, где будет показано, кто, где и в каком объеме смотрит фильмы на нашей платформе.
Пересчитать параметры экономики, чтобы выйти на 25-процентную маржинальность.</b>

Для решения был произведён расчёт следующих метрик:
1. Сделан перереасчёт параметров так, чтобы маржинальность была +25%.
2. Были визулизированы графики на сонове полученных данных из всех предыдущих задач.

> [Калькулятор юнит-экономики онлайн-кинотеатра](https://github.com/Twozya/Data-Analytic/blob/main/%D0%9A%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80%20%D1%8E%D0%BD%D0%B8%D1%82-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B8%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D0%BA%D0%B8%D0%BD%D0%BE%D1%82%D0%B5%D0%B0%D1%82%D1%80%D0%B0.zip)


### <b>Проект 3: Распределение и планирование нагрузки учителей онлайн-школы</b>

Что нужно было сделать:
* <b>Задача №1. Найти преподавателя, который провёл максимальное количество уроков в 2021 году. Интересуют только уроки, которые были списаны с баланса, то есть успешно пройдены или прогуляны студентом. Триальные уроки не нужны.</b>

Для решения было сделано следующее:
1. Из таблицы с уроками выбрал id учителя и количество проведённых уроков.
2. В условии прописал, что нужны успешные уроки или уроки, которые были пропущены учеником. Так же указал, что нужен именно 2021 год и нетриальные уроки.
3. Обернул этот запрос в CTE конструкцию.
4. В новый запрос из полученного предыдущего выбрал id учителя.
5. Прописал условие, чтобы выбрать только того учителя, у которого было больше всех проведённых уроков.
6. Ниже написал уже запрос, который уже соединит таблицу с информацией по учителям с данными, которые были получены выше.
7. Полученный результат выгрузил в Excel.

* <b>Задача №2. Нужно узнать распределение учителей по количеству проводимых в месяц уроков (опять же - не триальных, а только успешных или прогулянных самим студентом). Выведите распределение учителей по количеству проведённых в месяц уроков в штуках.</b>

Для решения было сделано следующее:
1. Из таблицы с уроками выбрал id учителя, количество проведённых уроков и выделил месяцы 2021 года.
2. В условии прописал, что нужны успешные уроки или уроки, которые были пропущены учеником. Так же указал, что нужен именно 2021 год и нетриальные уроки.
3. Сделал группировку по id учителя и по месяцам.
4. Сделал сортировку по id учителя и количеству проведённых уроков.
5. Обернул всё это в подзапрос.
6. Из полученых данных выбрал количество проведённых уроков и количество учителей.
7. Сгрупировал и сделал сортировку по количеству проведённых уроков.
8. Полученный результат выгрузил в Excel.

> [Распределение и планирование нагрузки учителей онлайн-школы](https://github.com/Twozya/Data-Analytic/blob/main/%D0%A0%D0%B0%D1%81%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%20%D0%BF%D0%BB%D0%B0%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B8%20%D1%83%D1%87%D0%B8%D1%82%D0%B5%D0%BB%D0%B5%D0%B9%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D1%88%D0%BA%D0%BE%D0%BB%D1%8B.zip)


### <b>Проект 4: A/B-тестирование по принятию решения изменения дизайна</b>

Что нужно было сделать:
* <b>Задача №1. Выбрать окно конверсии.</b>

Для решения было сделано следующее:
1. Выгрузил данные из csv-файла.
2. Безымянную колонку с нумерацией определил как индекс.
3. Проверил типы данных в каждой колонке и перевёл столбцы с датами в формат даты.
4. Вычислил 95, 90 и 85 перцентили и узнал, что 95 перцентиль соответствует недельному окну конверсии.
5. Построил гистограмму распределения времени между первым заходом на сайт и покупкой.

* <b>Задача №2. Исследовать распределение пользователей по группам по основным сегментам.</b>

Для решения было сделано следующее:
1. Выгрузил данные из csv-файла.
2. Безымянную колонку с нумерацией определил как индекс.
3. Написал функцию, чтобы проверить распределение пользователей по сегментам внутри каждой группы.
4. Построил барчарт распределения пользователей.

* <b>Задача №3. Оценить статистическую значимость в изменении конверсии с помощью критерия хи-квадрат.</b>

Для решения было сделано следующее:
1. Определил три группы, по которым создал новые три таблицы для дальнейшего тестирования.
2. Вычислил статистический критерий для каждой группы с помощью теста хи-квадрат.
3. Получнные результаты сравнил с уровенем значимости в 5%.

* <b>Задача №4. Оценить влияние теста на средний чек с помощью бутстрапа.</b>

Для решения было сделано следующее:
1. В таблицах очистил строки, в которых отсутствуют покупки. 
2. Рассчитал бутстрап среднего чека для тестовой и контрольной выборок по трём группам.
3. Построил гистограмму распределения значений среднего чека.

* <b>Задача №5. Сделать вывод по результатам проведённого теста.</b>

Для решения было сделано следующее:
1. Был сделан вывод на основе преведённого тестирования.

> [A/B-тестирование по принятию решения изменения дизайна](https://github.com/Twozya/Data-Analytic/blob/main/AB-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%20%D0%BF%D1%80%D0%B8%D0%BD%D1%8F%D1%82%D0%B8%D1%8E%20%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F%20%D0%B4%D0%B8%D0%B7%D0%B0%D0%B9%D0%BD%D0%B0.zip)
