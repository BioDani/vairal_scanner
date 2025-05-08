# vairal_scanner

mi_repositorio_tesis/
├── .github/
│   └── workflows/
│       └── main.yml         # Flujo de trabajo de CI/CD (opcional pero recomendado)
├── data/
│   ├── raw/               # Datos sin procesar, tal como se obtuvieron
│   ├── interim/           # Datos preprocesados pero no transformados para el modelo
│   └── processed/         # Datos listos para ser utilizados por los modelos
├── docs/
│   ├── informe_avance_1.md  # Documentación del proyecto, informes, etc.
│   └── ...
├── notebooks/
│   ├── exploracion_datos.ipynb
│   ├── preprocesamiento.ipynb
│   ├── entrenamiento_modelo_pruebas.ipynb
│   └── ...
├── src/
│   ├── __init__.py        # Marca el directorio como un paquete de Python
│   ├── data/
│   │   ├── __init__.py
│   │   └── make_dataset.py  # Funciones para descargar y procesar datos
│   ├── features/
│   │   ├── __init__.py
│   │   └── build_features.py # Funciones para crear características para el modelo
│   ├── models/
│   │   ├── __init__.py
│   │   ├── model.py         # Definición de la arquitectura del modelo
│   │   └── train_model.py   # Script para entrenar el modelo
│   ├── visualization/
│   │   ├── __init__.py
│   │   └── visualize.py     # Funciones para generar visualizaciones
│   └── utils.py           # Funciones utilitarias generales
├── tests/
│   ├── __init__.py
│   ├── test_data.py
│   ├── test_features.py
│   └── test_models.py
├── .gitignore             # Especifica archivos que Git debe ignorar
├── LICENSE                # Licencia del proyecto (ej., MIT, Apache 2.0)
├── README.md              # Documentación principal del proyecto
├── requirements.txt       # Lista de dependencias del proyecto
└── setup.py               # Para empaquetar el proyecto (opcional pero recomendado)