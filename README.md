# CV_3

На основе ноутбука из предыдущего задания (с классификацией по CIFAR10), свернуть нейросеть, используя минимум два уровня свертывания (как в примере из лекции). Желательно добиться как можно большего значения accuracy. Можно менять функции активации, функцию ошибки (loss), глубину свертывания, типы слоев, количество слоев, оптимизаторы, количество эпох и т.д. Нельзя менять метрику и тип нейронной сети (CNN).


1) Имортируем нужные библиотеки и подгружаем датасет:

![Image alt](https://github.com/dnlqwer/CV_3/blob/main/pic/1.png)


2) Стандартизируем данные: 

![Image alt](https://github.com/dnlqwer/CV_3/blob/main/pic/2.png)


3) Устанавливем слои для модели, используя MaxPooling:   

![Image alt](https://github.com/dnlqwer/CV_3/blob/main/pic/3.png)


4) Компилируем модель:

![Image alt](https://github.com/dnlqwer/CV_3/blob/main/pic/4.png)


5) Обучаем модель: 

![Image alt](https://github.com/dnlqwer/CV_3/blob/main/pic/5.png)


6) Прогоняем тестовый набор:

![Image alt](https://github.com/dnlqwer/CV_3/blob/main/pic/6.png)


7) Результат:

![Image alt](https://github.com/dnlqwer/CV_3/blob/main/pic/7.png)
