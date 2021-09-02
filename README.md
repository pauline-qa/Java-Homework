# Отчёт о тестировании CC Validator

## Краткое описание

20.07.2021 - 22.07.2021 было проведено функциональое тестирование приложения CC Validator.

На тестирование затрачено: 10 часов

В результате тестирования выявлены следующие дефекты:
* [При вводе номера карты из 19 цифр результат Fail](https://github.com/pauline-qa/Java-Homework/issues/1)
* [При вводе номера карты из 14 цифр результат Fail](https://github.com/pauline-qa/Java-Homework/issues/2)
* [При вводе номера карты из 15 цифр результат Fail](https://github.com/pauline-qa/Java-Homework/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Тест-план](https://docs.google.com/spreadsheets/d/1vZFs_KeLIwim_f-vLADp9SXLa0FUTmAuCFcXPLPLKwQ/edit?usp=sharing)
  
В качестве тестовых данных использовались данные с сайта [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):
### Карты с 14 символами:
* 30595062885069
* 30433585862847
* 36216697850915
* 36106046423854

### Карты с 15 символами:
* 377574477453079
* 376127144691703
* 345845990323554
* 348398069085503

### Карты с 16 символами:
* 4916695085496299
* 4556694092969914
* 6011288752450127
* 6011408041204735
* 3542395687593155

### Карты с 19 символами:
* 4532686419372591447
* 6011442814681265022
* 3530715928283087378
* 4539880027584902531

Тестирование производилось в следующем окружении:
* macOS Big Sur Version 11.4 
* openjdk version "11.0.11"  
* OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
* OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)