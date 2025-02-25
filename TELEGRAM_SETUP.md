# Инструкция по размещению Mini App в Telegram

## 1. Регистрация бота
1. Откройте Telegram и найдите @BotFather
2. Отправьте команду `/newbot`
3. Следуйте инструкциям для создания нового бота
4. Сохраните полученный токен бота

## 2. Создание Mini App
1. В чате с @BotFather отправьте `/newapp`
2. Выберите бота, для которого создаете Mini App
3. Укажите короткое имя для вашего приложения
4. Загрузите иконку приложения
5. Укажите описание приложения

## 3. Настройка URL
1. После развертывания приложения на хостинге, получите HTTPS URL
2. Отправьте команду `/setdomain` в @BotFather
3. Выберите ваше приложение
4. Укажите полученный HTTPS URL

## 4. Публикация
1. Приложение будет доступно по ссылке: `https://t.me/{bot_username}/app`
2. Пользователи смогут открывать приложение через:
   - Меню бота
   - Прямую ссылку
   - Встраивание в другие чаты

## Важные замечания
- URL должен использовать HTTPS
- Домен должен быть доступен из Telegram
- При обновлении приложения изменения будут видны сразу, так как Telegram загружает веб-приложение напрямую с вашего сервера

## Тестирование
1. Откройте ссылку `https://t.me/{bot_username}/app`
2. Убедитесь, что приложение корректно открывается
3. Проверьте все функции в окне Telegram

## Обновление приложения
- Просто обновите код на вашем сервере
- Telegram будет загружать актуальную версию автоматически
- Не требуется дополнительных действий в @BotFather
