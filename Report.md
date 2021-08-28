# Отчёт о тестировании "Валидация номеров банковских карт"
	
## Краткое описание
	
28.08.2021 - 28.08.2021 было проведено тестирование "Валидация номеров банковских карт" приложения "Credit Card Number Validator"
	
На тестирование затрачено: 2
	
В результате тестирования выявлены следующие дефекты:
* [Issue:The program does not accept the values of card numbers not consisting of 16 digits](https://github.com/Margo-785/Credit-Card-Number-Validator/issues/1#issue-981841269)
	
##Описание процесса тестирования
	
* Ввод тестового номера карты в код
* Анализ результата
	
В качестве тестовых данных использовались номера кредитных карт разных банков с сайта [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):

![Card Numbers test](https://github.com/Margo-785/Credit-Card-Number-Validator/blob/master/list%20of%20bank%20card%20numbers.png?raw=true)

Тестирование производилось в следующем окружении:
* Windows 10 Домашняя для одного языка, версия 2004, сборка ОС 19041.1052 (64bit)
* Java version 11.0.12
* IntelliJ IDEA 2021.2(Community Edition) Build #IC-212.4746.92, built on July 27, 2021