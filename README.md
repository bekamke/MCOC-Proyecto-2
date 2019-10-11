# MCOC-Proyecto-2 (Benjamín Kamke) (Individual)

# INTRODUCCION:
En este proyecto se implementará y validará un modelo de simulación de transporte de
sedimentos en base a un método lagrangiano, es decir que sigue a cada partícula individualmente.
La validación se hará a nivel del comportamiento de una partícula y luego con el comportamiento
estadístico de cantidades crecientes de partículas. Además, se explorará cómo influyen las
decisiones de algoritmo de implementación, conocido como complejidad computacional, y
métodos de input-output (IO) en el rendimiento del programa.

# OBJETIVOS:
Diseñar un modelo que simule el transporte de partículas de sedimento en el fondo del agua.
Entender la influencia de la implementación de algoritmos computacionales, entre ellos
algoritmos de complejidad computacional y métodos (IO).
[Meta 3]: implementación del código para una partícula con perfil de velocidad

# RESULTADOS PARA UNA PARTÍCILA:

Para el estudio del comportamiento de una partícula transportada por un fluido se usaron los siguinetes datos y supuestos:
* La partícula transportada corresponde a una grano de arena
* La forma de la artícula es considerada como esférica 
* EL comportamiento se estudia mediante relaciones Euler-Lagrange

* Datos usados

    * diámetro de partícula = 1 mm
    * densidad de partícula = 155 kg/m^3
    * coeficiente Drag para partícula esférica = 0,47

El desplazamiento en x de la partícula según la velocidad con que se mueve se muestran el el siguiente gráfico, donde el eje "x" representa el desplazameinto y el eje "y" la velocidad en cierto instante 

![real p2](https://user-images.githubusercontent.com/53712876/65996866-a65a9300-e46e-11e9-945e-d2ca47f3125f.png)




# Con N particulas
# Discusion resultados
Con 1 partícula se demoro 0,720 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (1 particula)](https://user-images.githubusercontent.com/53590243/66688211-0239ce80-ec5c-11e9-9d84-ab314a6092a4.png)

Con 2 partículas se demoro 3,384 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (2 particulas)](https://user-images.githubusercontent.com/53590243/66688151-cdc61280-ec5b-11e9-80fd-5acf161fb165.png)

Con 3 partículas se demoro 5,584 segundos y quedo el siguiente gráfico:
![imagen proyecto 2 (3 particulas)](https://user-images.githubusercontent.com/53590243/66688105-95263900-ec5b-11e9-9b1a-3157bfa4f0d1.png)

Con 4 partículas se demoro 13,289 segundos y quedo el siguiente grafico:
![Imagen proyecto 2 (4 particulas)](https://user-images.githubusercontent.com/53590243/66687942-f26dba80-ec5a-11e9-9628-d23fe199064e.png)

Con 5 partículas se demoro 19,503 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (5 particulas)](https://user-images.githubusercontent.com/53590243/66688026-3cef3700-ec5b-11e9-9d66-6a0eb67eb08b.png)

Con 6 partículas se demoro 29,232 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (6 particulas)](https://user-images.githubusercontent.com/53590243/66687883-c4887600-ec5a-11e9-81ba-c67d17ff9934.png)

Con 7 partículas se demoro 29,996 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (7 particulas)](https://user-images.githubusercontent.com/53590243/66687835-812e0780-ec5a-11e9-88ec-3b6b8192de75.png)

Con 8 partículas se demoro 40,451 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (8 particulas)](https://user-images.githubusercontent.com/53590243/66687671-db7a9880-ec59-11e9-8750-ffc33ddbbf79.png)

Con 9 partículas se demoro 47,589 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (9 particulas)](https://user-images.githubusercontent.com/53590243/66687619-9ce4de00-ec59-11e9-85d2-3232983b1ead.png)

Con 10 partículas se demoro 50,04 segundos y quedo el siguiente gráfico:
![imagen proyecto 2 (10 particulas)](https://user-images.githubusercontent.com/53590243/66686819-09121280-ec57-11e9-8e69-c6dd634b14e1.png)

Con 15 partículas se demoro 206,161 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (15 particulas)](https://user-images.githubusercontent.com/53590243/66687420-f6004200-ec58-11e9-8a94-4f25e1ce0bd7.png)

Con 20 partículas se demoro 403,847 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (20 particulas)](https://user-images.githubusercontent.com/53590243/66687210-475c0180-ec58-11e9-94b6-fb4d1bd4972a.png)

Estos gráficos representan el movimiento de N partículas a lo largo de un río, se puede apreciar como estás partículas rebotan al fondo del río y siguen su transcurso o como tambien chocan entre ellas y cambian su movimiento pero siempre con la misma direccion en donde fluye el río. El tiempo máximo que se tomo para estas pruebas fue de 0,5 segundos.
# Datos Pc:

Marca: HP

Procesador: Intel(R) Celeron(R) CPU N3050 @ 1.60GHz 1.60Ghz

Memoria instalada (RAM): 4.00 GB (3.86 GB utilizable)

Tipo de sistema: Sistema operativo de 64 bits, procesador x64

Lápiz y entrada táctil: La entrada táctil o manuscrita no está disponible para está pantalla

El comportamiento de mi computador no es el mejor, ya que demora mucho en arrojar algún resultado. Puede ser por tema de que no tengo linux instalado o tengo mucha memoria utilizada. 
Para poder obtener un mejor resultado del tiempo se realizaron 3 iteraciones por cada experimento, donde se calculo un promedio y ese fue puesto en los resultados.
