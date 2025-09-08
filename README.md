# Data Warehouse Labs - INTEP

Este repositorio contiene laboratorios prácticos para el aprendizaje de conceptos de Data Warehouse, ETL (Extract, Transform, Load) y análisis de datos utilizando Python y Jupyter Notebooks.

## 📚 Proyectos Incluidos

### 1. Ejercicios Básicos de Python 🐍
**Archivo:** `ejercicios_python_basicos.ipynb`

Introducción práctica a los conceptos fundamentales de Python:
- Variables y tipos de datos
- Listas y operaciones básicas
- Funciones simples
- Estructuras de control (if, for)
- Trabajo con diccionarios

**Objetivo:** Preparar a los estudiantes con las bases de programación antes de trabajar con análisis de datos.

### 2. ETL Básico - Pipeline de Datos de Estudiantes 📊
**Archivo:** `etl_basico.ipynb`

Primer pipeline ETL completo trabajando con datos reales de estudiantes universitarios.

**Fases del ETL:**
- **Extract:** Carga de datos desde archivos CSV (`datos_estudiantes.csv`, `notas_estudiantes.csv`)
- **Transform:** Limpieza, validación y combinación de datos
- **Load:** Generación de reportes y visualizaciones

**Datos utilizados:**
- Información básica de estudiantes (ID, nombre, edad, programa, semestre, ciudad)
- Calificaciones en diferentes materias (matemáticas, programación, inglés, física)

**Resultados generados en `resultados_etl_basico/`:**
- `estudiantes_completo.csv`: Datos combinados con métricas calculadas
- `estudiantes_destacados.csv`: Estudiantes con mejor rendimiento
- `reporte_por_ciudad.csv`: Análisis por ubicación
- `reporte_por_programa.csv`: Análisis por programa académico
- `analisis_visual.png`: Visualizaciones de los datos

### 3. ETL Avanzado - Análisis de Acciones de Tata Motors 📈
**Archivo:** `etl.ipynb`

Pipeline ETL avanzado para procesar datos históricos de acciones de Tata Motors (1995-2025).

**Características:**
- Descarga automática de datos desde Kaggle
- Procesamiento de 30 años de datos históricos
- Análisis técnico y financiero
- Generación de indicadores técnicos (medias móviles, volatilidad, etc.)
- Validación y calidad de datos

**Resultados generados en `etl_output/`:**
- `tata_motors_processed.csv`: Datos procesados con indicadores
- `tata_motors_processed.parquet`: Formato optimizado para big data
- `tata_motors_monthly_summary.csv`: Resumen mensual
- `tata_motors_yearly_summary.csv`: Resumen anual
- `by_year/`: Archivos separados por año (1995-2025)
- `etl_metadata.json`: Metadatos del proceso ETL
- `etl_validation_charts.png`: Gráficos de validación

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Computación numérica
- **Matplotlib** - Visualización de datos
- **Jupyter Notebook** - Entorno interactivo
- **Kaggle API** - Descarga de datasets

## 📁 Estructura del Repositorio

```
laboratorios/
├── datos_estudiantes.csv          # Datos básicos de estudiantes
├── notas_estudiantes.csv          # Calificaciones de estudiantes
├── ejercicios_python_basicos.ipynb # Ejercicios básicos de Python
├── etl_basico.ipynb              # Pipeline ETL básico
├── etl.ipynb                     # Pipeline ETL avanzado
├── .gitignore                    # Archivos ignorados por Git
├── resultados_etl_basico/        # Resultados del ETL básico
│   ├── estudiantes_completo.csv
│   ├── estudiantes_destacados.csv
│   ├── reporte_por_ciudad.csv
│   ├── reporte_por_programa.csv
│   └── analisis_visual.png
└── etl_output/                   # Resultados del ETL avanzado
    ├── tata_motors_processed.csv
    ├── tata_motors_processed.parquet
    ├── tata_motors_monthly_summary.csv
    ├── tata_motors_yearly_summary.csv
    ├── etl_metadata.json
    ├── etl_validation_charts.png
    └── by_year/                  # Datos por año
        ├── tata_motors_1995.csv
        ├── tata_motors_1996.csv
        └── ... (hasta 2025)
```

## 🚀 Cómo Ejecutar los Proyectos

### Prerrequisitos
1. Python 3.7+
2. Jupyter Notebook
3. Librerías: pandas, numpy, matplotlib, kagglehub

### Instalación de dependencias
```bash
pip install pandas numpy matplotlib jupyter kagglehub
```

### Ejecución
1. Clona este repositorio
2. Navega al directorio del proyecto
3. Ejecuta Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Abre los archivos `.ipynb` y ejecuta las celdas en orden

## 📊 Conjuntos de Datos

### Datos de Estudiantes
- **Fuente:** Datos simulados de estudiantes universitarios
- **Registros:** 10 estudiantes
- **Variables:** ID, nombre, edad, programa, semestre, ciudad, calificaciones

### Datos de Tata Motors
- **Fuente:** Kaggle (jatinkalra17/tata-motors-stock-details1995-2025)
- **Período:** 1995-2025
- **Registros:** 7,804 días de trading
- **Variables:** Precios (Open, High, Low, Close), volumen, indicadores técnicos

## 🎯 Objetivos de Aprendizaje

- Comprender los conceptos fundamentales de ETL
- Manipular datos con Pandas
- Crear pipelines de procesamiento de datos
- Generar visualizaciones y reportes
- Trabajar con diferentes formatos de datos (CSV, Parquet, JSON)
- Implementar análisis técnico en datos financieros

## 📝 Notas Importantes

- Los notebooks están diseñados para ejecutarse en orden
- Algunos procesos pueden requerir conexión a internet (descarga de datasets)
- Los resultados se generan automáticamente en las carpetas correspondientes
- Se recomienda revisar los metadatos generados para validar la calidad del proceso

## 🤝 Contribuciones

Este repositorio es parte del programa de formación en Data Warehouse de INTEP. Para sugerencias o mejoras, por favor contacta al equipo docente.

## 👨‍💻 Autor

**Cesar Castillo**  
[LinkedIn](https://www.linkedin.com/in/cesar-eduardo-castillo/)

---

**INTEP - Instituto de Educación Superior**  
*Laboratorios de Data Warehouse - 2025*</content>
<filePath>c:\Users\Owner\Documents\INTEP-LABS\laboratorios\README.md
