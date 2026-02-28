# Recipes exchange

[![CI](https://github.com/BU-Marina/RecipesExchange/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/BU-Marina/RecipesExchange/actions/workflows/ci.yml)

## Описание

Платформа для обмена рецептами

## Запуск проекта в контейнерах

Выполнить из директории с файлом docker-compose_local.yaml (infra/)

```
docker-compose -f docker-compose_local.yml up -d --build
```

После запуска в контейнерах проект будет доступен по:

```
http://localhost/
```

Остановить и удалить контейнеры и volumes:

```
docker-compose -f docker-compose_local.yml down -v
```
