# IMT2200-Proyecto-Semestral

## Librerias usadas
pandas, numpy, matplotlib, seaborn y json

## Resumen del proyecto

El proyecto, desarrollado por nosotros, busca optimizar el proceso de selección de **Enseña Chile** mediante un enfoque de ciencia de datos que cruza registros históricos internos con fuentes públicas (MINEDUC, DEMRE) para identificar patrones de éxito en el proceso de postulación. El objetivo es caracterizar qué variables académicas y sociodemográficas predicen realmente un buen desempeño, permitiendo a la fundación mejorar su reclutamiento detectando talento en diversas universidades y carreras mediante la ciencia de datos, ayudándoles a aumentar el porcentaje de exito de sus postulantes en el proceso.

## Objetivos específicos:

- Caracterizar históricamente a postulantes y seleccionados.
- Analizar la relación universidad-carrera-selección.
- Identificar universidades y carreras prioritarias.
- Proponer una categorización en niveles de prioridad.

## Contexto y motivación

Enseña Chile es una fundación que busca atraer profesionales talentosos al mundo educativo para generar un impacto real en las comunidades escolares más vulnerables del país.

No obstante, sus procesos de postulación enfrentan desafíos importantes: la tasa de aceptación suele ser baja y los perfiles de quienes postulan parecen ser bastante heterogéneos.

Este proyecto apunta a utilizar los datos históricos de postulaciones de Enseña Chile, junto con información universitaria disponible en fuentes públicas como el MINEDUC, para detectar patrones, brechas y oportunidades de mejora en el reclutamiento y selección del programa. La idea es elaborar recomendaciones estratégicas que ayuden a la Fundación a focalizar mejor sus esfuerzos, diversificar el perfil de candidatos y aumentar la probabilidad de éxito en las postulaciones.

La audiencia principal de este trabajo está compuesta por el equipo de gestión de Enseña Chile, aunque también busca ser un aporte para investigadores y responsables de políticas educativas interesados en comprender con mayor claridad cómo se distribuye el talento docente potencial en el país.

## Preguntas objetivo

¿Qué características académicas y sociodemográficas se correlacionan con un mayor éxito en el proceso de selección de Enseña Chile?

¿Existen universidades o carreras que presenten consistentemente una mayor proporción de postulantes aceptados?

¿Qué regiones del país presentan menor participación o tasa de éxito en postulaciones?

¿Es posible construir un modelo predictivo que estime la probabilidad de éxito de un postulante en función de sus características iniciales?

¿Cómo se pueden utilizar estos hallazgos para focalizar los esfuerzos de reclutamiento y reducir posibles sesgos hacia ciertas instituciones de elite?

## Datos
### Datos internos de Enseña Chile:

- Registros históricos de postulaciones:

Columnas Generación/Año pech: Año de la generación donde seleccionado iniciaría su primer año de colegio
Columnas # Proceso/Proceso: Procesos de postulación según fechas que se deciden cada año. De 1 a 3 anuales
Columna Resumen Estado Postulación: Si está en proceso, fuera del proceso o seleccionado.
Columna Estado de la Postulación: Depende de la etapa en que se encuentra

Siglas usadas en celdas:
DE: Día de Entrevista (Etapa de selección antigua)
PR: Primera Revisión (Formulario: filtro 1)
ET: Entrevista Telefónica (filtro 1.1)
EG: Entrevista Grupal (filtro 2)
EP: Entrevista Personal (filtro 3)
Datos externos (fuentes públicas):

Distribución de estudiantes universitarios por institución, región y carrera.
Información de equidad y brechas (ej. género, tipo de institución).

### Datos DEMRE:

Puntajes PAES de matrícula, por año, provistos por datos abiertos del Departamento de Medición, Evaluación y Registro Educacional de la Universidad de Chile.




## Integrantes y sus roles
Como roles todos participaron por igual con exactamente el mismo nivel de aporte, ya que todos participaron a su medida en la limpieza de datos, EDA, analisis, etc.
* @SergioHdezDC
* @panchoclo3
* @sebastian18931
* @Cristobal-Lyon-Diaz




