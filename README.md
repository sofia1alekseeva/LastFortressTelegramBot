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