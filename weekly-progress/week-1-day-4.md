# Progreso Diario – AWS Cloud Journey

## Fecha
2025-08-12

## Módulo completado
**Módulo 3 – Infraestructura Global y Fiabilidad**

## Objetivos de aprendizaje
- Comprender la jerarquía de la infraestructura de AWS:
  - Regiones, Zonas de Disponibilidad (AZ), Edge Locations, Local Zones, Wavelength Zones.
- Identificar prácticas de diseño para alta disponibilidad y tolerancia a fallos.
- Conocer servicios que soportan fiabilidad y distribución global.

## Contenido cubierto
- Diferencia entre región y AZ.
- Importancia de distribuir recursos en múltiples AZ para minimizar el impacto de fallos.
- Uso de Edge Locations para mejorar la latencia en entrega de contenido (CloudFront, Route 53, Global Accelerator).
- Principios de **Alta Disponibilidad (HA)**, **Tolerancia a Fallos** y **Escalabilidad** en AWS.
- Servicios relevantes:
  - **Route 53** (DNS escalable y global).
  - **CloudFront** (CDN).
  - **S3** (durabilidad 99.999999999%).
  - **Auto Scaling** y **ELB** para distribución de carga.
  - **CloudWatch** para monitoreo proactivo.

## Ejemplo práctico realizado
- Simulación de despliegue de aplicación en dos AZ con balanceador de carga y Auto Scaling para manejar tráfico variable.
- Configuración teórica de distribución de contenido con CloudFront para reducir latencia global.

## Aprendizajes clave
- Distribuir en varias AZ es esencial para evitar interrupciones.
- Edge Locations no son centros de datos completos, sino puntos de presencia para mejorar el acceso.
- Multi-AZ ≠ Multi-Region: el primero es para resiliencia local, el segundo para recuperación ante desastres globales.

## Próximo paso
- Iniciar el **Módulo 4** del curso (pendiente de confirmar tema).
