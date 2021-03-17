# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

12.01.2020 - 13.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Некорректный статус для валидных карт с номером из 19 цифр](https://github.com/kseniabobkova/Credit-Card-Number-Validator/issues/1)
* [Некорректный статус для валидных карт платежной системы American Express](https://github.com/kseniabobkova/Credit-Card-Number-Validator/issues/2)
* [Некорректный статус для валидных платежной системы Diners Club](https://github.com/kseniabobkova/Credit-Card-Number-Validator/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [List_of_Tested_Valid_Credit_Card_Number](https://github.com/kseniabobkova/Credit-Card-Number-Validator/blob/master/List_of_Tested_Valid_Credit_Card_Number.md)
* [src](https://github.com/kseniabobkova/Credit-Card-Number-Validator/tree/master/src)

В качестве тестовых данных использовались данные:
* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [Установка IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)


Тестирование производилось в следующем окружении:
* Windows 10 Pro Version: 87.0.4280.88 (Official Build) (64-bit)
* Java 11.0.9.1
* IntelliJ IDEA Community Edition 2020.3.1
