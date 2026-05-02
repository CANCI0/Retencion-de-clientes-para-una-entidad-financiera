# Retencion de clientes para una entidad financiera

Proyecto de clasificacion para la competicion de Kaggle de retencion de clientes de una entidad financiera.

## Resultado principal

- Modelo final: XGBoost con umbral 0.50
- Private recall en Kaggle: 0.58367
- Submission final: `submissions/submission_xgboost_th50.csv`

## Contenido del repositorio

- `proyecto_retencion_clientes.ipynb`: notebook principal con EDA, preprocesamiento, modelado y generacion de submissions.
- `submissions/`: predicciones generadas para distintos modelos y umbrales.
- `reports/memoria.pdf`: memoria final del proyecto.
- `reports/kaggle_screenshot.png`: captura del resultado en Kaggle.
- `data/README.md`: instrucciones para colocar los ficheros de datos que no se versionan.
- `requirements.txt`: dependencias principales del proyecto.

## Como reproducir el proyecto

1. Crea y activa un entorno virtual de Python.
2. Instala las dependencias:

```bash
pip install -r requirements.txt
```

3. Coloca los ficheros `train.csv` y `test.csv` dentro de la carpeta `data/`.
4. Abre `proyecto_retencion_clientes.ipynb` y ejecuta las celdas en orden.
5. Las submissions nuevas se guardaran automaticamente en `submissions/`.