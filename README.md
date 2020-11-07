# tel_bot_horoscope

English:

About the project:
A project for creating a light bot that puts out the user's horoscope for 2 days (current and tomorrow) at the user's request.
Data is parsed and written to the database every day at a certain time (at 12.01 Moscow time).

About files:
To get acquainted with the code and how it works, please go to the file data.py.
It stores both code and comments describing the actions of a particular code fragment or function.
The job of the current file is to extract, prepare, and then provide information to the database that the telegram bot will use.

To get acquainted with the code and how it works, please go to the file tel_bot.py.
File tel_bot.py stores the bot itself.
It stores both code and comments describing the actions of a particular code fragment or function.
It creates and installs buttons, button calls, database calls, and displays the horoscope that the user needs.


Русский язык:

О проекте:
Проект для создания легкого бота, который выкладывает по запросу пользователя его гороскоп за 2 дня (текущего и завтравшнего).
Данные парсятся и записываются в базу данных каждые сутки по определенному времени (в 12.01 по МСК).

О файлах:
Для ознакомления с кодом и его работе, прошу перейти в файл data.py.
В нем хранится как и код, так и комментарии описывающие действия того или иного фрагмента кода или функции.
Работа текущего файла состоит в том, чтобы добыть, подготовить а затем обеспечить информацией базу данных, которую будет использовать телеграмм бот.

Для ознакомления с кодом и его работе, прошу перейти в файл tel_bot.py.
Файл tel_bot.py хранит в себе самого бота.
В нем хранится как и код, так и комментарии описывающие действия того или иного фрагмента кода или функции.
В нем создаются и устанавливаются кнопки, вызовы кнопок, вызов базы данных и вывод нужного для пользователя гороскопа.
