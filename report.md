# Отчёт о тестировании <Credit Card Number Validator>

## Краткое описание

<29.03.2021> - <30.03.2021> было проведено <тестирование белого ящика - покрытие условий> приложения <Credit Card Number Validator>.

На тестирование затрачено 8 часов

В результате тестирования выявлены следующие дефекты:
* <https://github.com/July-git/java1/issues>


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [исходный код программиста](https://github.com/netology-code/javaqa-homeworks/tree/master/intro).md

В качестве тестовых данных использовались данные <https://www.freeformatter.com/credit-card-number-generator-validator.html#validate>:
* VISA<4916567726651741>-result is OK
* MasterCard<5468445907236963>-result is OK
* InstaPayment<6391621884328722>-result is OK
* Diners Club - Carte Blanche<30030663214899>-result is OK
* VISA<4916519517228653309>-result is OK
* Diners Club - International<36647101055321>-result is OK
* AMEX<370830593655279>-result is OK
* JCB<3532367932029683>-result is OK

Тестирование производилось в следующем окружении:
* <Microsoft Windows 8.1 Pro>
* <Java version "11.0.10">
* <Google Chrome>
