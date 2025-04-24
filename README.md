# Hibernate + Redis: Сравнение производительности

## Обзор

Приложение демонстрирует:

*   Использование Hibernate ORM для работы с базой данных.
*   Кэширование данных в Redis.
*   Сравнение производительности MySQL и Redis.

## Основные возможности

*   Пакетная загрузка данных в БД.
*   Кэширование в Redis.
*   Оптимизация SQL-запросов.

## Технологии

*   Java 18
*   Hibernate 5.6
*   MySQL 8
*   Redis
*   Maven

## Установка

1.  Убедитесь, что MySQL и Redis запущены.
2.  Настройте `src/main/resources/spy.properties`.
3.  Импортируйте схему [БД](https://javarush.com/downloads/ide/javarush/dump-hibernate-final.sql).

## Запуск

```bash
mvn clean install