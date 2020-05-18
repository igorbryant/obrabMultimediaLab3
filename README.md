# obrabMultimediaLab3
### --2А--
Красный= 0.0007
Оранжевый= 0.0001
Синий= 0.0006.
Если смотреть на обучающую выборку, на график точности,  то Оранжевый сошелся быстрее всех и уже на 8 эпохе стал равен 1. Синий стал равен
1 на 11 эпохе, а красный на 13. Далее, на графике каждый из них имеет минимальные выбросы.
На графике потерь быстрее всех так же сходится Оранжевый. 
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/2a_1.jpg) 
На валидационной выборке на графике точности Оранжевый имеет наименьший разброс по сравнению с Синим и Красным( его верхние и нижние пики
имеют меньше, чем Красного и Синего). На графике потер Оранжевый и Синий ведут себя примерно одинаково, в то время, как у Красного видно 
значительное уменьшение во время от нулевого до второго шага.
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/2a_2.jpg) 
### Следовательно, я считаю, что Оранжевый, где lr= 0.0001- наиболее оптимальный.



### --3С--
Красный= 0.00045
Оранжевый= 0.0001
Синий= 0.00066.
На обучающей выборке, график точности, Оранжевый сходится быстрее остальных, но становится равным 1 только на 10 шаге вместе с Синим, в то
время, как Красный становится равен 1 на 8 шаге. Далее каждый имеет незначительные выбросы по точности. На графике потерь Оранжевый так же схоится быстрее
остальных, хоть и имеет изначально выброс.
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/3c_1.jpg) 
На валидационной выборке Оранжевый очень похож с Красным по разбросу, но все же Красный имеет более большие выбросы. Синий же тоже похож 
на Красный и Оранжевый график, но тк у него между 76 и 80 шагами, 88 и 92, 92 и 96 шагами отсутствуют значения, я считаю, что Оранжевый 
наиболее оптимальный.
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/3c_2.jpg) 
### По моему мнению Оранжевый lr=0.0001- наиболее оптимальный.


### --3D--
Красный= 0.0001
Оранжевый= 0.00055
Синий= 0.0004.
На обучающей выборке, график точности, Красный сходится быстрее всех и становится равным 1 на 27 шаге, Оранжевый на 29, Синий на 32.
Далее каждый имеет незначительные выбросы по точности. На графике потерь каждый из графиков имеют выбросы, у Красного самый меньший. Сходится Красный 
так же быстрее остальных.
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/3d_1.jpg) 
На валидационной выборке у Оранжевого графика наблюдается потеря значений на некоторых шагах. Красный и Синий графики ведут себ ядостаточно похоже,
но все же Синий имеет немного наибольший разброс, нежели Красный график. Смотря на потери у Красного графика наблюдаюся наименьше выбросы + у Синего
так же имеются потери значений на некоторых шагах.
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/3d_2.jpg) 
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/3d_3.jpg) 
### По моему мнению Красный lr=0.0001- наиболее оптимальный.

### --3E--
Красный= 0.001
Оранжевый= 0.0002
Синий= 0.0001.
На обучающей выборке: 1) на графике точности видим, что Красный изначально имеет сильный по сравнению с Оранжевым и Синим выброс, потом же ситуация нормализуется. Оранжевый и Синий ведут себя достаточно схоже , имея незначительные выбросы. 2) на графике потерь Красны имеет выброс наиболее больший, чем остальные, но к концу такого не наблюдается.

На валидационной выборке: 1) на графике точности лучше всего себя показывает Синий, так как имеет немного меньший разброс. В целом графики ведут себя схоже. 2) на графике потерь Синий показывает себя лучше всего, имея значительно меньшие выбросы.

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/3e_1.jpg) 
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab3/raw/master/3e_2.jpg) 
### По моему мнению Синий lr=0.0001- наиболее оптимальный.
