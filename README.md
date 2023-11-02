# Портфолио: Аналитик данных

## Обо мне:

Привет, меня зовут Радион, я начинающий аналитик данных. На данный момент прохожу обучение от Skypro по специальности "Аналитик даных", одновременно с этим, прохожу дополнительное обучение на других полезных сайтах.
В этом репозитории вы сможете найти некоторые из моих проектов, выполненных во время обучения и практики.

## Навыки и умения:
- Инструменты анализа данных: ``SQL``, ``Excel``
- Языки программирования и библиотеки: ``Python``
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``
- Средства визуализации данных: ``PowerBi``

## Проекты:
``Проект №1``: Калькулятор юнит-экономики онлайн-кинотеатра
<p>Что необходимо было сделать:<p/>
<li>1. Нашему отделу аналитики необходимо посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность (это всё пойдет на слайды презентации для стратсессии в конце квартала) и собрать хорошую наглядную визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на нашей платформе."</li>
<li>2. "Просьба собрать калькулятор юнит-экономики нашего продукта, поскольку сейчас очень не хватает такой автоматизированной системы для быстрого принятия решений."</li>

<p>Как решал:<p/>
<ol>
<p>1. Для начала определить, что является юнитом.<p/>
<p>2. Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.<p/>
<p>3. Выбрать оптимальный вариант расчета Retention.<p/>
<p>4. Собрать визуализации основных бизнес-показателей.<p/>
<p>5. Исследовать данные о пользователях и их поведении.<p/>
</ol>
> <a href="https://1drv.ms/x/s!Ap31R8MMlhJli19O8ttvPcmagBHQ?e=MfZ9Co">Ссылка на проект</a>

<p>Выводы:<p/>
<ol>
<p>Итог№1. Калькулятор юнит-экономики построен, сценарий выхода на 25%-ную маржинальность предложен.<p/>
<p>Итог№2. Исследование данных о пользователях и их поведении можно видеть на листе визуализация. <p/>
</ol>
<br>

``Проект №2``: Моделирование изменение баланса студентов с помощью SQL
<p>Что необходимо было сделать:<p/>
<li>Запрос, который собирает данные о балансах студентов за каждый "прожитый" ими день.</li>

<p>Как решал:<p/>
<ol>
<p>1. Узнаем, когда была первая транзакция для каждого студента. Начиная с этой даты, мы будем собирать его баланс уроков. <p/>
<p>2. Соберем таблицу с датами за каждый календарный день 2016 года.<p/>
<p>3. Узнаем, за какие даты имеет смысл собирать баланс для каждого студента.<p/>
<p>4. Найдем все изменения балансов, связанные с успешными транзакциями.<p/>
<p>5. Найдем баланс студентов, который сформирован только транзакциями.<p/>
<p>6. Найдем изменения балансов из-за прохождения уроков. <p/>
<p>7. По аналогии с уже проделанным шагом для оплат создадим CTE для хранения кумулятивной суммы количества пройденных уроков. <p/>
<p>8. Создадим CTE ``balances`` с вычисленными балансами каждого студента. <p/>
<p>9. Посмотрим, как менялось общее количество уроков на балансах студентов.<p/>
</ol>
> <a href="https://metabase.sky.pro/question/91403">Ссылка на проект</a>
<p>Выводы:<p/>
<ol>
<p>Итог№1. У определенных студентов количество купленных уроков меньше количества пройденных(количество уроков по таблице ``classes`` больше, чем количество оплаченных уроков по таблице ``payments``).<p/>
<p>Итог№2.  Мы наблюдаем отсутствие зеркальности количества оплачиваемых уроков, и тех, которые проводятся со студентами. Это влечет за собой значительное увеличение в динамике количества уроков на балансе у студентов. Необходимо определить, с чем связана такая разница в количестве покупаемых и проводимых уроков, а также установить возможность негативных последствий.<p/>
<ol/>

## Контактная информация:
- Gmail: radionsanakoev@gmail.com
- @Mail: radionsanakoev@mail.ru
