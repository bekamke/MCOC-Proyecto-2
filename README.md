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
Con 1 particula se demoro  segundos y quedo el siguiente gráfico:



Con 2 particulas se demoro  segundos y quedo el siguiente gráfico:


Con 3 particulas se demoro segundos y quedo el siguiente gráfico:



Con 4 particulas se demoro  segundos y quedo el siguiente grafico:

Con 5 particulas se demoro 36,367 segundos y quedo el siguiente gráfico:
![imagen proyecto 2 (5 particulas)](https://user-images.githubusercontent.com/53590243/66686795-fac3f680-ec56-11e9-9285-7e692f11deda.png)


Con 6 particulas se demoro  segundos y quedo el siguiente gráfico:


Con 7 particulas se demoro  segundos y quedo el siguiente gráfico:


Con 8 particulas se demoro  segundos y quedo el siguiente gráfico:

Con 9 particulas se demoro  segundos y quedo el siguiente gráfico:

Con 10 particulas se demoro 50,04 segundos y quedo el siguiente gráfico:
![imagen proyecto 2 (10 particulas)](https://user-images.githubusercontent.com/53590243/66686819-09121280-ec57-11e9-8e69-c6dd634b14e1.png)

Con 15 particulas se demoro 206,161 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (15 particulas)](https://user-images.githubusercontent.com/53590243/66687420-f6004200-ec58-11e9-8a94-4f25e1ce0bd7.png)

Con 20 particulas se demoro 403,847 segundos y quedo el siguiente gráfico:
![Imagen proyecto 2 (20 particulas)](https://user-images.githubusercontent.com/53590243/66687210-475c0180-ec58-11e9-94b6-fb4d1bd4972a.png)

# Datos Pc:

Marca: HP

Procesador: Intel(R) Celeron(R) CPU N3050 @ 1.60GHz 1.60Ghz

Memoria instalada (RAM): 4.00 GB (3.86 GB utilizable)

Tipo de sistema: Sistema operativo de 64 bits, procesador x64

Lápiz y entrada táctil: La entrada táctil o manuscrita no está disponible para está pantalla

