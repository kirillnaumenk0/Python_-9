# Телеграм-бот для игры в крестики-нолики

Незнаю что не так но сперва была ошибка : from telegram.ext import Updater, CommandHandler, CallbackQueryHandler, MessageHandler, Filters
ImportError: cannot import name 'Filters' from 'telegram.ext

Изменил Filters на filters вроде исправилось. 
---
Потом вышла другая с которой  я не справился:
updater = Updater(getToken())  # получения токена из файла 'token.txt' и инициализация updater
              ^^^^^^^^^^^^^^^^^^^
TypeError: Updater.__init__() missing 1 required positional argument: 'update_queue'
