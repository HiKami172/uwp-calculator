# CustomCalculatorUWP
Репозиторий содержит приложение и автоматизированные тесты
## О приложении:
Калькулятор, предназначенный для работы с вещественными числами. Содержит стандартные бинарные операции, а также операцию возведения в квадрат.

### Версия 1.1

## ПО для запуска:
- Microsoft Visual Studio 2019
- ОС Windows 8 или старше
- WinAppDriver

## Запуск приложения:
- Скомпилировать проект в Visual Studio c параметром "Release" и разрядностью своей системы
- Открыть поддиректорию проекта bin/Release/{Разрядность системы} и запустить .exe файл

## Запуск тестового проекта:
- Скомпилировтаь(build) тестируемое приложение с параметром "Debug" и задеплоить(deploy)
- Откыть тестовый проект и запустить окно Test Explorer (View->Test Explorer)
- Добавить в проект nuget пакет "Appium.WebDriver"
- Выбрать параметр "Release" и целевую платформу "x64"
- Запустить WinAppDriver
- Нажать кнопку "Запустить все" в  окне Test Explorer

### Информация о тест-кейсах, автоматизированных в тестовом проекте "CalculatorTest":
https://docs.google.com/document/d/1dRSpHp9ci0NRsBbwphMJRrtM38ARr7kDDtclKT-5LoU/edit?usp=sharing