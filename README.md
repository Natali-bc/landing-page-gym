# Starter

## Запуск сборки

Инсталяция зависимостей

```
npm i
```

Сборка запускается командой

```
npm start
```

## Структура проекта

### В сборке используется шаблонизатор nunjuks

> https://mozilla.github.io/nunjucks/templating.html.

- Страницы проекта хранятся в папке **pages**

- Секционные фрагменты хранятся в папке **partials**

- Чтобы подключить на страницу фрагмент хранящийся в **_partials_**

```
{% include 'sidebar.html' %}
```

- Можно вызывать переменные используя токены

```
Здесь будет {{ Title }}
```

- Записать значение переменной для текущего шаблона

```
{% set title = "Заголовок" %}
```
