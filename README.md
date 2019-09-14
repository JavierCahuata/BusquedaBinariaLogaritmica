# Explicación de la Complejidad Logaritmica de la Busqueda Binaria

Partimos del hecho de que para la busqueda binaria se requiere que el conjunto de numeros este ordenado.

![image](https://raw.githubusercontent.com/JavierCahuata/fibonacci/master/20190913-175938.jpg)

Para un conjunto de datos n, partimos en 2 el conjunto para la primera iteración es decir un n/2

![image](https://raw.githubusercontent.com/JavierCahuata/fibonacci/master/20190913-180026.jpg)

para la segunda iteración detenemos un n/4

![image](https://raw.githubusercontent.com/JavierCahuata/fibonacci/master/20190913-180042.jpg)

para la tercera iteración iteración detenemos un n/8

![image](https://raw.githubusercontent.com/JavierCahuata/fibonacci/master/20190913-180053.jpg)

por lo que podemos decir que para encontrtar el numero que estamos buscando tenemos que 1 = n / 2^x. entonces tendriamos lo siguiente: 

![image](https://raw.githubusercontent.com/JavierCahuata/fibonacci/master/20190913-180205.jpg)
