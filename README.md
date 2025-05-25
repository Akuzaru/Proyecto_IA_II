# Proyecto_IA_II

### Titulo:
Detección de Medicamentos con Mayor Riesgo de Desabastecimiento.

### Autores:
- Edgar Camilo Ramírez Rueda - 2220101
- Oscar Silva - 2220087

### Objetivo:
Desarrollar un modelo de inteligencia artificial que analice datos de consumo, precios y logística para predecir el riesgo de desabastecimiento de medicamentos no vitales en Colombia, permitiendo a farmacias, distribuidores y autoridades de salud tomar decisiones preventivas y optimizar su disponibilidad.

### Dataset:

Tomado del repositorio público Datos Abiertos de Colombia: Ministerio de Salud y Protección Social de Colombia. (n.d.). Medicamentos vitales no disponibles. Link: https://www.datos.gov.co/Salud-y-Protecci-n-Social/MEDICAMENTOS-VITALES-NO-DISPONIBLES/sdmr-tfmf/about_data

Dentro del dataset se puede observar una lista de diagnósticos para diferentes enfermedades con fecha y código, junto a indicación del nombre del medicamento necesario para el tratamiento junto con su concentración, forma, medida, principio activo, y cantidad solicitada por cada entidad de salud.

De modo que los datos o variables que nos interesan para nuestro análisis son las siguientes:
- Variable de marca de tiempo: FECHA_DE_AUTORIZACIÓN.
- Variables numéricas: CANTIDAD_SOLICITADA.
- Variables de texto: TIPO_DE_SOLICITUD, SOLICITANTE/IMPORTADOR, IUM, PRINCIPIO_ACTIVO1, CONCENTRACIÓN_DELMEDICAMENTO1, UNIDAD_MEDIDA1, PRINCIPIO_ACTIVO2, CONCENTRACIÓN_DEL_MEDICAMENTO2, UNIDAD_MEDIDA2, FORMA_FARMACÉUTICA, NOMBRE_COMERCIAL_, PRESENTACIÓN_COMERCIAL, DIAGNOSTICO_CIE-1NO REPORTA, CÓDIGO_DIAGNOSTICO_CIE-10.

### Modelos:
- Clasificación: Decision Tree Classifier, Random Forest Classifier, Support Vector Classifier.
- Regresión: Decision Tree Regressor, Random Forest Regressor, Support Vector Regressor, Deep Neural Network.
- No Supervisados: t-distributed Stochastic Neighbor Embedding (t-SNE), Principal Component Analysis (PCA).

### Enlaces:
- Código en Notebook de Google Colaboratory: https://colab.research.google.com/drive/16n7Sq9JdFpowQAvALTw9VdhLzkGJGQTd?usp=sharing.
- Video:
- Repositorio: https://github.com/Akuzaru/Proyecto_IA_II
