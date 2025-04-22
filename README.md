# FoodPlanBot

Telegram-бот и админка на Django для выдачи рецептов и планирования рациона.

## 🚀 Стек технологий
- Python 3.11+
- Django 5.2
- Aiogram 3.x
- SQLite (для MVP, можно заменить на PostgreSQL)

## 📦 Установка

```bash
# Клонируем репозиторий
git clone https://github.com/your_username/FoodPlanBot.git
cd FoodPlanBot

# Создаём виртуальное окружение
python -m venv venv
source venv/bin/activate  # или .\venv\Scripts\activate на Windows

# Устанавливаем зависимости
pip install -r requirements.txt

# Создаём .env файл 
cp .env

# Выполняем миграции
python manage.py migrate

# Запускаем Django-сервер
python manage.py runserver

# Запуск Telegram-бота
python run_bot.py
```

## ⚙️ Переменные окружения (.env)

```env
BOT_TOKEN=your-secret-token
```


## 🧠 Что реализовано в MVP
- Выдача рецептов с картинками
- Поддержка фильтров: веган/без глютена/бюджет
- Лайки/дизлайки на блюда
- Генерация списка покупок
- Админка для добавления/удаления рецептов

## 🔜 В планах
- Интеграция платёжки
- Уведомления в Telegram
- Расчёт бюджета на неделю

## 🤝 Вклад
Пулл-реквесты и идеи приветствуются! Просто создайте issue или предложите улучшение.

## 📄 Лицензия
Проект сделан в рамках MVP для частного использования. Распространяется по лицензии MIT.

