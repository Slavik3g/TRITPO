|Сценарий|Действие|Ожидаемый результат|Полученый результат|Прохождение теста|
|:---|:---|:---|:---|:---|
|Добавить новое напоминание|Отправка сообщения пользователем подходящем по шаблону|Добавление сообщения в бд|Сообщение добавлено в бд|+ |
|Оповещение о напомининии|Отправка пользователем сообщения и возврат его от бота|Бот напомнит вам о вашем напоминании|Бот напомнил пользоваелю| +|
|Команда помощи|Отправка '/help' боту|Отправка пользователю необходимого шаблона для отправки|Бот отправил шаблон для отправки|  +|
|Команда показа всех удовлетомления|Отправить боту сообщение '/show'|Возврат от бота списка ожидающих уведомлений|Список ожидающих уведомлений| +  |
|Разбор ошибок в написании времени|Отправить сообщение боту имеющее вид: 'напочни через 1 час поесть'|Создание нового уведомления: [time: current time + 1 hour, content: 'поесть'|Для некоторых входных данных бот выводит строку использования| -|
|Разбор ошибок в написании команды|Отправить сообщение боту имеющее вид: 'напочни завтрв в 8 проверить почту'|Создание нового уведомления: [time: next_day.08.00, content: 'поесть'|Для некоторых входных данных бот выводит строку использования| -|

