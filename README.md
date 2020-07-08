# Пример бота для ВК
Данный бот сделан для демонстрации возможностей. Это лишь малая часть того, что можно ли сделать.
## Установка зависимостей
Для начала нам нужно установить сам Python. Делается на linux это так:
```
apt install python
```
Или
```
sudo apt install python
```
Теперь устанавливаем библиотеку vk api командой:
```
pip install vk_api
```
## Настройка бота
Мы установили Python и библиотеку, теперь скачиваем бота и настраиваем
Заходим в файл `settings.py` и вставляем в поле `token` свой токен от группы ВК. Он должен иметь разрешение на отправку сообщений.
Также нам нужно включить LongPoll API в настройках группы.
После этого заходим в файл `bot.py` и меняем сообщения. `msg` — это отправка сообщения. `msgkbrd` — отправка сообщения с клавиатурой.
## Включение бота
Всё, что осталось сделать — включить бота. Для этого в консоли заходим в папку с ботом, например:
```
cd vkbot
```
И запустить бота командой:
```
python bot.py
```
Теперь наш бот запущен, и всё хорошо!
