# Ejercicio: Detectar si una imagen es un 5 o no

## Descripción
Construir un modelo de clasificación binaria utilizando el dataset load_digits de scikit-learn para determinar si una imagen corresponde al dígito 5 o a cualquier otro número.

El objetivo principal de la actividad es comprender el flujo completo de un problema de clasificación binaria y analizar distintas métricas de evaluación utilizadas en Machine Learning.

El desarrollo debe realizarse en un notebook de Jupyter documentando cada etapa del proceso.

## Objetivos
- Cargar y explorar el dataset load_digits
- Transformar el problema multiclase en clasificación binaria
- Entrenar un modelo de clasificación
- Generar predicciones
- Evaluar el modelo utilizando métricas de clasificación binaria
- Interpretar los resultados obtenidos

## Requisitos
- Python 3.14+
- ipython
- jupyter
- scikit-learn
- pandas
- matplotlib
- numpy

## Modelos a utilizar
- SGDClassifier (Fase 1)
- Random Forest (Fase 2 para comparar)

## Instalación y Ejecución

El proyecto está configurado para ejecutarse de manera asilada utilizando Docker. Sigue estos pasos:

1. **Construir e iniciar el contenedor**:
   ```bash
   docker compose up -d --build
   ```

2. **Acceder al notebook**:
   Acceder a la siguiente direccion desde el navegador:
   [http://localhost:8888/tree/notebook/notebook.ipynb?token=tarea5](http://localhost:8888/tree/notebook/notebook.ipynb?token=tarea5)

3. **Detener el contenedor**:
   Para detener el entorno una vez que termines de trabajar, ejecuta:
   ```bash
   docker compose down
   ```