# Polinomios
Un polinomio de grado n es una función matemática de la forma:

![image](https://user-images.githubusercontent.com/5318519/170802456-a10bcc98-d6bb-4c8e-8414-32ccbbbf437d.png)

donde x es el parámetro y a<sub>0</sub>, a<sub>1</sub>, … , a<sub>n</sub> son números reales dados.

Algunos ejemplos de polinomios son:

![image](https://user-images.githubusercontent.com/5318519/170802537-dc5398b6-42d4-4cdb-a1f3-77b7964464bc.png)

Los grados de estos polinomios son, respectivamente, 2, 1, 5 y 80.

Evaluar un polinomio significa reemplazar x por un valor y obtener el resultado. Por ejemplo, si evaluamos el polinomio p en el valor x=3, obtenemos el resultado:

p(3)=1+2⋅3+3<sup>2</sup>=16

Un polinomio puede ser representado como una lista con los valores a<sub>0</sub>, a<sub>1</sub>, … , a<sub>n</sub>. Por ejemplo, los polinomios anteriores pueden ser representados así en un programa:

![image](https://user-images.githubusercontent.com/5318519/170802594-b7d23741-97e2-46b1-9bc7-b0ad2e71b557.png)

Observa que la posición (indice) en el arreglo es igual a la potencia, y que los valores son los coeficientes. Por lo tanto para el ultimo ejemplo, deberas tener un arreglo de 81 posiciones y solo la posicion 40 y 80 tendran un valor el 5 y 2 respectivamente.

1. Escriba la función grado(p) que entregue el grado de un polinomio:
```
>>> grado(r)
5
>>> grado(s)
80
```
2. Escriba la función evaluar(p, x) que evalúe el polinomio p (representado como una lista) en el valor x:
```
>>> evaluar(p, 3)
16
>>> evaluar(q, 0.0)
4.0
>>> evaluar(r, 1.1)
-2.82347
>>> evaluar([4, 3, 1], 3.14)
23.2796
```
3. Escriba la función sumar_polinomios(p1, p2) que entregue la suma de dos polinomios:
```
>>> sumar_polinomios(p, r)
[0, 2, 1, -5, 0, 3]
```
