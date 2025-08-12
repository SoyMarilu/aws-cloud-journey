# AWS Cloud Journey – Weekly Progress

Este directorio recoge mi **avance semanal** mientras desarrollo mi experiencia en AWS. Cada semana incluyo ejemplos, reflexiones, retos superados y aprendizajes clave.

---

##  Estructura del directorio

- `week-XX/`: Carpeta para cada semana (e.g. `week-01`, `week-02`, etc.).
  - `README.md`: Resumen de lo estudiado durante la semana.
  - `scripts/`: Scripts o códigos utilizados.
  - `diagrams/`: Diagramas (ejemplo: infraestructura o flujos).
  - `notes.md`: Apuntes detallados o documentos complementarios.

---

##  Cómo utilizarlo

1. Navega a la carpeta de la semana que te interese (`week-03`, por ejemplo).
2. Abre el `README.md` para ver:
   - Objetivos semanales.
   - Temas cubiertos.
   - Retos enfrentados y posibles soluciones.
   - Preguntas abiertas para seguimiento.
3. Revisa los scripts y diagramas para entender la implementación práctica.

---

##  Ejemplo: Estructura de `week-03/README.md`

```markdown
# Semana 03 – Infraestructura Global y Fiabilidad

## Objetivos de la semana
- Entender la infraestructura global de AWS: regiones, zonas de disponibilidad y edge locations.
- Aprender buenas prácticas para la alta disponibilidad y tolerancia a fallos.

## Temas cubiertos
- Diferencias entre Regiones, AZ, Edge locations, Local Zones.
- Servicios clave: Route 53, CloudFront, Multi-AZ RDS, ELB, Auto Scaling.

## Retos y soluciones
- **Reto**: Configurar un despliegue multi-AZ desde cero.
  **Solución**: Usé Terraform para definir infraestructura en dos AZs, con ELB y Auto Scaling.

## Scripts y recursos
- `scripts/setup-multi-az.sh`: Script para desplegar infraestructura básica.
- `diagrams/global-infra.png`: Diagrama de la arquitectura utilizada.

## Preguntas abiertas
- ¿Cómo optimizaría esto para múltiples regiones?
- ¿Qué implicaciones tiene usar Wavelength zones comparado con Local Zones?

## Aprendizajes clave
- La segmentación multi-AZ mejora la resiliencia.
- Edge locations aceleran la distribución de contenido a escala global.

