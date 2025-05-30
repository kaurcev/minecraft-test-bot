# Максимально простой бот для Minecraft

## Описание

Этот скрипт представляет собой бота для игры Minecraft, который использует библиотеку `mineflayer` для взаимодействия с игровым миром. Бот может выполнять различные команды, такие как следование за игроком, сбор предметов, атака мобов и отправка сообщений в Telegram. Бот также может получать определения из Википедии по запросу.

### Пример использования
- Введите айда, чтобы бот начал следовать за вами.
- Введите собери, чтобы бот собрал все предметы вокруг.
- Введите стой, чтобы остановить бота.
- Введите ебаш, чтобы бот начал атаку на ближайшего моба.
- Введите : <запрос>, чтобы получить определение из Википедии.
- Введите тг <сообщение>, чтобы отправить сообщение в Telegram.

## Установка

1. **Клонируйте репозиторий:**
```bash
git clone https://github.com/kaurcev/minecraft-bot-nodejs.git
cd minecraft-bot-nodejs
```
2.  **Установите зависимости**
```bash
npm install
```

### Зависимости
- ```axios```: Для выполнения HTTP-запросов.
- ```dotenv```: Для работы с переменными окружения.
- ```mineflayer```: Основная библиотека для создания бота Minecraft.
- ```mineflayer-pathfinder```: Плагин для навигации бота в игровом мире.
- ```prismarine-viewer```: Для визуализации мира Minecraft (не используется в данном скрипте, но может быть полезен для расширения функционала).

3. **Создайте файл .env в корне проекта и добавьте следующие переменные:**

```
HOST=<адрес_сервера>
PORT=<порт_сервера>
USERNAME=<имя_пользователя>
VERSION=<версия_Minecraft>
TGTOKEN=<токен_Telegram_бота>
TGCHAT=<ID_чата_в_Telegram>
```

4. **Запустите бота:**
```bash
npm start
```

## Функционал
Бот поддерживает следующие команды, которые можно вводить в чате Minecraft:

- ```айда```: Бот будет следовать за указанным игроком.
- ```собери```: Бот соберет все предметы, находящиеся в радиусе действия.
- ```стой```: Бот остановит все текущие действия.
- ```ебаш```: Бот начнет атаку на ближайшего моба.
- ```: <запрос>```: Бот получит определение из Википедии по указанному запросу.
- ```тг <сообщение>```: Бот отправит сообщение в указанный чат Telegram.


#### Обратная связь
Для доработок, исправления багов или расширения функционала всегда можно написать в Telegram: [@kaurcev](https://kaurcev.t.me/)

