# Automatizaciones con Power Automate

Colección de automatizaciones de proceso construidas con **Microsoft Power Automate** en un
entorno corporativo real. No son ejercicios de curso: resuelven problemas concretos de extracción
de datos, deduplicación y manejo de zonas horarias.

> Todos los flujos están **anonimizados**: sin identificadores de tenant, usuario, conexiones,
> drive, calendario, correo ni buzón. Datos de ejemplo inventados.

## Proyectos

| Proyecto | Problema que resuelve | Lo técnico que demuestra |
|---|---|---|
| [**email-to-excel-extractor**](./email-to-excel-extractor) | Convierte correos de aviso semiestructurados en filas limpias y sin duplicados en Excel | Parsing con `trim`/`split`, deduplicación server-side (`$filter`), `convertTimeZone`, control de concurrencia |
| [**calendar-digest**](./calendar-digest) | Envía cada mañana un resumen del día del calendario en un solo correo | Trigger programado, ventanas de fecha en zona horaria correcta, `For each` + `Join` para componer HTML |

## Stack

Microsoft Power Automate (Cloud) · Microsoft 365 (Outlook, Excel, Calendar) · expresiones `fx`
(`trim`, `split`, `convertTimeZone`, `formatDateTime`, `Join`).

## Otros proyectos

Para el lado de **agentes de IA**, mira mi proyecto destacado:
👉 [News Reporter Agent](https://github.com/CarlesChe7/News-Master-Reporter)

## Autor

**Carles Escrich Andreu** · Consultor de IA e Hiperautomatización · MB-800
[LinkedIn](https://www.linkedin.com/in/CarlesEscrichAndreu) · [GitHub](https://github.com/CarlesChe7)
