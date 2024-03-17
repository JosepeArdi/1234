# Homework bot
### Телеграм-бот для проверки статуса домашнего задания на платформе Яндекс.Практикум. Опрашивает API Практикума каждые десять минут на предмет изменения статуса. Логирует и уведомляет в чате об ошибках возникающих в ходе работы. Деплой бота осуществлен на облачной платформе Heroku.

## Как запустить
* клонировать репозиторий, перейти в директорию проекта
1. git clone git@github.com:JosepeArdi/homework_bot.git
2.cd homework_bot
* создать виртуальное окружение и установить [зависимости](requirements.txt)
1. python -m venv venv
2. venv/Scripts/activate (для Windows)
3. venv/bin/activate (для linux)
1. pip install -r requirements.txt
* создать файл с переменными окружения по [примеру](.env.example)
* запустить скрипт
1. python homework.py
## Запуск тестов
1. pytest
