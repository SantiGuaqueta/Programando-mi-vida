# Programando-mi-vida -:smile:
El dia de hoy resolveremos el reto 4 propuesto en clase el cual consiste en 2 cosas las cuales son :

1 Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.
2 Revise el procedimiento matemático para hallar raices cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.

Como soy un primiparo en la programacion lo resolvere de la forma mas facil que pueda yo entender y realizar:
## Primer punto 
Primero mostrare el Pseudocode para el algoritmo pedido y despues el diagrama de flujo.
```pseudocode
[Inicio]
[variables]
N=entero =ingresado
M=entero=√N +1
lista 1=[2 hasta N]
lista 2=[2 hasta M]
    Para cada j en la lista 2 hacer
      Para cada i en la lista 1 hacer 
        si(i>j) y residuo (i/j)=0)entonces
		 remover i de la lista 1
	  Fin si
	Fin para
Fin para
Imprimir lista 1
[fin]
```
[![diagrama-P-gina-1.jpg](https://i.postimg.cc/fRs5yFyf/diagrama-P-gina-1.jpg)](https://postimg.cc/crDf5FQv)

### Segundo punto
Este segundo punto lo realizare al contrario primero mostrare el diagrama de flujo y despues el Psudocode para este algoritmo.
[![diagrama-P-gina-1-drawio.png](https://i.postimg.cc/9F0wpYSH/diagrama-P-gina-1-drawio.png)](https://postimg.cc/8j8CkMNZ)
```pseudocode
[Inicio]
[variables]
N=entero=ingresado
x=entero=ø
Lista 1=[lista de numeros impares de 1 hasta N]
  Para cada i en la lista 1 hacer
       Si N>ø entonces 
	   N=N-i
       x=x+1
    Fin si
Fin Para
Imprimir(x)
[fin]
```
#### Fin
Gracias por leer hasta el final que tengas buen día.
