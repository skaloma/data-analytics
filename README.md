# data-analytics
# Портфолио: аналитик данных
## Обо мне 
Привет! Меня зовут Алеся, я начинающий аналитик данных. Я отлично знаю Excel, изучаю SQL, также планирую изучить Python для анализа данных. Мне интересно "копаться" в данных, находить закономерности и необычные детали, и делать из этого выводы.  
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

## Навыки и технологии
- Инструменты анализа данных: `SQL`, `Excel`
- Системы управления базами данных: `PostgreSQL`

## Проекты  
**Проект 1: Калькулятор юнит-экономики онлайн-школы в Excel**  
Что нужно было сделать:  
1. Настроить калькулятор юнит-экономики для того, чтобы понять:
      - сколько новых пользователей нужно привести на платформу, чтобы выполнить план по новым платящим студентам (4000 активных студентов);
      - на какой бюджет стоит ориентироваться для достижения этой цели.
2. Настроить в калькуляторе учет корректировок планов маркетинга (удержать маржинальность на уровне 15%, выйти на выручку выше 35000000 руб. в месяц, увеличить зарплату преподавателей)
3. Пересчитать план найма преподавателей.

Как решала:
1. Провела анализ на исторических данных. Рассчитала такие показатели как средний Retention, LT, LTR, CAC, постоянные и переменные расходы и посчитала маржу. 
2. Собрала все эти данные в калькулятор, который позволяется вносить изменения с указанием процента изменения, и показывается получившиеся плановые показатели. 
3. На основе плановых показателей рассчитала прогнозные данные на год вперед. 
4. Посчитала интенсивность одного преподавателя, и, зная, плановое количество уроков, рассчитала план найма преподавателей (с помочью надстройки "Поиск решения", которая подобрала оптимальные значения количества преподавателей для выполнения плановых показателей).

<a href='https://drive.google.com/drive/folders/1z3NXE_KAtSYyZB0bNcO4yhCMxz-F1EvL?usp=sharing'>Ссылка на проект</a>

**Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра в Excel**   
Что нужно было сделать:
1. Просчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-ти процентную маржинальность.
2. Визуализировать какие пользователи, где и в каком объеме смотрят фильмы на платформе.
3. Поисследовать данные о пользователях и их поведении.

Как решала:
1. Провела анализ на исторических данных. Рассчитала показатели: Средний Retention, LT, LTR, CAC, постоянные расходы, маржа. 
2. Создала калькулятор, позволяющий рассчитатывать плановые показатели на основе фактических данных, принимая значения изменения, вводимые пользователем. 
3. Подобрала, какие изменения фактических данных нужно провести для выхода на 25-ти процентную маржинальность. 
4. Поисследовала данные для ответа на следующие вопросы:
      - В каких часовых поясах больше всего подписчиков?
      - Какую долю из все фильмов составляют самые просматриваемые фильмы на нашей платформе?
      - В какие месяцы и в какое время суток большая активность пользователей?
      - Какова динамика количества пользователей по месяцам?
5. Построила визуализацию для ответа на поставленные вопросы. 
6. На основе анализа данных сделала выводы, которые могут быть полезны для маркетинга. 

<a href='https://docs.google.com/spreadsheets/d/1NngTUXosOI6lMKoFzp6ch3b1qtET_HC9/edit?usp=sharing&ouid=112991897766436802885&rtpof=true&sd=true'>Ссылка на проект</a>

**Проект 3: Когортный анализ онлайн-школы в Excel**   
Что нужно было сделать:
- Проанализировать клиентский LTV по когортам времени захода на нашу платформу и сделать выводы, какие когорты лучше, а какие хуже с точки зрения LTV.

Как решала:
1. Построила сводную таблицу с абсолютными доходимостями клиентов по месячным когортам.
2. Посчитала клиентский Retention для каждой когорты.
3. На основании Retention рассчитала LT с помощью метода усредненных прямоугольников для каждой когорты.
4. Рассчитала LTR для каждой когорты с помощью ARPU. (Значение ARPU было дано равным 300).
5. Рассчитала LTV с помощью усредненных костов для каждой когорты.

<a href='https://docs.google.com/spreadsheets/d/1WZdloAULK5zgp3PA-KKAtzFdMS_8VJTe/edit?usp=drive_web&ouid=112991897766436802885&rtpof=true'>Ссылка на проект</a>
