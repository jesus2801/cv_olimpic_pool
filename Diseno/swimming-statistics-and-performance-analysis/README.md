Estamos investigando la posibilidad de implementar un módulo de análisis de rendimiento y generación de estadísticas dentro de nuestro proyecto final. La idea es que, además de monitorear la seguridad de los nadadores, podamos obtener datos objetivos sobre su desempeño en una piscina semiolímpica de 25 metros.

Nuestro enfoque consiste en utilizar la información espacial y temporal que obtenemos del seguimiento de los nadadores en video para calcular métricas como distancia recorrida, velocidad promedio, número de vueltas y tiempo por largo. Para esto necesitamos primero calibrar la escena, convirtiendo las posiciones en píxeles a metros reales, tomando como referencia la longitud a medir de la piscina.

Con estos datos, podemos aplicar fórmulas físicas simples para obtener la velocidad promedio:

v = d / t

y también estimar la velocidad instantánea y detectar cambios de dirección para contabilizar vueltas. Esto nos permitirá construir estadísticas individuales de cada nadador y generar reportes de rendimiento comparativos entre sesiones o entre diferentes nadadores.

Para implementar esta parte del sistema, planeamos usar bibliotecas de Python como NumPy para cálculos numéricos, Pandas para organizar y manipular los datos, y Matplotlib para generar gráficas de evolución del rendimiento.

Algunos enlaces de interés son https://numpy.org/, https://pandas.pydata.org/, y https://matplotlib.org/

Creemos que este módulo puede complementar el proyecto final no solo en la prevención de riesgos, sino también en la evaluación del rendimiento deportivo, proporcionando información objetiva y útil para entrenadores y para la planificación de entrenamientos.
