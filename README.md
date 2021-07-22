# Отчёт о тестировании CC Validator

## Краткое описание

20.07.2021 - 22.07.2021 было проведено функциональое тестирование приложения CC Validator.

На тестирование затрачено: 10 часов

В результате тестирования выявлены следующие дефекты:
* При вводе номера карты из 19 цифр результат Fail <https://github.com/pauline-qa/Java-Homework/issues/1>
* При вводе номера карты из 14 цифр результат Fail <https://github.com/pauline-qa/Java-Homework/issues/2>
* При вводе номера карты из 15 цифр результат Fail <https://github.com/pauline-qa/Java-Homework/issues/3>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* тест-кейс <https://github.com/pauline-qa/Java-Homework/issues/4>
* баг-репорты <https://github.com/pauline-qa/Java-Homework/issues/1> <https://github.com/pauline-qa/Java-Homework/issues/2> <https://github.com/pauline-qa/Java-Homework/issues/3>

В качестве тестовых данных использовались данные с сайта <https://www.freeformatter.com/credit-card-number-generator-validator.html>:
* 4539993275089660 - OK
* 4916281490297447019 - OK
* 6011047611604732 - OK
* 30176677933238 - OK

Тестирование производилось в следующем окружении:
* macOS Big Sur Version 11.4
* Java version 11