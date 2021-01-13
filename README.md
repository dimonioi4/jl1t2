# Отчёт о тестировании Credit Card Number Validator
## Краткое описание

13.01.2021 - 13.01.2021 было проведено тестирование приложения Credit Card Number Validator на основе метода эквивалентных значений, на основе опыта и предположениях об ошибках.

На тестирование затрачено: 1 час.


## Описание процесса тестирования

В качестве тестовых данных использовались данные :
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Код Credit Card Number Validator](https://github.com/netology-code/javaqa-code/blob/master/1.1_intro/hello-programming/src/Main.java)

Все номера карт являются вымышленными, созданные генератором случайных номеров карт.

### Ожидаемый результат тестирования:

Для валидных номеров карт "Result is OK";  
Для невалидных номеров карт "Result is FAIL";

### Фактический результат тестирования:

5404368477854170 - Result is OK  
0000000000000000 - Result is FAIL  
" " - Result is FAIL  
54043684778541700 - Result is FAIL  
абырвалг - Result is FAIL  
40436847785417 Result is FAIL

Дефектов не выявлено.

Тестирование производилось в следующем окружении:

    <Windows 10 x64>
    <версия Java 11.0.9.1 2020-11-04>
    <IntelliJ IDEA Community>
   
