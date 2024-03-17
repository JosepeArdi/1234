# Homework bot
### Телеграм-бот для проверки статуса домашнего задания на платформе Яндекс.Практикум. Опрашивает API Практикума каждые десять минут на предмет изменения статуса. Логирует и уведомляет в чате об ошибках возникающих в ходе работы. Деплой бота осуществлен на облачной платформе Heroku.

## Как запустить
* клонировать репозиторий, перейти в директорию проекта
git clone git@github.com:JosepeArdi/homework_bot.git
cd homework_bot
* создать виртуальное окружение и установить [зависимости](requirements.txt)
python -m venv venv
. venv/Scripts/activate (для Windows)
. venv/bin/activate (для linux)
pip install -r requirements.txt
* создать файл с переменными окружения по [примеру](.env.example)
* запустить скрипт
python homework.py
## Запуск тестов
pytest