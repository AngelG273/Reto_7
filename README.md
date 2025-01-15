# Reto_7

## Punto 1: 

``` Python
i : int = 0 
# Se evaluan los i hasta 100
while(i < 100): 
  # se la suma 1 para evaluar digito por digito
  i += 1 
  # Se imprime cada i y su cuadrado
  print(i, i**2) 
```

## Punto 2

``` Python
if __name__ == "__main__":
  print("Numeros impares")
  # Numeros impares hasta el 999
  i : int= -1
  while i < 999:
    i+=2  # Al sumarle 2 a valor que toma i apartir de -1 este se vuelve impar
    print (i)

  print("Numeros pares")
  # Numeros pares hasta el 1000
  i : int= 0
  while i < 999:
    i+=2  # Al sumarle 2 a cada valor que toma i apartir de 0 este se vuelve par
    print (i) 
  ```

## Punto 3

``` Python
if __name__ == "__main__":
  #Se evalua que el numero ingresado sea mayor o igual a 2
  while True:   
    n = int ( input ("Ingrese un numero mayor a 2:"))
    if n >= 2:
      break
    else:
      print (int(input("Ingrese un numero mayor a 2:")))

  # Se evalua que el numero sea par
  for i in range(n,1,-1):
    if i % 2 == 0:
      # Se imprime el numero par
      print (i)
```

## Punto 4

``` Python
# Se define la funcion factorial_de_numero
def factorial_de_numero(n):
  factorial = 1
  for i in range(1,n+1):
    factorial *=i # Se multiplica el 1 por el numero que esta dentro del rango
  return factorial

if __name__=="__main__":
  #Se define el valor n
  n = int ( input ("Ingrese un numero natural:"))
  #se define el rango para i
  for i in range(1,n+1):
    # se llama la función factorial
    Factorial_n = factorial_de_numero(i)
    # Se imprime i y su factorial
    print(str(i) + " su factorial es " + str(Factorial_n))
```

## Punto 5

``` Python
if __name__=="__main__":
  #Se define n
  n = int(input("Ingrese un numero: "))
  #Se define el rango para i
  for i in range(0,n+1):
    #Se da la cual va a ser elevada a i
    a : int =2
    a**=i
# Imprime el valor al cual se va aelevar 2 y el resultado de elvarlo
print("2 elevado a " + str(n) + " es " + str(a))
```

## Punto 6

``` Python

```

## Punto 7

``` Python
# función para las tablas de multplicar
def tablas_multiplicar():
  #Se define el rango para las tablas
  for i in range(1, 10):
    # Se imoprime un separador para las tablas
    print("Tabla de multiplicar del" + str (i))
    #Se define el rango de los valors que multiplican a i
    for j in range(1, 10+1):
      print(str(i) + " x " + str(j) +" = "+ (str(i * j)))
    print()  # Línea en blanco para separar las tablas

if __name__ == "__main__":
  #Utilizamos la función
  tablas_multiplicar()
```

## Punto 8

``` Python

```

## Punto 9

``` Python

```

