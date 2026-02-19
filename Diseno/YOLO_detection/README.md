Detección de Personas con YOLO

Para la detección de nadadores se empleará el modelo de detección de objetos YOLO (You Only Look Once), un algoritmo de visión por computadora que permite identificar objetos en imágenes en tiempo real.
YOLO permite detectar múltiples personas por frame, obtener coordenadas de cada nadador, procesar video en tiempo real y adaptarse mediante reentrenamiento con imágenes de piscina.

YOLO es extremadamente rápido porque no se ocupa de canalizaciones complejas. Puede procesar imágenes a 45 fotogramas por segundo (FPS). Además, YOLO alcanza más del doble de precisión media (mAP) que otros sistemas en tiempo real, lo que lo convierte en un gran candidato para el procesamiento en tiempo real. 

El plan, hasta ahora, es complementarlo con OpenCV y DeepSort, para la identificacion de personas asignando IDs. 

Enlaces de interés: https://opencv.org/, https://github.com/ultralytics/ultralytics, https://github.com/nwojke/deep_sort

Este, también, es un artículo explicativo sobre la detcción de objetos con YOLO que fue especialmente útil para nuestra investigación: https://www.datacamp.com/es/blog/yolo-object-detection-explained. 
