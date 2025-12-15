# 📊 Solucionador de Ejercicios de Monopolio

Scripts en Python para resolver automáticamente ejercicios de microeconomía sobre monopolios. Desarrollado como proyecto de aprendizaje durante mis primeros pasos con Python.

**Resuelve dos tipos de problemas:**

- Discriminación de Precios de Tercer Grado
- Tarifa Lineal de Dos Tramos

## 🎯 Qué hace

Estos notebooks automatizan los cálculos de ejercicios de monopolio. Ingresas las ecuaciones de demanda y costos, y el script hace todo el trabajo matemático:

- Calcula cantidades y precios óptimos
- Encuentra el punto de equilibrio (IMG = CMG)
- Muestra los resultados en formato LaTeX
- Genera gráficos (en el caso de tarifas de dos tramos)

## 📦 Lo que incluye

### Discriminación de Tercer Grado

- Hasta 3 segmentos de demanda
- Hasta 3 plantas de producción
- Calcula ingresos y costos marginales
- Encuentra cantidades y precios por segmento
- Compara con escenario de competencia perfecta

### Tarifa Lineal de Dos Tramos

- Múltiples grupos de consumidores
- Calcula precio de uso (P) y cargo fijo (A)
- Genera gráficos de la solución
- Entrada interactiva de datos

## Ejemplos de uso

### Discriminación de Tercer Grado

Abre `Discriminación_de_tercer_grado.ipynb` y sigue las instrucciones. Básicamente:

1. Define cuántos mercados y plantas tienes
2. Ingresa las ecuaciones de demanda (formato: `q = 180 - 3/2 * p`)
3. Ingresa las ecuaciones de costo (formato: `CT = 60 * q + 4200`)
4. Ejecuta y obtén los resultados

### Tarifa de Dos Tramos

Abre `Tarifa lineal de dos tramos.ipynb`:

1. Ingresa el número de grupos de consumidores
2. Ingresa las demandas lineales
3. Ingresa la función de costo
4. El notebook calcula P, A y genera un gráfico

---

Hecho por [Johan Escobar](https://www.linkedin.com/in/johan-er/) • [GitHub](https://github.com/JohanEsR17)

*Proyecto de aprendizaje de Python aplicado a microeconomía*
