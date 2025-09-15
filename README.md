# 🤖 Inteligencia Artificial y Machine Learning: Conceptos Básicos  
**🎓 Datos del Alumno**  
**Nombre:** Mariano Casal  
**Curso:** 6.° año  
**Materia:** Programación IV  
---

## 🧠 **Inteligencia Artificial (IA)**  

### 📚 Definición  
La **Inteligencia Artificial (IA)** es una rama de la informática que desarrolla sistemas capaces de realizar tareas que, en humanos, requieren inteligencia, como el aprendizaje, razonamiento o percepción.  

---

### 🗂️ Tipos de IA  
1. **🔍 IA Débil (Narrow AI)**  
   - **Función:** Realiza tareas específicas.  
   - **Ejemplos:**  
     - Asistentes virtuales: *Siri, Alexa*.  
     - Sistemas de recomendación: *Netflix, Spotify*.  

2. **🌐 IA General (AGI)**  
   - **Función:** Teóricamente iguala la inteligencia humana en múltiples áreas.  
   - **Estado actual:** No existe; es un objetivo en investigación.  

3. **🚀 Superinteligencia (ASI)**  
   - **Función:** Superaría ampliamente a la inteligencia humana.  
   - **Ejemplo hipotético:** Robots autónomos con conciencia propia.  

---

### 🛠️ Aplicaciones Prácticas de IA  
- 🏥 Diagnóstico médico asistido (*IBM Watson Health*).  
- 🚗 Vehículos autónomos (*Tesla Autopilot*).  
- 🌍 Traducción automática en tiempo real (*Google Translate*).  

---

## 📊 **Machine Learning (ML)**  

### 📚 Definición  
Subcampo de la IA que utiliza algoritmos para identificar patrones en datos y mejorar automáticamente su rendimiento sin intervención humana explícita.  

---

### 🗂️ Tipos de Machine Learning  
1. **🔖 Aprendizaje Supervisado**  
   - **Característica:** Datos etiquetados.  
   - **Ejemplos:**  
     - Predicción de precios de inmuebles.  
     - Clasificación de correos como *spam* o *no spam*.  

2. **🧩 Aprendizaje No Supervisado**  
   - **Característica:** Datos sin etiquetas.  
   - **Ejemplos:**  
     - Segmentación de clientes (*marketing*).  
     - Detección de fraudes en transacciones.  

3. **🎮 Aprendizaje por Refuerzo**  
   - **Característica:** Aprendizaje basado en recompensas.  
   - **Ejemplos:**  
     - Entrenamiento de agentes en juegos (*AlphaGo*).  
     - Optimización de rutas en robots autónomos.  

4. **🧠 Deep Learning**  
   - **Característica:** Redes neuronales profundas.  
   - **Ejemplos:**  
     - Reconocimiento facial (*Meta*).  
     - Generación de texto (*ChatGPT*).  

---

### 🛠️ Aplicaciones Prácticas de ML  
- 🎵 Recomendaciones personalizadas (*Spotify, YouTube*).  
- 💊 Predicción de enfermedades mediante historiales clínicos.  
- 🏭 Mantenimiento predictivo en industria 4.0.  

---
# Tkinter

**Tkinter** es la biblioteca estándar de Python para crear interfaces gráficas de usuario (GUI). Está basada en **Tcl/Tk** y permite desarrollar aplicaciones con elementos gráficos como ventanas, botones, etiquetas, cuadros de texto, menús, etc.

## Resumen:
- **Interfaz de Tcl/Tk**: Tkinter es un wrapper de la biblioteca gráfica Tcl/Tk.
- **Elementos gráficos**: Permite crear botones, etiquetas, menús, cuadros de texto, etc.
- **Multiplataforma**: Funciona en Windows, macOS y Linux.
- **Fácil de usar**: No requiere instalación adicional, ya que está incluida por defecto en Python.
- **Aplicaciones sencillas**: Ideal para proyectos con interfaces gráficas simples.
- **Estructura basada en objetos**: Utiliza un enfoque basado en objetos y eventos (ej. clic en botones).

## Ejemplo básico:

```python
import tkinter as tk

ventana = tk.Tk()
ventana.title("Mi primera app")
ventana.geometry("300x200")

etiqueta = tk.Label(ventana, text="¡Hola, mundo!")
etiqueta.pack()

ventana.mainloop()

> **📌 Nota:** Este documento fue creado por **Mariano Casal** para la materia **Programación IV** (6.° año).  
> **🔗 Recursos útiles:** [Coursera](https://www.coursera.org) | [Libros de IA](https://www.amazon.com)  
