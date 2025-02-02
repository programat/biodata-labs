# Олимпийские игры

Это исторический набор данных о современных Олимпийских играх, включая все игры от Афин 1896 года до Рио-2016. Эти данные собраны из www.sports-reference.com в мае 2018 года.

Отметим, что зимние и летние Игры проводились в одном и том же году вплоть до 1992 года. После этого они расположены так, что зимние игры происходят по четырехлетнему циклу, начиная с 1994 года, затем летние в 1996 году, затем зима в 1998 году и так далее. Распространенная ошибка, которую люди делают при анализе этих данных, заключается в предположении, что летние и зимние игры всегда были в шахматном порядке.

## Содержание

Файл athlete_events.csv содержит 271116 строк и 15 столбцов. Каждый ряд соответствует отдельному спортсмену, участвующему в индивидуальном Олимпийском соревновании (athlete-events). Колонны такие:

| Рус | Ftuk |
| --- | --- |
| ID-уникальный номер для каждого спортсмена | ID - Unique number for each athlete |
| Имя-фамилия спортсмена | Name - Athlete's name |
| Пол - м или ж | Sex - M or F |
| Возраст-Целое Число | Age - Integer |
| Высота - в сантиметрах | Height - In centimeters |
| Вес - в килограммах | Weight - In kilograms |
| Теам-название команды | Team - Team name |
| НОК-Национальный олимпийский комитет З-буквенный код | NOC - National Olympic Committee 3-letter code |
| Игры-год и сезон | Games - Year and season |
| Год-Целое Число | Year - Integer |
| Сезон - лето или зима | Season - Summer or Winter |
| Город-хозяин города | City - Host city |
| Спорт - Спорт | Sport - Sport |
| Событие - Событие | Event - Event |
| Медаль-Золотая, Серебряная, Бронзовая или NA | Medal - Gold, Silver, Bronze, or NA |

## Аннотация

Олимпийские данные по www.sports-reference.com это результат невероятного количества исследований группы энтузиастов олимпийской истории и самопровозглашенных "статисторианцев". Эти данные объединены в удобный формат для анализа данных.

Этот набор данных дает возможность задать вопросы о том, как развивались Олимпийские игры с течением времени, включая вопросы об участии и результативности женщин, различных наций, а также различных видов спорта и событий.