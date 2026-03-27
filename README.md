<h1 align="center">SmartBus: Predicción del tiempo de espera en transporte público </h1>

<p align="center">
  <img src=smartbus.jpg>
</p>

## Naturaleza del proyecto

SmartBus es una solución de ciencia de datos diseñada para predecir el tiempo real de espera en las estaciones del transporte publico.El proyecto surge como respuesta a la necesidad de mejorar la experiencia de los usuarios del transporte público y reducir la incertidumbre asociada a los tiempos de llegada de los buses a las estaciones.
## Liderazgo del proyecto

El científico de datos fue responsable de:
- Definir el problema analítico junto a stakeholders del sistema de transporte.
- Diseñar la estrategia de recolección y preparación de datos.
- Construir modelos predictivos de tiempo de llegada.
- Evaluar el desempeño de los modelos mediante métricas estadísticas.
- Coordinar la implementación de la solución en una aplicación digital.

## Objetivo del proyecto

Desarrollar un modelo de machine learning capaz de predecir el tiempo estimado de llegada de buses utilizando datos históricos de operación, condiciones de tráfico y patrones de demanda.


## Metodología aplicada

El proyecto siguió el ciclo de vida de ciencia de datos:

1. Comprensión del negocio
2. Comprensión de los datos
3. Preparación de datos
4. Modelado
5. Evaluación
6. Despliegue

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Comfortaa&size=50&pause=50&color=FF6B6B&center=false&vCenter=false&width=2000&height=200&lines=Producto+desarrollado)](https://git.io/typing-svg)

Se implementó una aplicación que permite:
- Consultar el tiempo estimado de llegada del bus
- Visualizar predicciones en tiempo real
- Identificar horarios de mayor congestión
## Funcionamiento de la aplicación

La aplicación obtiene la ubicación en tiempo real del bus correspondiente a la ruta seleccionada y estima su tiempo de llegada a la estación.

Para realizar esta predicción, el sistema tiene en cuenta múltiples variables, tales como:

- Hora del día
- Datos históricos de tiempos de recorrido en trayectos similares
- Condiciones climáticas (por ejemplo, la lluvia puede generar retrasos)
- Volumen estimado de pasajeros, basado en registros de validaciones en estaciones
- Estado del tráfico urbano

A partir de estos datos, el modelo predictivo calcula un tiempo estimado de llegada, ajustándose dinámicamente a las condiciones actuales y patrones históricos.

## Modelo predictivo

El sistema utiliza un modelo de regresión supervisada que aprende a partir de datos históricos para predecir el tiempo de llegada de los buses.

Las variables de entrada incluyen:

- Distancia del bus a la estación
- Nivel de tráfico
- Hora del día
- Condiciones climáticas
- Cantidad de pasajeros segun la hora

El modelo identifica patrones en estos datos y genera predicciones en tiempo real.

 Distancia (km) | Hora     | Tráfico | Clima  | Pasajeros | Tiempo estimado |
|---------------|----------|--------|--------|-----------|----------------|
| 3             | 7:30 AM  | Alto   | Lluvia | Alto      | 12 minutos     |
| 1.5           | 2:00 PM  | Bajo   | Soleado| Medio     | 5 minutos      |
| 4             | 6:00 PM  | Alto   | Nublado| Alto      | 15 minutos     |

## Diferenciación frente a otras aplicaciones

A diferencia de aplicaciones existentes como [Transmiapp](https://www.transmilenio.gov.co/), SmartBus se enfoca en ofrecer predicciones más precisas mediante el uso de una mayor cantidad de variables y fuentes de datos.

Mientras que otras aplicaciones se basan principalmente en la ubicación en tiempo real de los buses, SmartBus integra múltiples factores como:

- Condiciones del tráfico urbano
- Datos climáticos
- Históricos de tiempos de recorrido
- Volumen estimado de pasajeros
- Hora del día y patrones de demanda

Esto permite generar estimaciones más completas y ajustadas a la realidad.

Además, SmartBus es una aplicación independiente, lo que le permite ser flexible en la integración de nuevas fuentes de datos y en la mejora continua de sus modelos predictivos, sin depender directamente de las limitaciones de sistemas oficiales.

la aplicación se encuentra disponible por el momento solo en Play Store en fase beta.
<a href="https://play.google.com/store/games?hl=es_CO">  <img src="https://i0.wp.com/unaaldia.hispasec.com/wp-content/uploads/2022/07/image-3.png?resize=1024%2C647&ssl=1"> </a>




