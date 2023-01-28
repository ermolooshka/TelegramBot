#TelegramBot

Это первый, написанный мной телеграм-бот.
Бот был написан в рамках учебной программы школы Skillfactory.
Данная работа считается итоговой работой в разделе: Основы Python.

 имя бота в тг:
 @CuRate_from_Ermoloohka_bot

Задание: написать и протестировать Telegram-бота, в котором будет реализован следующий функционал:

Бот возвращает цену на определённое количество валюты (евро, доллар или рубль).
Человек должен отправить сообщение боту в виде: 
<имя валюты цену которой он хочет узнать>  <имя валюты в которой надо узнать цену первой валюты>  <количество первой валюты>.
При вводе команды /start или /help пользователю выводятся инструкции по применению бота.
При вводе команды /values должна выводиться информация о всех доступных валютах в читаемом виде.
При ошибке пользователя вызывать собственно написанное исключение APIException с текстом пояснения ошибки.
Текст любой ошибки с указанием типа ошибки должен отправляться пользователю в сообщения.


Данный бот не запущен, необходимо запустить бот со своего устройства (загрузить данный репозиторий на свой компьютер).
Для работы с данным телеграм-ботом необходимо установить библиотеки requests и PyTelegramBotAPI (версия 4.X).
