#### Краткое описание
Необходимо проверить работоспособность функционала валидации банковских карт в программе Credit Card Number Validator

* 22.11.2020 - 22.11.2020 , Ad hoc test приложения "Credit Card Number Validator"

На тестирование затрачено: 01:00 

#### В результате тестирования выявлено:
Валидные номера карт длиной <> 16 цифр не проходят проверку 
(https://github.com/NikiHollywood/1.1-vvedeniye-java/issues/5)

#### Описание процесса тестировании
Руководство по установке IntelliJ IDEA (https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
Код приложения находится в репозитории (https://github.com/NikiHollywood/1.1-vvedeniye-java)

#### Ожидаемый результат: 
В результате работы приложения в случае ввода валидного номера карты в консоль выводится
сообщение "Result is OK", в случае ввода невалидного значения - "Result is FAIL"

#### В качестве тестовых данных использовались данные:
* Для генерации банковских карт использовался ресурс (https://cartoved.ru/common/generator-kreditnyh-kart.html)

#### Тестирование производилось в следующем окружении:
* Win 10
* Java 11
