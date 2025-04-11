# Stable Diffusion Telegram Bot

## 🌟 English

A Python-based Telegram bot that generates images using the DreamStudio API (Stable Diffusion) with aiogram 3.x and SQLite. 
This bot offers a user-friendly menu for creating images based on customizable prompts and an admin panel for managing settings like welcome messages and prompts.

### 🚀 Features
- **Image Generation**: Create stunning images with prompts like "Female Jedi" or "Female Stormtrooper" via Stable Diffusion.
- **Main Menu**: Buttons for "Home," "Info," "Contact," "Female Jedi," "Female Stormtrooper," and an admin-only "Admin Panel."
- **Admin Panel**: Restricted access to edit welcome text, info, contact details, and prompts for image generation.
- **Database**: Uses SQLite to store settings and prompts persistently.
- **Console Feedback**: Logs "BOT STARTED" and API request statuses for easy debugging.

### 🛠️ Installation
1. Install required packages:
   ```bash
   pip install aiogram requests
   ```
2. Update the following in `stable_diffusion_bot.py`:
   - `TOKEN`: Your Telegram bot token from [@BotFather](https://t.me/BotFather).
   - `ADMIN_ID`: Your Telegram user ID (find it via [@userinfobot](https://t.me/userinfobot)).
   - `STABLE_DIFFUSION_API_KEY`: Your API key from [DreamStudio](https://dreamstudio.ai/).
3. Run the bot:
   ```bash
   python stable_diffusion_bot.py
   ```

### 📜 License
MIT License

---

## 🌟 Русский

Телеграм-бот на Python, который генерирует изображения через API DreamStudio (Stable Diffusion) с использованием aiogram 3.x и SQLite. 
Бот предоставляет удобное меню для создания изображений по настраиваемым промтам и админ-панель для управления текстами и настройками.

### 🚀 Возможности
- **Генерация изображений**: Создавайте красивые картинки с промтами вроде "Девушка-Джедай" или "Девушка-Штурмовик" через Stable Diffusion.
- **Главное меню**: Кнопки "Главная," "Информация," "Написать мне," "Девушка-Джедай," "Девушка-Штурмовик" и "Админка" (только для админа).
- **Админ-панель**: Ограниченный доступ для редактирования приветствия, информации, контактов и промтов для генерации.
- **База данных**: Использует SQLite для надежного хранения настроек и промтов.
- **Отладка в консоли**: Выводит "БОТ ЗАПУЩЕН" и статусы запросов к API для удобства.

### 🛠️ Установка
1. Установите необходимые библиотеки:
   ```bash
   pip install aiogram requests
   ```
2. Обновите следующие параметры в `stable_diffusion_bot.py`:
   - `TOKEN`: Токен вашего бота от [@BotFather](https://t.me/BotFather).
   - `ADMIN_ID`: Ваш Telegram ID (узнайте через [@userinfobot](https://t.me/userinfobot)).
   - `STABLE_DIFFUSION_API_KEY`: Ваш API-ключ от [DreamStudio](https://dreamstudio.ai/).
3. Запустите бота:
   ```bash
   python stable_diffusion_bot.py
   ```

### 📜 Лицензия
Лицензия MIT
