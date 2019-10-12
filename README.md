# MCOC-Proyecto-2

## OBJETIVO
Analizar el transporte de sedimentos en el lecho de un fluido, enfatizando el desempeño del código en diferentes computadores.

# Desarrollo
Mediante el estudio del comportamiento de una partícula arrastrada por un fluido realizado en la entrega tres, se implementrá el estudio indivudual para el transporte de un número creciente de partículas. para esto se toma el perfil de velocidades creado anteriormente bsado en un método Lagrangiano.

# Parámetros usados: (Unidades base SI (m, kg, s))
*gravedad = 9.81 m/s^2         
*diámetro = 0.15e-3
*densidad del agua = 1000 kg/m^3            
*densidad de partícula (arena) =  2650 kg/m^3 

*paso del tiempo = 0.001s   
*timepo evaluado = 0.5s   
*tiempo inicial = 0s     

*coeficiente de arrastre = 0.47                  
*coeficiente de lift = 0.2
*masa adicional = 0.5

# Características del computador:
* MARCA: HP
* EDICIÓN: Windows 10
* NOMBRE DEL DISPOSITIVO: DESKTOP-OSR0SSJ
* PROCESADOR: INtel(R) Core(TM) i5-7200U CPU @
* RAM: 8,00 GB
* TIPO DE SISTEMA: Sistema Operativo de 64 bits, procesador x64

# Resultados obtenidos 
Los siguientes gráficos muestran el movimineot bi-dimensional de las partículas de arena arrastradas por el lecho de un río, donde el eje "x" representa la longitud del río, mientras que el eje "y" la profundidad de este. El estudio modela cómo se distribuyen durente 0,5 segundos.

* Caso 1: Movimiento de dos partículas 
; Timepo en porcesar = 5 seg

![2 particulas](https://user-images.githubusercontent.com/53712876/66693641-468b9580-ec81-11e9-8fe8-94d5d197fe6f.png)

* Caso 2: Movimiento de 5 partículas
; Tiempo en procesar: 21,58 segundos

![5 particulas](https://user-images.githubusercontent.com/53712876/66693642-48edef80-ec81-11e9-9a13-c83852925f9a.png)

* Caso 3: Movimiento de 10 partículas 
; Tiempo en procesar: 11,26 segundos

![10 particulas ](https://user-images.githubusercontent.com/53712876/66693644-4ab7b300-ec81-11e9-80e1-119ac2ee0a9f.png)

* Caso 4: Movimiento de 20 partículas
; Tiempo en procesar: 468 segundos 
![20 particulas](https://user-images.githubusercontent.com/53712876/66693647-4d1a0d00-ec81-11e9-888a-e3bdaf1ae440.png)

# Discusión
De los gráficos anteriores es posible observar que el movimiento de partículas de sedimentos no depende únicamente de su tamaño ni de la fuerza con que el fluido de un río avanza, sinó que se ve directamente afectada con la cantidad de partículas que circulan a la vez, ya qu,e estas tienden a chocar entre ellas y a modificar sus trayectorias. Por lo que, es posible concluir que su posición se ve afectada por varias fuerzas como la de arrastre, lift, boyante (la cual determina si el cuerpo flota o se hunde), su propio peso (dado por la masa y gravedad) y por la interacción entre ellas, fuerza descrite en el código como K_penal, donde entre más partículas hayan presentes, más influencia tendrá.

