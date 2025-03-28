# Telegram Bot: Трекер активности и курсы валют
# Описание проекта
Этот проект представляет собой Telegram-бота, разработанного на Python с использованием библиотеки pyTelegramBotAPI. 
Бот предназначен для идентификации активности пользователей в чатах, составления рейтинга активности и предоставления информации о курсах валют (рубли к доллару и евро) на заданные даты. Проект компьютерных навыков работы с API, обработки данных, файлов ввода-вывода и создания интерактивных ботов.

# Основные функции:
Рейтинг активности : Бот подсчитывает количество сообщений от каждого пользователя в чате и формирует топ-10 самых активных участников.
  
Личный уровень : Показывает необходимое количество его сообщений и место в общем рейтинге.

Курс валют : определить курс рубля к доллару и евро на любом сайте с использованием библиотеки pycbrf .

Административные функции : Администратор может вводить новые чаты для идентификации активности с помощью команды /add .

Логирование : Уведомляет администратора о несанкционированном доступе к боту.
# используемые технологии
Python : Основной язык программирования.

pyTelegramBotAPI : Для взаимодействия с Telegram API.

pycbrf : Для получения курсов валют от Центрального банка РФ.

JSON : для хранения данных об активности пользователей.

Файловый ввод-вывод : Для сохранения списка чатов и данных пользователей.
# Структура проекта

bot.py — основной файл с логикой бота.

config.py — файл конфигурации для хранения токена бота и идентификатора администратора (не включен в репозиторий).

chats.txt — файл для хранения идентификаторов списка чатов, которые обслуживает бот (не включен в репозиторий).

data.json — файл для хранения данных об активности пользователей (не включен в репозиторий).

стикер.webp , рубль.jpg — медиафайлы, используются снизу (не включены в репозиторий).
