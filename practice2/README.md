## Задание 1: Создайте свой собственный фильтр через инициализацию матрицы


Сделал матрицу следующего вида:

![](https://github.com/CepbluKot/image_processing/blob/master/practice2/task_1_res_2.png)

Сравнение с GaussianBlur:

![](https://github.com/CepbluKot/image_processing/blob/master/practice2/task_1_res.png)

Вывод: получили эффект размытия благодаря выбору только тех пикселей, который находятся на диагоналях, эффект похож на GaussianBlur, однако оказывает более сильное размытие при меньшем размере матрицы относительно GaussianBlur (на картинке 1 нашей матрицы размерность 7*7, у GaussianBlur 11*11)

## Задание 2: Напишите алгоритм выделения границ контрастного объекта на изображении

Сравнение выделения при помощи перевода в HSV + Canny с разницей изображений:

![](https://github.com/CepbluKot/image_processing/blob/master/practice2/task_2_res_1.png)

Проверка алгоритмов на реальном видео с камеры:

![](https://github.com/CepbluKot/image_processing/blob/master/practice2/task_2_res_2.gif)
