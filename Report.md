# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

17.03.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Некорректный статус для валидных карт с номером из 19 цифр](https://github.com/yulchespunches/Java-1.1/issues/1.md)
* [Некорректный статус для валидных карт платежной системы American Express](https://github.com/yulchespunches/Java-1.1/issues/2.md)
* [Некорректный статус для валидных платежной системы Diners Club](https://github.com/yulchespunches/Java-1.1/issues/3##.md)


* Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [List_of_Tested_Valid_Credit_Card_Number] https://github.com/yulchespunches/Java-1.1/blob/main/List_of_Tested_Valid_Credit_Card_Number.md 
* [src] https://github.com/yulchespunches/Java-1.1/tree/main/src

В качестве тестовых данных использовались данные:
* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [Установка IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)


Тестирование производилось в следующем окружении:
* MacBook Pro (13-inch, 2018, Four Thunderbolt 3 Ports)
* Java 11.0.9.1
* IntelliJ IDEA Community Edition 2020.3.1
