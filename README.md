# MCOC2020_P2_G9_Entrega5
  
  
# Informe Diseño 
# PUENTE MILLENIUM 

# Diseños preliminares.
Para la entrega 5 se realizaron dos tipos de diseños de puentes, uno inspirado en el puente Golden Gate y otro inspirado en el Millenium de Londres, los que se presentan a continuación.
  
Puente Golden 

![imagen](/Puente_Golden.png)

Peso : 1500 ton (Sin cumplir requerimientos de cargas)

Puente MILLENIUM

Peso : 400 ton (Sin cumplir requerimientos de cargas)

![imagen](/Puente_Millenium.png)

 * Para el diseño de los puentes se utilizaron funciones cuadraticas y lineales para poner nodos cada una distancia x.
 * Teniendo estos 2 modelos pre establecidos, decidimos continuar con el diseño del Puente estilo Millenium, debido a que tiene una cantidad menor de barras a utilizar y en      el caso del Puente estilo Golden Gate existian barras muy altas y que tenian que resistir cargas muy altas, complicando el diseño.


# Cambios en el diseño.

 Como se mencionó anteriormente el modelo a utilizar es el Puente estilo Millenium. El modelo inicial presentaba las siguientes deformaciones con la combinacion 1.2D + 1.6L.
 
 ![imagen](/Deformaciones.png)
 
  * Peso = 474 ton

Para lograr la optimización de las barras se fijo el valor de t=1mm y se analizó la estructura 500 veces, de las cuales se va cambiando el valor de R. Si R cumple se queda ese valor, pero va cambiando de nuevo segun el valor de FU. Si FU es menor a 1 se busca disminuir el valor de R, y si FU es mayor a 1 se aumenta el valor de R, haciendo que FU sea lo más cercano posible a 1. 
 
 ![imagen](/Deformaciones_Finales.png)
 
  * Peso =  1.353,6 ton  
