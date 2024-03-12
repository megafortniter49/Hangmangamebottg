# Telegram Hangman Bot

Этот бот для Telegram предлагает классическую игру "Виселица", где игроки должны угадывать слова по одной букве за раз.

## ПРЕДУПРЕЖДЕНИЕ

Этот код не будет работать так как вам нужно создать файлы `log.txt` и `reviews.txt`, а так же записать API токен вашего бота в переменную `TOKEN` в файле `config.py`.

## Функции

- **Начало новой игры**: Игроки могут начать новую игру, и бот автоматически выберет слово для угадывания.
- **Угадывание букв**: Игроки отправляют букву, чтобы проверить, есть ли она в слове.
- **Сдача**: В любой момент игры игрок может сдаться, чтобы узнать правильное слово.
- **Загадать слово другу**: Игроки могут загадать своё слово для друга, создавая уникальный код игры.
- **Оставить отзыв**: Игроки могут оценить бота и оставить текстовый отзыв.
- **Помощь и информация**: Бот предоставляет информацию о том, как играть, и контактную информацию автора.

## Как начать играть

1. Добавьте бота в Telegram через [ссылку на бота](https://t.me/Hangmangame1488bot).
2. Напишите боту `/start` для начала игры или `/help` для получения инструкций.

## Команды

- `/start` - начать новую игру или перезапустить текущую игру.
- `/setword <слово>` - загадать слово для друга. Используйте в формате `/setword слово`.
- `/review` - оставить оценку и отзыв о боте.
- `/about` - узнать информацию о проекте и его создателе.
- `/social` - получить контактную информацию автора.
- `/support` - поддержать проект пожертвованием.

## Технологии

- Python 3
- aiogram для создания бота

## Автор

[Геворкян Баграт]((https://github.com/megafortniter49))

Спасибо, что интересуетесь моим проектом! Если у вас есть вопросы или предложения, не стесняйтесь связаться со мной через команду `/social` в боте.

---

Проект создан [Геворкяном Багратом](https://github.com/megafortniter49) © 2024
