#ReactStarterKit

## Как использовать

### Требования

Должна быть установлена NodeJS
[Как установить Node.js](https://www.digitalocean.com/community/tutorials/node-js-ubuntu-18-04-ru#Установка-при-помощи-nvm)

### Установка

Устанавливаем пакеты

```
npm ci
```

## Запуск в режиме разработчика

Запуск в dev-сервера (будет доступен по адресу http://0.0.0.0:8000/)

```
npm run start
```

Сборка проекта

```
npm run build
```

## Разработка

### Структура папок

* `app` - Корень приложения;
* `fonts` - Шрифты;
* `helpers` - Хелперы;
* `icons` - Иконки;
* `images` - Картинки;
* `modules` - Модули;
* `styles` - Стили.

### Модули

#### Структура модуля

* `actions` - экшены;
* `api` - апи;
* `components` - компоненты;
* `constatnts` - константы;
* `reducers` - редьюсеры;
* `selectors` - селекторы;
* `types` - типы;

Структурируются по сущностям
