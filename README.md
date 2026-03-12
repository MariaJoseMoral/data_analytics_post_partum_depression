# Análisis de datos sobre la depresión postparto

Proyecto de análisis exploratorio y visualización de datos sobre síntomas asociados a la **depresión postparto**, basado en el estudio *La violencia del diagnóstico* de la psiquiatra **Laura Martín López-Andrade**.

El objetivo del proyecto es identificar **patrones sintomáticos, relaciones entre síntomas y diferencias por grupos de edad** mediante análisis estadístico y visualización interactiva.

---

## Objetivos del proyecto

- Analizar la **distribución de síntomas** asociados a depresión postparto.
- Identificar **síntomas predominantes** dentro de la muestra.
- Explorar **relaciones entre síntomas** mediante correlaciones.
- Analizar si existen **diferencias sintomáticas entre grupos de edad**.
- Detectar **síntomas centrales** dentro de la red de síntomas.

---

## Dataset

El dataset recoge respuestas de **1.503 madres** sobre diferentes síntomas asociados a depresión postparto.

### Variables principales

- **Edad** (agrupada por rangos)
- **Síntomas emocionales**
  - Ansiedad
  - Tristeza
  - Culpa
  - Irritabilidad
- **Síntomas conductuales**
  - Problemas de vínculo con el bebé
  - Trastornos alimentarios
  - Insomnio
  - Intentos suicidas
- **Síntomas cognitivos**
  - Problemas de concentración o toma de decisiones

Los síntomas se reportan según frecuencia de aparición.

---

## Estructura del análisis

El proyecto se organiza en varios bloques de análisis visual:

### 1. Muestra y distribución por edad

- Total de participantes: **1503 madres**
- Mayor concentración entre **35 y 45 años**
- Distribución relativamente equilibrada entre rangos de edad.

Principales indicadores:

- 24,2 % de la muestra se sitúa entre **40-45 años**
- **65,2 %** reporta **ansiedad**

---

### 2. Síntomas predominantes

Los síntomas más frecuentes dentro de la muestra son:

1. **Ansiedad**
2. **Problemas de sueño**
3. **Irritabilidad**
4. **Tristeza**
5. **Problemas de concentración**

Los **síntomas emocionales** representan más de la mitad de los casos reportados.

---

### 3. Comparación por grupos de edad

El análisis muestra que:

- El **patrón de síntomas es relativamente estable entre edades**
- No aparecen diferencias significativas entre rangos etarios.
- Los síntomas emocionales siguen siendo predominantes en todos los grupos.

Esto sugiere que la experiencia sintomática de la depresión postparto **no depende fuertemente de la edad de la madre**.

---

### 4. Clusters emocionales y red de síntomas

Se realizó un análisis de correlación entre síntomas para detectar **relaciones dentro del sistema sintomático**.

Resultados principales:

- Existen **correlaciones moderadas entre síntomas emocionales y conductuales**.
- Algunos síntomas funcionan como **nodos centrales** dentro de la red.

Síntomas con mayor centralidad:

| Síntoma | Centralidad |
|--------|-------------|
| Irritabilidad | 3.33 |
| Ansiedad | 3.27 |
| Culpa | 3.06 |
| Trastorno alimentario | 2.95 |
| Intento suicida | 2.68 |

Esto sugiere que ciertos síntomas pueden **activar o reforzar otros dentro del sistema**.

---

## Principales conclusiones

- **La ansiedad emerge como síntoma central**, conectándose con múltiples manifestaciones emocionales y conductuales.
- Los **síntomas emocionales predominan** en la depresión postparto (ansiedad, tristeza y culpa).
- El **patrón de síntomas es estable entre grupos de edad**.
- Algunos síntomas actúan como **conectores dentro de la red sintomática**, lo que puede ser relevante para estrategias de detección temprana.

---

## Retos del análisis

- El dataset original se encontraba en **formato wide**, lo que dificultaba algunos análisis.
- El **modelo de respuestas** (frecuencias categóricas) requiere transformación para ciertos métodos estadísticos.
- Falta de variables adicionales para enriquecer el análisis.

---

## Próximos pasos

- Incorporar **variables socioeconómicas**:
  - nivel educativo
  - modelo familiar
  - origen
  - situación económica

- Analizar la **relación entre síntomas y circunstancias vitales**.
- Explorar la **evolución temporal de los síntomas** mediante datos longitudinales.
- Aplicar **modelos de redes psicológicas** para estudiar interacciones entre síntomas.

---

## Herramientas utilizadas

- **Power BI** — visualización interactiva
- **Python / Pandas** — preparación y análisis de datos
- **Análisis de correlación** para detección de clusters sintomáticos

---

## Autora

**María José Moral Morgado**

📧 mariamoral1@gmail.com

---

## Referencia

Este proyecto se basa en el estudio:

**Laura Martín López-Andrade**  
*La violencia del diagnóstico*

---

## Licencia

Este proyecto tiene fines **educativos y de investigación**.
