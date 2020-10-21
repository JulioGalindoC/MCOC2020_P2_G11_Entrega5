# MCOC2020_P2_G11_Entrega5

Teniendo en cuenta la restricción de que ningún tramo del tablero exceda los 6 [m] de separación, para el diseño de este, lo primero que se hizo fue dividir la luz en 40 tramos.
Al ser la luz de 215[m] la distancia entre nodos del tablero en el eje x resulto igual a 5,375 [m] (215/40). El ancho del tablero fue dado en el enunciado, es por esto que la distancia entre nodos del tablero en el eje y es igual a 2 [m].

A continuacion se busco una geometría lo más optima posible. La primera solución planteada fue la utilización de un arco en forma de catenaria invertida que pase por tres puntos, el punto inicial fue el punto 7 y el punto final el punto 28 (como se especifica en el enunciado), el punto medio del arco se planteo en z = 115[m]. Es importante mencionar que al hacer los rediseños, se cambiaron tanto las propiedades de cada barra como la flecha del arco. El diseño preliminar se puede apreciar en la siguente imagen:

INSERTAR IMAGEN DISEÑO PUENTE.

Las propiedades para todas las barras en primera instancia fueron las siguentes: 

- A = (1.1*cm)**2
- r = sqrt(A/3.141593)
- props = [r, r, 200*GPa, 7600*kg/m**3, 420*MPa]
 
