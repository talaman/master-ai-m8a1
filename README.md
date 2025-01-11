# master-m8a1

1. Caso de uso: Detección de cáncer de piel
En este caso de uso, se utilizarán datos para respaldar un diagnóstico clínico de cáncer de piel. 
La idea es diseñar un sistema que pueda analizar imágenes de la piel y proporcionar un diagnóstico basado en datos.

2. Tipos de datos necesarios
Para ayudar al médico a dar un diagnóstico, se necesitarían los siguientes tipos de datos:
- Imágenes de alta resolución de la piel (estructurado)
- Historial clínico del paciente (estructurado y no estructurado)
- Datos de sensores que puedan medir parámetros relevantes de la piel (estructurado)

3. Procesamiento de datos
El dato debe ser capturado mediante dispositivos de imagen y sensores. 
Las imágenes se preprocesan para mejorar la calidad y se etiquetan con información relevante del historial clínico. 
Luego, los datos se almacenan en una base de datos estructurada y se preparan para ser analizados por el sistema de diagnóstico.

4. Tipo de sistema
El sistema utilizado para dar un diagnóstico sería una IA entrenada con redes neuronales convolucionales (CNN) para el análisis de imágenes. 
El modelo se entrenaría con un conjunto de datos grande y diverso de imágenes de piel etiquetadas con diagnósticos confirmados.

5. Interpretación de salidas del modelo
Las salidas del modelo se interpretarían utilizando técnicas de visualización como mapas de calor para mostrar las áreas de la imagen que contribuyeron al diagnóstico. 
Los resultados no son 100% explicables, por lo que se necesitarían técnicas post modelado como LIME o SHAP para mejorar la interpretabilidad.

6. Riesgos y viabilidad
Los riesgos incluyen la posibilidad de diagnósticos incorrectos debido a datos insuficientes o sesgados, y la necesidad de validación clínica rigurosa. 
La viabilidad depende de la calidad y cantidad de datos disponibles, así como de la aceptación del sistema por parte de los profesionales de la salud.

7. Casos reales
Existen casos reales de implementaciones similares, como el uso de la IA en la aplicación DermAssist de Google, que ayuda a identificar afecciones de la piel mediante el análisis de imágenes.