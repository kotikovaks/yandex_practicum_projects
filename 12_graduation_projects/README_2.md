# Оценка результатов A/B-теста


**Цель исследования** — Проверить корректность проведения A/B-теста и дать оценку его результатам.

**Ход исследования**

1. Обзор и предобработка данных
2. Оценка корректности проведения теста в следующих аспектах:
  - соответствие данных требованиям технического задания;
  - время проведения теста;
  - аудитория теста. 
3. Исследовательский анализ данных. 
- Мы изучим:
  - распределение количества событий на пользователя;
  - то, как число событий в выборках распределено по дням;
  - то, как меняется конверсия в воронке в выборках на разных этапах;
  - то, какие особенности данных нужно учесть, прежде чем приступать к A/B-тестированию.
- Оценим результаты A/B-тестирования и проверим статистической разницы долей z-критерием.
4. Общий вывод

**Результат:** На основании проведенного анализа и сделанных выводов можно утверждать, что:
- Есть статистически значимое различие по конверсии между группами.
- График различия конверсии между группами сообщает, что результаты группы А лучше группы В.
- Количество событий на пользователя в группе А существенно выше группы В.
- В группе В очень низкий уровень конверсии на всех этапах воронки.

Однако стоит отметить следующие моменты:
- Некорректное деление пользователей между группами, что привело к количественному различию между ними и, вероятно, к отсутствию активности 68% участников группы В. Для качественного деления трафика следовало провести A/A-тест, который помог бы измерить качество деления, определить доли групп, и подтвердить однородность трафика.
- Смешение участников двух тестов. Участие пользователей в нескольких тестах одновременно могло повлиять на чистоту результата для всех тестов.

Учитывая вышеизложенное, можно признать тест неуспешным.
