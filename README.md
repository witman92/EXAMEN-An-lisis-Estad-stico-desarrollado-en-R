# EXAMEN-An-lisis-Estad-stico-desarrollado-en-R

EXAMEN
An´alisis Estad´ıstico (AES1018)
Fecha: 26-06-2025
Deber´a entregar un informe en formato pdf y enviarlo a jcontreras@udla.cl, a m´as tardar
a las 23:59 hrs del d´ıa 01-07-2025.
1. Los datos Estudiantes.xlsx fueron recogidos aplicando una encuesta a una muestra de estudiantes
universitarios, y corresponde a un dataframe con 400 observaciones y 18 variables, las cuales se describen en el mismo archivo.
a) [0.5 pts] Realize un an´alisis de correlaci´on m´ultiple entre las variables cuantitativas y describa los
resultados.
b) [1 pto] Para la variable Ingreso (en millones de pesos), y suponiendo que esta variable tiene una
distribuci´on normal, realice tests de diferencias de medias (con un 95% de nivel de confianza) para
esta variable clasificada seg´un Estrato y describa los resultados.
c) [0.5 pts] Para la variable Colegio, realice el test de proporci´on considerando las clases Privado
y Publico.
2. De los datos Estudiantes.xlsx de la pregunta 1:
a) [1 pto] Realice un modelo regresi´on lineal donde la variable respuesta es Puntaje. Considere como
conjunto de covariables a las variables m´as adecuadas seg´un los m´etodos visto en clases.
b) [1 pto] Del modelo obtenido en a), realice un an´alisis de diagn´ostico de los residuos y outliers.
3. Considere el set de datos Swordfish.txt, correspondiente a la especie pez espada del oce´ano Pac´ıfico
Sur. Las variables son EDAD (en a˜nos), LONGITUD (en cm), PT (peso total en kg), y SEXO (g´enero, 1:
macho, 2: hembra) de cada individuo/observaci´on.
a) [0.5 ptos] Los bi´ologos marinos proponen modelar la relaci´on edad/longitud mediante la funci´on
de von Bertalanffy:
L(t) = L∞(1 − e
−k(t−t0)
),
donde L(t) es talla en el tiempo t de la especie y t es la edad de la especie. Los par´ametros son L∞
(talla m´axima permisible en la especie), k es el par´ametro de curvatura (1/t), y t0 es el par´ametro
1
de condici´on inicial. Es posible obtener un modelo de regresi´on lineal a partir de la funci´on de
von Bertalanffy? Entre los argumentos matem´aticos, como los vistos en clases.
b) [1.5 ptos] Los bi´ologos marinos proponen modelar la relaci´on longitud/peso mediante la funci´on
vista en clases:
yi = w(xi) = axb
i
εi
,
donde w(xi) es el peso del individuo i con longitud xi
, εi ∼i.i.d. N(0, σ2
), y los par´ametros son:
a es el peso te´orico en x = 0 y b es la taza de crecimiento del peso. Linealice la ecuaci´on anterior
para realizar un ajuste de regresi´on lineal por cada g´enero, provea los resultados junto a un an´alisis
de diagn´ostico de los residuos y outliers.
