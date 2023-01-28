# Эксперименты с github actions

## send_message.yaml [ [link](.github/workflows/send_message.yaml) ]

![send_message](https://github.com/thrashches/actions_test/actions/workflows/send_message.yaml/badge.svg)

Это пример для отправки сообщения через Telegram.
Для работы примера в Secrets репозитория должны быть следующие переменные:

- ```TELEGRAM_TO``` - id чата в телеграме, в который добавлен бот
- ```TELEGRAM_TOKEM``` - токен для доступа к телеграм боту
- Любые другие переменные, которые вы хотите передавать в сообщении

Само сообщение пока лучше писать в ```html```. В плане поддержки ```markdown``` есть [баги связанные с экранированием символов](https://github.com/appleboy/telegram-action/issues/30).
