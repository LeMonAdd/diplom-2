# Дипломный проект №2 Яндекс практикум (автоматизация API)

### Используемые технологии:

1. Java 11
2. Junit 4.13.2
3. Gson 2.10.1
4. Rest-assured 5.3.0
5. Javafaker 1.0.2
6. allure-junit4 2.15.0
7. Allure-rest-assured 2.15.0
8. Commons-lang3 3.11

Тестируемый сервис - https://stellarburgers.nomoreparties.site/

Документация API - https://code.s3.yandex.net/qa-automation-engineer/java/cheatsheets/paid-track/diplom/api-documentation.pdf

### Описание классов пакета test.java

CreateOrderTest - ручка создания заказов

CreateUserTest - ручка создания пользователя 

LoginUserTest - ручка авторизации пользователя

ReceivingOrdersFromSpecificUserTest - ручка получения заказа

UpdateUserTest - ручка изменения данных о пользователе

### Описание классов пакета main.java.model

В данном пакете содержится модель пользователя и заказа

### Описание классов пакета main.java.client

Данный класс содержит основной функционал автотестового проекта

UserClient - класс взаимодействия с пользователем

UserCredentional - содержит конф. данные пользователя 

UserGenerator - создаёт уникального пользователя с обязательными полями

Для запуска тестов необходимо в консоли проекта ввести команду mvn clean test