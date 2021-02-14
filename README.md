[![Build status](https://ci.appveyor.com/api/projects/status/j8tuhohrua3um04d?svg=true)](https://ci.appveyor.com/project/IrinaVasilenko88/ci)


# Обучение в Нетологии.

## Домашнее задание по курсу Автоматизированное тестирование

## Тема: Управление состоянием, Continuous Integration

- Настройка "Appveyor"
- Добавление JSON Schema
- Доработка JSON Schema (добавление способа валидации значения поля на два из возможных значения: "RUB" или "USD")

**Для запуска проекта:**
1. Склонировать проект из репозитория командой 

```
git clone https://github.com/IrinaVasilenko88/CI.git
``` 
2. Открыть склонированный проект в Intellij IDEA
3. Открыть в терминале каталог ```artifacts```
4. Для запуска приложения ввести команду ```java -jar app-mbank.jar```
5. Для запуска в браузере ввести ссылку http://localhost:9999/
6. Запустить команду ```gradlew test```
7. Для просмотра результатов в Appveyor нажать на значок бейджика в README.md(в начале документа)
