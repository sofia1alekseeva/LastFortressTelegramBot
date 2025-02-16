Discord ↔ Telegram Bridge Bot

Этот бот синхронизирует сообщения между Discord и Telegram, включая текст и медиафайлы. Отслеживает последние 5 сообщений в Discord-канале и автоматически пересылает их в Telegram с поддержкой редактирования и удаления.

## 📦 Основные функции
- **Автоматическая пересылка** новых сообщений
- **Редактирование** текста и медиафайлов
- **Удаление** сообщений в обоих платформах
- Поддержка **изображений/видео/документов**
- Отправка **истории сообщений** при старте

## ⚙️ Технологии
- **Discord.js** v14 - взаимодействие с Discord API
- **Node Telegram Bot API** - работа с Telegram Bot
- **TypeScript** - статическая типизация
- **Dotenv** - управление переменными окружения

## 🚀 Быстрый старт

### Требования
- Node.js v18+
- npm v9+
- Аккаунты на [Discord Dev Portal](https://discord.com/developers) и [Telegram](https://t.me/BotFather)

### Установка
```bash
git clone https://github.com/yourusername/discord-telegram-bot.git
cd discord-telegram-bot
npm install
```

#### Создайте файл .env в корне проекта:
```bash
DISCORD_TOKEN=ваш_токен_бота
DISCORD_CHANNEL_ID=ид_канала
TELEGRAM_TOKEN=ваш_телеграм_токен
TELEGRAM_CHAT_ID=ид_чата
```
#### Скомпилируйте проект:
```bash
npm run build
```

#### Запустите бота:
```bash
npm start
```

## Настройка
### Discord
#### Создайте бота на Discord Developer Portal.

Включите следующие интенты:

- Guilds

- GuildMessages

- MessageContent

Пригласите бота на сервер с правами:

- Read Messages

- View channel

Telegram
Создайте бота через @BotFather.

Получите TELEGRAM_CHAT_ID через @userinfobot.

Использование
Напишите сообщение в указанный Discord-канал.

Бот автоматически перешлет его в Telegram.

При редактировании или удалении сообщения в Discord, изменения отразятся и в Telegram.

### Пример работы
**Discord**:
```
[User]: Привет! Вот фото:
[Прикрепленное изображение]
```
**Telegram**:
```
User (Discord):
Привет! Вот фото:
[Фото]
```