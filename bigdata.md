## BIG DATA
En terminos generales, ¿cuando decimos que manejamos grandes volumenes de datos y cuando no?
# Manejo de Grandes Volúmenes de Datos vs. No Grandes Volúmenes

Se considera que manejamos **grandes volúmenes de datos** (Big Data) cuando se cumplen características asociadas a los **"3 V's"** (y más), propuestos por Gartner:

## 📊 **Grandes Volúmenes de Datos (Big Data)**
1. **Volumen**:  
   - Datos que superan la capacidad de procesamiento o almacenamiento de herramientas tradicionales (ej: terabytes, petabytes, exabytes).  
   - Ejemplos: Registros de redes sociales, datos de sensores IoT, transacciones globales.  

2. **Velocidad**:  
   - Datos generados/actualizados en tiempo real o casi real.  
   - Ejemplos: Flujos de redes sociales, telemetría de vehículos autónomos, transacciones financieras.  

3. **Variedad**:  
   - Datos estructurados, semiestructurados y no estructurados (ej: texto, imágenes, videos, logs).  
   - Ejemplos: Correos electrónicos, registros médicos, datos satelitales.  

4. **Otros factores**:  
   - **Veracidad**: Calidad y confiabilidad de los datos.  
   - **Valor**: Necesidad de técnicas avanzadas (machine learning, IA) para extraer insights.  

**Herramientas comunes**: Hadoop, Spark, bases de datos NoSQL (MongoDB, Cassandra), cloud computing (AWS, Google Cloud).

---

## 📥 **No Grandes Volúmenes de Datos**
Se habla de volúmenes "pequeños" o tradicionales cuando:  
1. **Volumen manejable**:  
   - Datos que caben en una sola máquina o servidor (ej: gigabytes o menos).  
   - Ejemplos: Hojas de cálculo de ventas mensuales, registros de clientes de una PYME.  

2. **Velocidad baja**:  
   - Datos estáticos o actualizados esporádicamente.  
   - Ejemplos: Informes trimestrales, bases de datos históricas.  

3. **Estructura definida**:  
   - Datos tabulares (filas y columnas) compatibles con SQL.  
   - Ejemplos: Tablas de Excel, bases de datos relacionales (MySQL, PostgreSQL).  

**Herramientas comunes**: Excel, SQL, herramientas de BI tradicionales (Tableau, Power BI).

---

### 📌 **Resumen Comparativo**
| Característica          | Grandes Volúmenes               | No Grandes Volúmenes          |
|-------------------------|----------------------------------|-------------------------------|
| **Volumen**             | TB, PB, EB                      | MB, GB                        |
| **Velocidad**           | Tiempo real/streaming           | Estático/batch                |
| **Variedad**            | Multi-formatos (texto, imágenes)| Estructurados (tablas)        |
| **Infraestructura**     | Distribuida (clústeres, cloud)  | Servidores locales            |
| **Procesamiento**       | Herramientas especializadas     | Herramientas tradicionales    |

**Nota**: La línea entre ambos es difusa y depende del contexto (ej: 1 TB puede ser "grande" para una startup pero no para una empresa tecnológica).
Repasar librerias en python
# Librerías en Python: Un Repaso

Las **librerías** (o bibliotecas) en Python son colecciones de **funciones, clases y módulos preescritos** que permiten resolver tareas específicas sin necesidad de programar desde cero. Facilitan el desarrollo al reutilizar código probado y optimizado por la comunidad.

---

## 🧩 **Características Clave**
1. **Reutilización de código**: Evitan reinventar la wheel para funcionalidades comunes.
2. **Modularidad**: Se instalan e importan según la necesidad del proyecto.
3. **Especialización**: Cada librería está diseñada para un propósito específico (ej: matemáticas, visualización, machine learning).
4. **Mantenidas por la comunidad**: Actualizadas constantemente (gracias a PyPI y contribuidores).

---

## 📚 **Tipos de Librerías**
### 1. **Librerías Estándar**
- Incluidas en la instalación base de Python.
- Ejemplos:  
  - `math`: Funciones matemáticas.  
  - `datetime`: Manejo de fechas y horas.  
  - `os`: Interacción con el sistema operativo.

### 2. **Librerías Externas**
- Instaladas via `pip` (Python Package Index).  
- Ejemplos populares:  
   - **Ciencia de Datos**:  
     - `NumPy`: Cálculos numéricos con arrays.  
     - `Pandas`: Manipulación de datos en tablas (DataFrames).  
     - `Matplotlib`/`Seaborn`: Visualización de datos.  
   - **Machine Learning**:  
     - `Scikit-learn`: Algoritmos de ML clásico.  
     - `TensorFlow`/`PyTorch`: Redes neuronales y deep learning.  
   - **Web**:  
     - `Django`/`Flask`: Frameworks para desarrollo web.  
     - `Requests`: Peticiones HTTP.  
   - **Científicas**:  
     - `SciPy`: Algoritmos científicos avanzados.  
     - `SymPy`: Matemáticas simbólicas.  

### 3. **Librerías para Automatización**
- `Selenium`: Automatización de navegadores web.  
- `OpenCV`: Procesamiento de imágenes.  
- `Automate`: Automatización de tareas del sistema.

---

## ⚙️ **Cómo Usarlas**
1. **Instalación**:  
   ```bash
   pip install nombre_libreria
investigar sobre PIP
# PIP: Gestor de Paquetes de Python

**PIP** (acrónimo recursivo de *"Pip Installs Packages"* o *"Preferred Installer Program"*) es el gestor de paquetes estándar para Python. Permite instalar, actualizar y administrar librerías y dependencias de terceros desde repositorios como **PyPI** (Python Package Index).

---

## 📦 **¿Qué es PIP?**
- Herramienta de línea de comandos incluida en Python 3.4+ (o instalable manualmente en versiones anteriores).  
- Accede a más de **400,000 paquetes públicos** en PyPI (https://pypi.org/).  
- Automatiza la resolución de dependencias entre librerías.

---

## 🛠️ **Funciones Clave**
1. **Instalar paquetes**:  
   ```bash
   pip install nombre_paquete
