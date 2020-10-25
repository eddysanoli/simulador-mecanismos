# Simulador de Mecanismos de 4 Barras

Simulador que utiliza las ecuaciones de síntesis de posición analítica de mecanismos de 4 barras para generar una animación del mecanismo en funcionamiento. En conjunto con la animación, el programa también despliega las gráficas de la evolución de los diferentes ángulos del mecanismo durante su movimiento.

## Uso

Para comenzar a utilizar el script, el usuario debe abrir `Sintesis_Posicion_Mecanismos.mlx` en Matlab. Ahí, el usuario baja a la sección de *Mecanismo de 4 barras* y únicamente debe de cambiar cual es el largo de cada eslabón o barra en el mecanismo, dado por los parámetros: `a`, `b`, `c` y `d`. También se puede elegir el `Global_Offset` o el número de grados que se encontrará inclinado el mecanismo completo. Una vez se alteran estos parámetros, se puede bajar a la sección de graficación y elegir si se desea la posición abierta o cerrada del mismo. Con todo esto ya se puede dar click al botón `Run Section`. Esto despliegará la animación deseada y su evolución a lo largo del tiempo. En caso el eslabón manivela (`a`) del mecanismo no pueda completar una revolución completa por restricciones geométricas (mecanismo no grashof) la animación mostrará únicamente la parte del movimiento del mecanismo en la que el mismo no se "atora". Las velocidades de los diferentes eslabones se muestran durante el desarrollo de la animación y también se incluyen gráficas de su desarrollo a lo largo del movimiento.

<p align="center">
   <img src="./Media/Animacion1.gif" width="49%" />
   <img src="./Media/Animacion2.gif" width="49%" /> 
</p>

## Opciones Adicionales

Luego de presionar `Run Section` también se generarán algunas figuras detallando la evolución de los ángulos y diferentes cantidades relacionadas al mecanismo. Además, si el usuario lo desea, se pueden simular otras variaciones del mecanismo de 4 barras, como un mecanismo manivela corredera, el cual cuenta con las mismas opciones que antes, con la excepción que no se puede establecer el largo de su eslabón `d` ya que este cambia libremente durante el movimiento.
