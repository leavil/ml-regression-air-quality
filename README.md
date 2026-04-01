# Proyecto: Calidad del aire - Regresión lineal y árboles de decisión

Este proyecto es la actividad 1 de la asignatura de Técnicas de Aprendizaje Automático del Máster Universitario en Inteligencia Artificial.

## Contenido del repositorio

- `rlm_td_quality_air.ipynb`: Notebook completo con EDA, limpieza de datos, regresión lineal simple, regresión lineal múltiple y árboles de decisión.
- `data/AirQualityUCI.csv`: dataset original de UCI Air Quality.
- `.gitignore`: reglas de archivos a ignorar.

## Objetivos

1. Análisis descriptivo del dataset (EDA).
2. Tratamiento de datos faltantes y outliers.
3. Modelado de regresión:
   - Regresión lineal simple (una variable).
   - Regresión lineal múltiple (todas las variables).
   - DecisionTreeRegressor (hiperparámetros configurados).
4. Evaluación con métricas: R², MAE, RMSE, RMSLE, análisis de residuos.
5. Comparativa de rendimientos.

## Cómo ejecutar

1. Clona el repositorio:

```bash
git clone <tu-url-git> proyecto-calidad-aire
cd proyecto-calidad-aire
```

2. Instala dependencias (rechazado entorno local):

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

3. Abre el notebook:

- Con VS Code (Jupyter) o Jupyter Lab:

```bash
code rlm_td_quality_air.ipynb
```

4. Ejecuta las celdas en orden.

## Dependencias

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Autor
- Arnau González Almirall
- Máster Universitario en Inteligencia Artificial
# ml-regression-air-quality
