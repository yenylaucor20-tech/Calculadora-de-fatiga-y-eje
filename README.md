# Calculadora-de-fatiga-y-eje
# Calculadora de Fatiga de Ejes Mecánicos

Aplicación desarrollada en Python con interfaz gráfica basada en **Tkinter** para el análisis de ejes mecánicos sometidos a flexión y torsión combinadas.
El programa permite calcular esfuerzos, factores de concentración y factores de seguridad mediante diferentes criterios de falla por fatiga.

# Descripción

Este software facilita el análisis de diseño de ejes mecánicos considerando cargas alternantes y medias. A partir de parámetros geométricos, propiedades del material y condiciones de carga, la aplicación calcula automáticamente:

* Factores de concentración de esfuerzos
* Sensibilidad a la muesca
* Factores de fatiga
* Esfuerzos equivalentes
* Factores de seguridad mediante diferentes criterios de diseño

La herramienta está orientada a estudiantes de ingeniería mecánica, mecatrónica o diseño de elementos mecánicos, así como a cualquier persona interesada en el análisis de fatiga de ejes.

# Características

* Interfaz gráfica sencilla usando Tkinter

* Conversión automática de unidades

* Cálculo automático o manual de:

  * Factores de concentración de esfuerzos (Kt, Kts)
  * Sensibilidad a la muesca (q, qs)
  * Factores de fatiga (Kf, Kfs)

* Evaluación de esfuerzos normales y cortantes

* Cálculo de esfuerzos equivalentes de Von Mises

* Determinación del factor de seguridad mediante:

  * Criterio de Goodman
  * Criterio de Soderberg
  * Criterio de Gerber
  * Criterio ASME elíptico

* Soporte para diferentes unidades:

  * Longitud: m, cm, in
  * Momento/Torque: N·m, lbf·in
  * Esfuerzo: Pa, MPa, psi, kpsi

# Parámetros de entrada

El programa requiere los siguientes datos:

# Geometría del eje

* Diámetro mayor (D)
* Diámetro menor (d)
* Radio de filete (r)

# Cargas aplicadas

* Momento alternante (Ma)
* Momento medio (Mm)
* Torque alternante (Ta)
* Torque medio (Tm)

# Propiedades del material

* Resistencia última (Sut)
* Límite de fluencia (Sy)
* Límite de resistencia a la fatiga (Se)

# Factores opcionales

Se pueden calcular automáticamente o introducir manualmente:

* (Kt, Kts)
* (q, qs)
* (Kf, Kfs)

# Resultados obtenidos

El programa muestra:

* Relaciones geométricas (D/d) y (r/d)
* Factores de concentración
* Factores de fatiga
* Esfuerzos alternantes y medios
* Esfuerzos equivalentes de Von Mises
* Esfuerzo máximo
* Factores de seguridad para distintos criterios de diseño

# Requisitos

* Python **3.x**
* Librerías utilizadas:

```python
math
tkinter
ttk
```

Estas librerías vienen incluidas por defecto en la mayoría de instalaciones de Python.

# Ejecución

1. Clonar el repositorio

```bash
git clone https://github.com/tu_usuario/nombre_del_repositorio.git
```

2. Entrar al directorio

```bash
cd nombre_del_repositorio
```

3. Ejecutar el programa

```bash
python nombre_del_archivo.py
```

# Interfaz del programa

La aplicación contiene dos pestañas principales:

**Datos**

* Se introducen las propiedades geométricas, cargas y propiedades del material.

**Resultados**

* Se muestran los cálculos completos del análisis de fatiga.

# Aplicaciones

Este programa puede utilizarse para:

* Análisis de diseño de ejes
* Verificación de seguridad en fatiga
* Apoyo académico en cursos de:

  * Diseño de Elementos Mecánicos
  * Resistencia de Materiales
  * Mecánica de Materiales

# Autores
Alamilla Barjau Raúl
Córdova Hernández Yeny Laura
Díaz López Aldo Humberto
Pérez Custodio Waris Itzel
Pons López Miguel Eduardo
Ramírez Reyes Juan Diego
Soto Magaña Abby Skarlett
Estudiantes de Ingeniería en Mecatrónica
Sexto semestre Grupo:A
