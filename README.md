# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут Сахаяна, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``:

## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:<p>
</ol>
  <li> Настроить в калькуляторе учет корректировок планов маркетинга.</li>
  <li> Пересчитать план найма преподавателей.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>
<p>1. Настроить в калькуляторе учет корректировок планов маркетинга:<p>
</ol>
<p>1) Добавила в список параметров калькулятора показатель "Поправочный коэффициент на привлечение".<p>
<p>2) Установила значение этого показателя по умолчанию как 100% и добавила возможность изменять этот показатель для расчётного периода 05.21-04.22 по аналогии с другими - через столбец "Изменение".<p>
<p>3) Настроила динамический расчёт количества новых студентов за период 05.21-04.22 с поправкой на этот коэффициент. Если для 05.21-04.22 он равен 120%, то в каждый месяц этого периода рассчётное значение количества новых студентов например, должно быть больше на 20%.<p>
<p>4) Просчитала сценарий, при котором планы маркетинга будут увеличены на 12%.<p>
</ol>
<p>2. Пересчитать план найма преподавателей:<p>
</ol>
<li>1) Добавила в калькулятор Найма преподавателей возможность изменять входных параметры: Пропускную способность П и Retention П.<li>
<li>2) Сделала поправку в расчёте общей пропускной способности - изменила формулу так, чтобы отразить, что новые преподаватели в первый месяц своей работы могут проводить только половину уроков от средней пропускной способности преподавателя.<li>
<li>3) Обновила прогнозное количество уроков, согласно 1 задаче.<li>
<li>4) Просчитала сценарий, при котором Пропускная способность П увеличится на 15 процентов, а Retention П упадёт на 2 процента.<li>
<li>5) С помощью Поиска решений составила новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей<li>
</ol> 
> <a href="https://github.com/SakhayanaKuzmina/Sakhayana_Kuzmina/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%201.xlsx">Ссылка на проект</a>
  (ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)

<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1 Обновленный лист с калькулятором и новое расчётное количество студентов на 04.2022 г. </li>
  <li>Итог №2 Обновлённый план по найму - с количеством новых преподавателей по месяцам за период с 05.2021 по 04.2022 г. </li>
</ol>
<br> 

<p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Собрать калькулятор юнит-экономики продукта, поскольку сейчас очень не хватает такой автоматизированной системы для быстрого принятия решений. </li>
  <li>Задача №2.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>

<li>1. Для понимания картины, рассчитала следующие метрики:<li>
<li>- Количество во подписок в каждый месяц.<li>       
<li>- Количество просмотров в каждый месяц.<li>  
<li>- Количество уникальных просматривающих пользователей в каждый месяц.<li>
<li>- Дата первого просмотра для каждого юзера.<li>
<li>- Количество первых просмотров для пользователя в каждый месяц.<li>
<li>- Среднее количество просмотров на одного юзера в каждом месяце.<li>

<li>2. Для создания калькулятора юнит-экономики продукта, рассчитала следующие метрики:<li>
<li>- Количество повторных оплат в каждом месяце<li>
<li>- Retention для каждого месяца<li>
<li>- Среднее геометрическое Retention<li>    
<li>- Лайфтайм<li>      
<li>- LTR<li> 
<li>- CAC<li>    
<li>- Маржинальность<li>
  
<li>3. Для создания сценария по настройке параметров:<li> 
<li>- Подогнала параметры таким образом, чтобы маржинальность была +25%<li>

<li>4. Для презентации построила графики:<li>
<li>- количество пользователей и интенсивность просмотров<li>
<li>- пользовательский Retention<li>      
<li>- распределение просмотров по суточным часам (0-23) в разрезе будние-выходные<li>      
<li>- распределение просмотров по тайтлам<li>
  
> <a href="https://drive.google.com/drive/folders/13Ee51QWeEFtARSBFqfTYBQ3naTb-Rdzx">Ссылка на проект</a>
 (ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
 
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 

<br> 
<p> Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  <li>Задача №2.</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>
  
> <a href="https://drive.google.com/drive/folders/1JS3mRx8_s8mohnmEV3_DgDbQ6YkLUFuV">Ссылка на проект</a>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)

  <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 

## Контактная информация
- Email:  kuzsakhayana@gmail.com
