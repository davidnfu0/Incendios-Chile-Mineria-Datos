# Una exploración sobre los incendios en Chile

Proyecto sobre los **Datos Históricos de Incendios en Chile** para el curso **Minería de Datos** (*CC5205*) de la Facultad de Ciencias Físicas y Matemáticas de la **Universida de Chile**.

___
**Profesores:** Cinthia Sánchez Macías y Jazmine Maldonado.
___
**Integrantes:** David Felipe, Cristian Jara, Alfredo Padilla, Gonzalo Serradilla y Pablo Vergara.
___

## Introducción y Motivación

El conjunto de datos que analizaremos proviene del Instituto para la Resilencia ante Desastres y comprende los incendios forestales registrados por CONAF en el período que abarca desde 2002 hasta 2020. Este conjunto de datos nos proporciona una visión temporal de estos incidentes, ya que se encuentra organizado por temporadas. Además, ofrece información detallada sobre cada evento, incluyendo su ubicación geográfica, la extensión de vegetación afectada, la causa del incendio, el nivel de alerta emitido y la duración de cada incidente.

Los incendios forestales han sido un problema que ha afectado a nuestro país durante años, siendo una de las grandes problemáticas de cada verano en el país, por lo que una buena compresión e interpretación de los datos puede ser muy provechosa para contribuir al desarrollo de estrategias efectivas de manejo ambiental y de seguridad.

**Variables del Dataset:**

-   **Ubicación:** Región, Provincia y Comuna, además de Latitud, Longitud y el Datum del punto de ignición estimado.

-   **Fecha:** Temporada, Fecha, Hora de inicio y Duración (en minutos) del incendio.

-   **Información del evento:** Nombre, Alerta Emitida, Escenario y Causa.

-   **Superficie quemada (en hectáreas):** Pino A, Pino B, Pino C, Eucalipto, Otras plantas, Arbolado, Matorral, Pastizal, Agrícola, Desechos y Total.

-   **Escenarios:** Variable que indica el tipo de escenario en que se desarrolló el incendio.

**Obtención de los datos:**

Los datos fueron obtenidos del sitio web: `www.plataformadedatos.cl`. Es una plataforma de acceso libre, que entre otras cosas, entrega datos sobre desastres socio naturales como los incendios. Esta plataforma es impulsada principalmente por la *CORFO*, el *Ministerio del Interior y Seguridad Pública* y el **CTCI**.

-   Los datos se pueden obtener en el siguiente enlace: [data](https://www.plataformadedatos.cl/catalog/categories/HAZARD/Incendio%20forestal/Registro%20hist%C3%B3rico%20de%20incendios).

___

## Preguntas de Investigación

___
1. ¿Es factible predecir la severidad de un incendio forestal en curso y determinar el nivel de alerta correspondiente basándose en sus características y factores actuales?
___
2. ¿Se pueden usar los registros existentes de incendios para identificar patrones y características predictivas que diferencien entre causas intencionales y no intencionales?
___
3. ¿Se pueden identificar grupos de incendios que compartan características similares, y estos grupos podrían proporcionarnos información valiosa para abordar eficazmente estas situaciones de emergencia?
___

## Metodología

Estas preguntas se contestarán mediante la aplicación de técnicas de minería de datos, tales como:
-  **Clustering:** Para identificar grupos de incendios que compartan características similares.
-  **Clasificación:** Para predecir la severidad de un incendio forestal en curso y determinar el nivel de alerta correspondiente basándose en sus características y factores actuales.

___