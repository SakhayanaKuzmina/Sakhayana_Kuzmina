# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут Сахаяна, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``:

## Проекты
<p> <strong>Проект 1: Калькулятор юнит-экономики онлайн-школы</strong></p>
<p>Что нужно было сделать:<p>

  <li> Настроить в калькуляторе учет корректировок планов маркетинга</li>
  <li> Пересчитать план найма преподавателей</li>
<br>
<p>Как решала:<p>
  <li> Настроить в калькуляторе учет корректировок планов маркетинга: </li>
<br>
<p>1) Добавила в список параметров калькулятора показатель "Поправочный коэффициент на привлечение"</p>
<p>2) Установила значение этого показателя по умолчанию как 100% и добавила возможность изменять этот показатель для расчётного периода 05.21-04.22 по аналогии с другими - через столбец "Изменение"</p>
<p>3) Настроила динамический расчёт количества новых студентов за период 05.21-04.22 с поправкой на этот коэффициент. Если для 05.21-04.22 он равен 120%, то в каждый месяц этого периода рассчётное значение количества новых студентов например, должно быть больше на 20%</p>
<p>4) Просчитала сценарий, при котором планы маркетинга будут увеличены на 12%</p>

  <li> Пересчитать план найма преподавателей:</li>

<p>1) Добавила в калькулятор Найма преподавателей возможность изменять входных параметры: Пропускную способность П и Retention П</p>
<p>2) Сделала поправку в расчёте общей пропускной способности - изменила формулу так, чтобы отразить, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя</p>
<p>3) Обновила прогнозное количество уроков, согласно 1 задаче</p>
<p>4) Просчитала сценарий, при котором Пропускная способность П увеличится на 15 процентов, а Retention П упадёт на 2 процента</p>
<p>5) С помощью Поиска решений составила новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей</p>

> <a href="https://github.com/SakhayanaKuzmina/Sakhayana_Kuzmina/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201.xlsx">Ссылка на проект</a>


<p>Выводы (итоги):<p>
<ol>
  <li> Обновленный лист с калькулятором и новое расчётное количество студентов на 04.2022 г. </li>
  <li> Обновлённый план по найму - с количеством новых преподавателей по месяцам за период с 05.2021 по 04.2022 г. </li>
</ol>
<br> 

<p> <strong>Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</strong></p>
<p>Что нужно было сделать:</p>
<ol>
  <li>Собрать калькулятор юнит-экономики продукта. </li>
  <li>Презентация новой бизнес-модели работы кинотеатра. </li>
<br>
<p>Как решала: <p>
<br> 
  <li> Для понимания картины, рассчитала следующие метрики:</li>
<p>- Количество во подписок в каждый месяц </p>
<p>- Количество просмотров в каждый месяц </p>
<p>- Количество уникальных просматривающих пользователей в каждый месяц </p>
<p>- Дата первого просмотра для каждого юзера </p>
<p>- Количество первых просмотров для пользователя в каждый месяц </p>
<p>- Среднее количество просмотров на одного юзера в каждом месяце </p>
<br> 
  <li> Для создания калькулятора юнит-экономики продукта, рассчитала следующие метрики:</li>
<p>- Количество повторных оплат в каждом месяце</p>
<p>- Retention для каждого месяца</p>
<p>- Среднее геометрическое Retention</p>
<p>- Лайфтайм</p>
<p>- LTR</p>
<p>- CAC</p>
<p>- Маржинальность</p>
</ol> 
<br> 
  <li> Для создания сценария по настройке параметров:</li>
<p>- Подогнала параметры таким образом, чтобы маржинальность была +25%</p>
</ol>
<br> 
  <li> Для презентации построила графики:</li>
<p>- количество пользователей и интенсивность просмотров</p>
<p>- пользовательский Retention</p>
<p>- распределение просмотров по суточным часам (0-23) в разрезе будние-выходные</p>
<p>- распределение просмотров по тайтлам</p>
</ol>  
<br> 
> <a href="https://drive.google.com/drive/folders/13Ee51QWeEFtARSBFqfTYBQ3naTb-Rdzx">Ссылка на проект</a>
 
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1 Калькулятор юнит-экономики продукта, в виде автоматизированной системы для быстрого принятия решений. </li>
  <li>Итог №2 Презентация новой бизнес-модели работы кинотеатра</li>
</ol>
<br> 

<br> 
<p> <strong>Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</strong></p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Смоделировать изменение балансов студентов. </li>
</ol>

<p>Как решала:<p>
  <li>Чтобы проверить, всё ли в порядке с данными и составить список гипотез и вопросов:</li>
<p>- Сколько всего уроков было на балансе **всех учеников** за каждый календарный день</p>
<p>- Как это количество менялось под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков)</p>

> <a href="https://drive.google.com/drive/folders/1JS3mRx8_s8mohnmEV3_DgDbQ6YkLUFuV">Ссылка на проект</a>

  <p>Выводы (итоги):<p>
<ol>
  <li>Запрос, который собирает данные о балансах студентов за каждый прожитый ими день.</li>
</ol>
<br> 

## Контактная информация
- Email:  kuzsakhayana@gmail.com
