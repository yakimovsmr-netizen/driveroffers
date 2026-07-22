# DriverOffers — Telegram Mini App

## Как запустить

### 1. Локальный просмотр (прямо сейчас)
Открой index.html в браузере — всё работает без сервера.

### 2. Публикация на GitHub Pages (бесплатный хостинг)
```bash
cd ~/.osy/files/driveroffers
git init
git add .
git commit -m "DriverOffers mini app"
gh repo create driveroffers --public --push --source=.
# Потом: Settings → Pages → Deploy from branch main
# URL будет: https://ВАШ-НИК.github.io/driveroffers/
```

### 3. Подключение к Telegram боту
1. Открой @BotFather в Telegram
2. /newbot → дай имя → получи TOKEN
3. /newapp → выбери своего бота → вставь URL GitHub Pages
4. Готово — бот открывает мини-апп!

## Что внутри
- 16 реальных офферов по 5 категориям (АЗС, страхование, еда, автосервис, шиномонтаж)
- Промо-баннер таксопарка «ПрямойКурс» с обратным таймером
- Генерация купонов с уникальными кодами
- Поиск по офферам
- Профиль водителя со статистикой
- Полная интеграция Telegram WebApp API
