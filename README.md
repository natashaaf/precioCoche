# 🚗 Predicción de Precio de Coches - Regresión Lineal

Práctica de Machine Learning para predecir el precio de coches utilizando un modelo de **Regresión Lineal**.

## 📋 Descripción

Este proyecto implementa un flujo completo de regresión lineal para predecir el precio de vehículos basándose en sus características técnicas como fabricante, tipo de combustible, dimensiones, potencia, etc.

## 📁 Estructura del proyecto

```
precio-coches/
├── README.md
├── requirements.txt
├── regresion.ipynb          # Notebook para el alumnado (ejercicios)
├── regresion_SOL.ipynb      # Notebook con la solución
├── data/
│   └── Precio_coches.xlsx   # Dataset de coches
└── models/                  # Carpeta para guardar modelos entrenados
```

## 📊 Dataset

El dataset `Precio_coches.xlsx` contiene información de vehículos con las siguientes variables:

| Variable | Descripción |
|----------|-------------|
| Fabricante | Marca del vehículo |
| Combustible | Tipo de combustible (gas/diesel) |
| Longitud | Longitud del vehículo |
| Ancho | Ancho del vehículo |
| Altura | Altura del vehículo |
| Numero_cilindros | Número de cilindros del motor |
| Potencia | Potencia del motor |
| RPM_pico | RPM máximas |
| **Precio** | Variable objetivo a predecir |

## 🛠️ Instalación

1. Clona el repositorio o descarga los archivos

2. Crea un entorno virtual (opcional pero recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # En macOS/Linux
   ```

3. Instala las dependencias:
   ```bash
   pip install pandas numpy scikit-learn openpyxl
   ```

## 🚀 Uso

1. Abre el notebook `regresion.ipynb` en Jupyter Notebook o JupyterLab
2. Sigue las instrucciones y completa los ejercicios
3. Consulta `regresion_SOL.ipynb` solo si necesitas verificar tus respuestas

## 📝 Contenido de la práctica

1. Importar librerías necesarias
2. Cargar datos desde archivo Excel
3. Convertir variables categóricas (one-hot encoding)
4. Crear arrays de entrada (X) y salida (y)
5. Dividir datos en Training y Test (80/20)
6. Construir modelo de Regresión Lineal
7. Entrenar el modelo
8. Validación cruzada (Cross-validation)
9. Realizar predicciones
10. Evaluar el modelo (R², RMSE)

## 📦 Dependencias

- pandas
- numpy
- scikit-learn
- openpyxl (para leer archivos Excel)

