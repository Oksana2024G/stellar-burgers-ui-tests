# Автоматизация UI-тестирования веб-приложения Stellar Burgers

### Технологический стек:
Python, Pytest, Selenium, Allure, POM

### Запуск автотестов

**Установка зависимостей**

> `$ pip install -r requirements.txt`

**Запуск автотестов с формированием отчётов allure**

>  `pytest --alluredir=allure_results`

| Название файла              | Содержание файла                                |
|-----------------------------|-------------------------------------------------|
| Tests dir                   | Директория с тестами                            |
| test_forgot_password.py     | Тесты на восстановление пароля                  |
| test_main_functionality.py  | Тесты на основную функциональность                    |
| test_order_feed.py          | Тесты на Ленту заказов                          |
| test_personal_account.py    | Тесты на Личный кабинет                         |
| conftest.py                 | Фикстуры                                        |
| Pages dir                   | Директория с методами                           |
| base_page.py                | Базовые методы                                  |
| main_page.py                | Методы главной страницы основного функционала   |
| account_page.py             | Методы личного кабинета                         |
| login_page.py               | Методы восстановления пароля при входе          |
| order_feed_page.py           | Методы ленты заказов                            |
| Locators dir                | Директория с локаторами                         |
| account_page_locator.py     | Локаторы личного кабинета                       |
| login_page_locator.py       | Локаторы для восстановления пароля при входе    |
| main_page_locator.py        | Локаторы главной страницы основного функционала |
| order_feed_page_locator.py   | Локаторы ленты заказов                          |
| curl.py                     | Файл с URL                                      |
| generators.py               | Генератор данных пользователя                   |
| requirements.txt            | Файл с зависимостями                            |
| allure_results.dir          | Папка с отчетами Allure                         |
