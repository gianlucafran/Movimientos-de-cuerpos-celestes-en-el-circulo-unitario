# Movimientos-de-cuerpos-celestes-en-el-circulo-unitario
Simulación del problema de los N cuerpos en el círculo unitario mediante ecuaciones diferenciales y métodos numéricos en Python. Modela interacciones gravitatorias, resuelve con RK4 y Verlet, y visualiza trayectorias dentro del círculo unitario.
# 🪐 Simulación de Mecánica Celeste y Sistema Solar

Este proyecto implementa simulaciones numéricas de mecánica orbital utilizando Python. El script modela la dinámica de cuerpos celestes, enfocándose en el Sistema Solar, y ofrece herramientas para visualizar órbitas, animaciones en 3D y campos gravitacionales.

## 📝 Descripción

El notebook (`movimiento_celeste.ipynb`) aborda la simulación de sistemas gravitatorios mediante la integración de ecuaciones diferenciales ordinarias (EDOs). El proyecto incluye:

* **Generación de Datos:** Creación de un dataset con condiciones iniciales (posición, velocidad y masa) para el Sol y los 8 planetas principales.
* **Problema de 2 Cuerpos:** Implementación del método de Runge-Kutta de orden 4 (RK4) para resolver órbitas simples en geometría circular ($S^1$).
* **Simulación de N-Cuerpos:** Integración numérica (posiblemente Verlet o RK4) para simular la interacción gravitatoria completa del Sistema Solar en 3D.
* **Visualización Avanzada:** Gráficos estáticos 2D/3D, animaciones interactivas de las trayectorias y representación del campo vectorial gravitacional.

## 🚀 Características

* **Carga Automática de Datos:** Genera y lee un archivo CSV (`solar_system_3d.csv`) con parámetros astronómicos reales (Masas en $M_{sun}$, Distancias en $AU$, Velocidades en $AU/yr$).
* **Métodos Numéricos:** Utiliza integradores robustos para asegurar la conservación de la energía y estabilidad orbital a lo largo del tiempo.
* **Animación 3D:** Genera una visualización animada que muestra el movimiento planetario alrededor del Sol.
* **Campo Gravitacional:** Calcula y visualiza el campo vectorial de fuerzas generado por los cuerpos masivos en una grilla tridimensional.

## 📋 Requisitos

Para ejecutar este notebook, necesitas tener instalado **Python 3.x** y las siguientes librerías científicas:

```bash
pip install pandas numpy matplotlib
