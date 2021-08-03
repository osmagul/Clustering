# Banners
### Размещение баннеров
- Необходимо кластеризовать данные координаты, чтобы выявить центры скоплений туристов. Поскольку баннеры имеют сравнительно небольшую площадь действия, нам нужен алгоритм, позволяющий ограничить размер кластера и не зависящий от количества кластеров.
- Определить 20 ближайших к баннерам центров кластеров. Т.е. посчитать дистанцию до ближайшего офиса для каждой точки и выбрать 20 с наименьшим значением.
- checkins.dat - файл с координатами баннеров, CarnivalCruiseLine.txt - файл с координатами офисов
- checkins.dat можно найти по этой ссылке: https://github.com/yuranich/ml_specialization/blob/master/checkins.dat
