# 14. Обработка фотографий покупателя — компьютерное зрение

### Описание проекта

Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
* Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
* Контролировать добросовестность кассиров при продаже алкоголя.

Требуется построить модель, которая по фотографии определит приблизительный возраст человека. В распоряжении есть набор фотографий людей с указанием возраста.

### Данные

Данные взяты с сайта ChaLearn Looking at People.
В вашем распоряжении одна папка со всеми изображениями и CSV-файл labels.csv с двумя колонками: `file_name` и `real_age`. 

### Навыки и инструменты

* обработка изображений
* нейронные сети
* pandas
* keras
