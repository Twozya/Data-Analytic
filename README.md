# Портфолио: аналитик данных
## Обо мне
Привет! Меня зовут Станислав, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
## Навыки и технологии
* Инструменты анализа данных: SQL, Excel:
* Языки программирования и библиотеки: Python, C/C++, Delphi
* Системы управления базами данных: MySQL, PostgreSQL
* Средства визуализации данных: PowerBi
## Проекты
<b>Проект 1: Калькулятор юнит-экономики онлайн-школы</b>

Что нужно было сделать:
* <b>Задача №1. Настроить в калькуляторе учёт корректировок планов маркетинга.</b>
1) Добавил в список параметров калькулятора показатель "Поправочный коэффициент на привлечение".
2) Установил значение этого показателя по умолчанию как 100% и добавил возможность изменять этот показатель для расчётного периода 05.21-04.22 по аналогии с другими - через столбец "Изменение".
3) Настроил динамический расчёт количества новых студентов за период 05.21-04.22 с поправкой на этот коэффициент. Если для 05.21-04.22 он равен 120%, то в каждый месяц этого периода рассчётное значение количества новых студентов должно быть больше на 20%.
4) Просчитал сценарий, при котором планы маркетинга будут увеличены на 12% (настройки остальных показателей не изменял).

* <b>Задача №2. Пересчитать план найма преподавателей.</b>
1) Добавил в калькулятор "Найма преподавателей" возможность изменять входные параметры: Пропускную способность преподавателей и Retention преподавателей - с помощью дополнительного столбца с процентными изменениями.
2) Сделал поправку в расчёте общей пропускной способности - изменил формулу так, чтобы отразить, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя, задаваемой параметром.
3) Обновил прогнозное количество уроков, добавив новые значения из Задачи 1 (полученные после поправки на планы маркетинга).
4) Просчитал сценарий, при котором Пропускная способность преподавателей увеличится на 15%, а Retention преподавателей упадёт на 2%.
5) С помощью "Поиска решений" составил новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей.

> [Калькулятор юнит-экономики онлайн-школы](https://github.com/Twozya/Test/blob/main/%D0%9A%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80%20%D1%8E%D0%BD%D0%B8%D1%82-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D0%BA%D0%B8%20%D0%BE%D0%BD%D0%BB%D0%B0%D0%B9%D0%BD-%D1%88%D0%BA%D0%BE%D0%BB%D1%8B.xlsx)

<b>Итог по задачи 1</b> - Обновлённый лист с калькулятором, новое расчётное количество студентов на 04.2022.

<b>Итог по задачи 2</b> - Обновлённый план по найму - с количеством новых преподавателей по месяцам за период с 05.2021 по 04.2022.
