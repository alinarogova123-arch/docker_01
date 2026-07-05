# StaticJinjaPlus Port

Докер порт StaticJinjaPlus

## Перменные окружения

Для изменения заданных по умолчанию значений задать перменные а виде `ПЕРЕМЕННАЯ=значение`.

- SJP_VERSION: Версия StaticJinjaPlus (по умолчанию `latest`)
- LOCAL_SRC_DIR: Директория с шаблонами (по умолчанию `templates`)
- LOCAL_OUT_DIR: Директория с собранными страницами (по умолчанию `build`)

### Доступные версии образов:

| Версия (Тег) | Базовая система |
| :--- | :--- |
| **`latest`** | Ubuntu |
| **`slim`** | Python-Slim |
| **`0.1.1`** | Ubuntu |
| **`0.1.1-slim`**| Python-Slim |
| **`0.1.0`** | Ubuntu |
| **`0.1.0-slim`**| Python-Slim |
| **`develop`** | Ubuntu |
| **`develop-slim`**| Python-Slim |

## Запуск

Docker должен быть уже установлен.

Для запуска разовой сборки:

```
docker compose run --rm compiler
```

Для запуска в режиме отслеживания:

```
docker compose run --rm watcher
```

## Цели проекта

Код написан в учебных целях — для курса по Python и веб-разработке на сайте [Devman](https://dvmn.org).
