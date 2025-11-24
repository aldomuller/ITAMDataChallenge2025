# ITAMDataChallenge2025
Econometric analysis of Airbnb listings in CDMX to identify the top three neighborhoods with the highest investment potential.

---

## 1. Resumen del repositorio

Este repositorio contiene todo el material utilizado en el Data Challenge, cuyo objetivo es identificar las tres colonias de la Ciudad de México con mayor potencial de rendimiento para invertir en propiedades destinadas a Airbnb.  

Aquí se incluyen:

- **Bases de datos** descargadas de Inside Airbnb (datos crudos y datos limpios).  
- **Scripts de código** utilizados para limpieza, análisis estadístico y estimación del modelo hedónico OLS semilogarítmico.  
- **Gráficas y tablas** generadas para el informe final.  
- **El documento final en PDF** (máximo 5 cuartillas), conforme a los lineamientos del Data Challenge.

La estructura del repositorio es:

DataChallenge-Airbnb-CDMX/
│
├── data/
│ └── clean/ # Datos limpios (airbnb_cdmx_clean.csv)
│
├── scripts/
│ ├── 01_cleaning.R # Limpieza y construcción de variables
│ ├── 02_analysis.R # Regresiones y tablas
│ └── 03_graphics.R # Gráficas y mapas
│
├── outputs/
│ ├── figures/ # Figuras generadas para el reporte
│ └── tables/ # Tablas exportadas
│
├── report/
│ └── DataChallenge_5pager.pdf # Documento final del reto
│
└── README.md # Este archivo

---

## 2. Descripción de carpetas

### **`data/`**
- `raw/`: bases originales descargadas de Inside Airbnb y bases externas.
- `clean/`: datos procesados y listos para análisis (por ejemplo `airbnb_cdmx_clean.csv`).

### **`scripts/`**
- `01_cleaning.R`: procesamiento, merges, creación de variables y limpieza general.  
- `02_analysis.R`: regresiones hedónicas OLS, tablas, descritivos.  
- `03_graphics.R`: mapas, distribuciones y gráficas finales para el informe.

### **`outputs/`**
- `figures/`: todas las gráficas incluidas en el PDF.  
- `tables/`: tablas exportadas si corresponde.

### **`report/`**
- `DataChallenge_5pager.pdf`: documento final del reto.

---

## 3. Contribución de cada integrante

**Aldo Muller Quintero**  
- Construcción de bases limpias  
- Procesamiento de datos externos y merges  
- Revisión técnica del OLS  

**Alexis Capdevielle Harrison**  
- Estimación de modelos econométricos  
- Elaboración de tablas y coefplots  
- Construcción del ranking de colonias  

**Liliana Vargas Lugo**  
- Redacción del informe final (5-pager)  
- Diseño de la estrategia econométrica (modelo hedónico)  
- Integración de gráficas y narrativa ejecutiva  

---

## 4. Descripción del uso de IA

El equipo utilizó herramientas de IA generativa para:

- **Redacción técnica**, especialmente para estructurar la explicación del modelo hedónico.  
- **Revisión de sintaxis LaTeX** y estructura del informe en PDF.  
- **Asistencia para estructura de carpetas y documentación** del repositorio.  
- **Navegación conceptual del paper de referencia** (*Merino & Muñoz-Rodríguez, 2024*).

Ningún análisis, regresión o código fue generado de forma automática:  
**todas las estimaciones, scripts y decisiones metodológicas fueron realizadas manualmente por el equipo.**

---

## 5. Referencias

Merino, Juan José, y Edwin Muñoz-Rodríguez (2024).  
*Professional Airbnb Hosts in Mexico City: A First Approximation*.  
Documento de Trabajo, Centro de Estudios Económicos, El Colegio de México.


---

