## Python Basico Nivel 2

### Funciones Basicas II

1. Cuenta regresiva : crea una función que acepte un número como entrada. Devuelve una nueva lista que cuenta hacia atrás en uno, desde el número (como el elemento 0) hasta 0 (como el último elemento).

* Ejemplo: la cuenta regresiva (5) debería devolver [5,4,3,2,1,0]
```py
def ejercicio_1(Num):
    for x in range(Num, -1, -1):
        print(x)

ejercicio_1(5)
```

2. Imprimir y volver : crea una función que recibirá una lista con dos números. Imprima el primer valor y devuelva el segundo.

* Ejemplo: print_and_return ([1,2]) debería imprimir 1 y devolver 2
```py
def ejercicio_2(array):
    print(x[0])
    return x[1]
    
x = [1,2]
print(ejercicio_2(x))
```


3. First Plus Length : crea una función que acepta una lista y devuelve la suma del primer valor de la lista más la longitud de la lista.

* Ejemplo: first_plus_length ([1,2,3,4,5]) debería devolver 6 (primer valor: 1 + longitud: 5)
```py
def first_plus_length(array):
    return array[0] + len(array) 

x = [1,2,3,4,5]
print("Returned:")
print(first_plus_length(x))
```

4. Valores mayores que el segundo : escribe una función que acepte una lista y crea una nueva lista que contenga solo los valores de la lista original que sean mayores que su segundo valor. Imprima cuántos valores son y luego devuelva la nueva lista. Si la lista tiene menos de 2 elementos, haga que la función devuelva False

* Ejemplo: values_greater_than_second ([5,2,3,2,1,4]) debería imprimir 3 y devolver [5,3,4]
* Ejemplo: values_greater_than_second ([3]) debería devolver False

```py
def values_higher_than_second(array):
    storage = []
    if len(array) < 3:
        return False
    for i in range(0, len(array)):
        if array[i]>array[1]:
            storage.append(array[i])
    return storage
    

x = [5,2,3,2,1,4]
print("Returned:")
print(values_higher_than_second(x))
y = [3]
print("Returned:")
print(values_higher_than_second(y))
```

5. Esta longitud, ese valor : escribe una función que acepte dos enteros como parámetros: tamaño y valor. La función debe crear y devolver una lista cuya longitud es igual al tamaño dado y cuyos valores son todos los valores dados.

* Ejemplo: length_and_value (4,7) debería devolver [7,7,7,7]
* Ejemplo: length_and_value (6,2) debería devolver [2,2,2,2,2,2]

```py
def x_times_value(array):
    storage = []
    for i in range(0, array[0]):
        storage.append(array[1])
    return storage
    

x = [4,7]
print("Returned:")
print(x_times_value(x))
y = [6,2]
print("Returned:")
print(x_times_value(y))
```

### Funciones For Loop 2

```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```


```py

```

```py

```


