informatica

En pseudocódigo, cuando no se definen funciones ni suprocesos, el programa en pseudocódigo sólo incluye la palabra reservada `Algoritmo` o `Proceso`, seguida del nombre del algoritmo que se utiliza para definir el inicio de un algoritmo. Luego, le sigue una secuencia de instrucciones y finaliza con la palabra reservada `FinAlgoritmo` o `FinProceso`.

`El ejemplo más simple de esta construcción es el programa Suma.psc de la Ayuda de PSeInt, un pequeño algoritmo que pide al usuario dos números para sumarlos y, después, muestra el resultado de la operación, al cual se le han hecho algunas adecuaciones para Señale las partes del algoritmo y el nombre de las variables en minúsculas:`

```
  // suma.psc
```
    // El ejemplo más simple de la Ayuda de PSeInt (2003)
    // Solicita dos numeros, los suma y muestra el resultado
```
    Proceso Suma
        // Parte 1: Declarar las variables y su tipo de dato 
        Definir a, b, c como Reales;
