# Tesis-IoT-Maria.
Este sistema es una solución tecnológica basada en el Internet de las Cosas (IoT) diseñada para la captura, normalización y estructuración de variables climáticas en tiempo real, específicamente enfocada en las condiciones de regiones tropicales.

En términos sencillos, el funcionamiento del sistema se divide en tres etapas principales:
Recolección: Utiliza sensores (simulados en Proteus y programados con Arduino) para medir variables críticas como la temperatura, la humedad y las precipitaciones.

Procesamiento y Normalización: Los datos captados son enviados a un middleware (Node-RED), donde se organizan y estructuran bajo el formato JSON. Este paso es fundamental para asegurar que la información sea consistente y libre de errores antes de ser almacenada.

Persistencia: Finalmente, los datos ya normalizados se guardan en una base de datos relacional (PostgreSQL 16), permitiendo que la información esté disponible y lista para ser consultada o analizada posteriormente.
Ojo y no menos importante , la base de datos se va llenando a medida que proteus envia los datos, con eso quiero decir q una sola tabla es la que se llena con los datos enviados.
