# Modelado-de-Estructuras-Latentes-An-lisis-Factorial-Aplicado. / 27 10 2026
# 📊 Modelado de Estructuras Latentes: Análisis Factorial Aplicado

## 📝 Descripción del proyecto

Este proyecto desarrolla una evaluación psicométrica del inventario **IPIP-50**, instrumento utilizado para analizar los cinco grandes factores de la personalidad (*Big Five*). Mediante técnicas de análisis factorial exploratorio y confirmatorio, se busca identificar y validar las dimensiones latentes que explican los patrones de respuesta de los participantes.

El estudio utiliza una muestra de **149.997 registros completos** y 50 ítems medidos mediante una escala Likert de cinco puntos, aplicando métodos estadísticos especializados para el tratamiento de variables ordinales.

## 🎯 Objetivo

Examinar la estructura factorial del inventario IPIP-50 para identificar, representar y evaluar cinco dimensiones fundamentales de la personalidad, utilizando técnicas de análisis multivariado implementadas en R.

## 🧠 Dimensiones analizadas

El modelo contempla los cinco grandes factores de la personalidad:

- **Extraversión (EXT):** sociabilidad, asertividad y energía.
- **Estabilidad emocional (EST):** regulación del estrés y control de la ansiedad.
- **Amabilidad (AGR):** empatía, cooperación y sensibilidad interpersonal.
- **Conciencia (CSN):** organización, disciplina y responsabilidad.
- **Apertura a la experiencia (OPN):** curiosidad intelectual, imaginación y flexibilidad.

## ⚙️ Metodología

El análisis se desarrolló mediante las siguientes etapas:

1. **Preparación de los datos:** depuración de la muestra y recodificación inversa de los 18 ítems redactados negativamente.
2. **Análisis de correlaciones:** cálculo de correlaciones policóricas para representar las relaciones entre variables ordinales.
3. **Evaluación de factibilidad:** aplicación de las pruebas Kaiser-Meyer-Olkin (KMO) y esfericidad de Bartlett.
4. **Análisis factorial exploratorio (AFE):** determinación de la estructura latente mediante extracción por mínimos residuos (*minres*) y rotación oblicua Oblimin.
5. **Análisis factorial confirmatorio (AFC):** evaluación del modelo de cinco factores mediante el paquete `lavaan` y el estimador WLSMV.
6. **Interpretación de resultados:** evaluación de índices de ajuste y análisis de las implicaciones de los factores identificados.

## 📈 Principales resultados

- **Muestra analizada:** 149.997 casos completos.
- **Variables observadas:** 50 ítems del inventario IPIP-50.
- **KMO global:** 0,909, indicador de una excelente adecuación muestral.
- **Prueba de Bartlett:** χ² = 2.766.923; p < 0,001.
- **Estructura factorial:** se retienen cinco factores principales, en concordancia con el modelo teórico de los *Big Five*.
- **Cargas factoriales:** en el análisis confirmatorio, la mayoría se sitúa entre 0,65 y 0,85.
- **Ajuste del modelo:** CFI = 0,847; TLI = 0,839; RMSEA = 0,112 y SRMR = 0,092.

Los resultados respaldan la identificación de las cinco dimensiones teóricas. Sin embargo, los índices de ajuste global del modelo confirmatorio muestran limitaciones, por lo que es necesario considerar posibles mejoras antes de concluir que el modelo presenta un ajuste satisfactorio.

## 🛠️ Herramientas y técnicas

- **R:** procesamiento y análisis estadístico.
- **Análisis factorial exploratorio (AFE).**
- **Análisis factorial confirmatorio (AFC).**
- **Correlaciones policóricas.**
- **Paquetes de R:** `lavaan` y herramientas para análisis factorial.
- **Visualización de datos:** mapas de calor, gráficos de sedimentación y diagramas de rutas factoriales.

## 💡 Aplicaciones

Este análisis permite explorar el uso de modelos psicométricos en contextos como:

- Investigación en psicología y ciencias del comportamiento.
- Construcción e interpretación de perfiles de personalidad.
- Investigación aplicada a la gestión del talento humano.
- Estudios de bienestar organizacional.
- Modelos estadísticos multivariados y ecuaciones estructurales.

Estas aplicaciones representan posibles usos de los resultados y no implican que el instrumento, por sí solo, permita predecir el desempeño laboral o diagnosticar condiciones de salud.

## 📂 Contenido del repositorio

El repositorio está orientado a documentar el desarrollo del análisis factorial aplicado al inventario IPIP-50.

Se recomienda organizarlo de la siguiente manera:

```text
analisis-factorial-ipip50/
├── README.md
├── informe/
│   └── primera_entrega_analisis_factorial.pdf
├── codigo/
│   └── analisis_factorial.R
├── datos/
│   └── README.md
└── resultados/
    └── graficos/
```

*Nota: esta estructura es una propuesta de organización. Los archivos deben incorporarse según los recursos efectivamente disponibles.*

## 🔬 Reproducibilidad

El proyecto contempla el uso de código en R y un conjunto de datos de acceso público para documentar el procedimiento estadístico. Para reproducir los resultados, se recomienda incluir el script fuente, especificar las dependencias utilizadas y documentar la fuente y las condiciones de acceso a los datos.

## 👨‍💻 Autoría

Proyecto académico sobre análisis factorial aplicado, modelado de estructuras latentes y evaluación psicométrica mediante técnicas de análisis multivariado.

---

**Palabras clave:** Análisis factorial, IPIP-50, Big Five, psicometría, R, correlaciones policóricas, AFE, AFC, variables ordinales y modelado de estructuras latentes.
