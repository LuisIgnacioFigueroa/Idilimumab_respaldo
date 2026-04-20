# Idilimumab_respaldo
Código empleado para la evaluacion estadística y gráfica de la Respuesta transcripcional en pacientes con leucémia linfoblastica aguda tratados con Idillimumad (inductor de miRNAs)

## Descripcion

Este codigo implementa un flujo de trabajo para el **analisis estadistico y la visualizacion grafica** de la respuesta transcripcional en pacientes con **leucemia linfoblastica aguda (LLA)** tratados con **Idilimumab**, un inductor de miRNAs.
El objetivo es identificar patrones diferenciales de expresion y representar graficamente los resultados para facilitar la interpretacion biomedica.

# La implementación integra tres componentes principales:

## Procesamiento de datos transcriptómicos

Importación y normalización de matrices de expresión génica derivadas de secuenciación de RNA (RNA-seq) o microarrays.

Filtrado de ruido técnico y ajuste por covariables clínicas relevantes (edad, sexo, estado de la enfermedad).

Transformación de datos para análisis comparativo entre grupos tratados y controles.

## Evaluación estadística

Aplicación de pruebas de hipótesis (t-test, ANOVA, modelos lineales generalizados) para identificar diferencias significativas en la expresión de miRNAs modulados por Idilimumab.

Corrección por múltiples comparaciones mediante métodos como Benjamini-Hochberg (FDR).

Cálculo de métricas de efecto (fold-change, intervalos de confianza) para cuantificar la magnitud de la respuesta transcripcional.

## Visualización gráfica

Generación de gráficos exploratorios (boxplots, heatmaps, PCA) que permiten observar patrones globales de expresión.

Representación de perfiles diferenciales mediante volcano plots y diagramas de dispersión para destacar miRNAs regulados significativamente.

Integración de anotaciones funcionales que vinculan los miRNAs modulados con rutas biológicas y procesos celulares asociados a la progresión de la LLA.
