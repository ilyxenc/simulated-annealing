# simulated-annealing
Алгоритм имитации отжига — общий алгоритмический метод решения задачи глобальной оптимизации, особенно дискретной и комбинаторной оптимизации. Один из примеров методов Монте-Карло.

# Задание:
Найти длину гамильтонова цикла **_S<sub>4</sub>_** в полном графе **_K<sub>6</sub>_** после четырех циклов решения задачи методом отжига. Даны расстояния **_L<sub>i,j</sub>_** между вершинами. Даны также: начальная последовательность вершин **_V_**, последовательность замен вершин **_Z_** и выпавшие при этом вероятности перехода **_P<sub>k</sub>_**, **_k = 1,...,4_**. Переход на худшее (**_∆S<sub>k</sub> = S<sub>k</sub> − S<sub>k-1</sub> > 0_**) решение допустим, если **_P<sub>*</sub>_ _=_ _100e<sup>−∆S<sub>k</sub>/T<sub>k</sub></sup>_ _>_ _Pk_**, где снижение температуры происходит по закону **_T<sub>k+1</sub> = 0.5T<sub>k</sub>_** от **_T<sub>1</sub> = 100_**.

<img width="300" alt="Полносвязный граф" src="https://user-images.githubusercontent.com/44255660/141200530-68b4c474-7f94-4c6d-8b99-dc77842bf1f3.png">
