**EN** [English version](README.md)

# Cabbie — Caso de estudio independiente de producto y arquitectura

> Estado: **en progreso** · Extracto de arquitectura sanitizado: sin credenciales, registros de clientes ni URLs de producción.

Plataforma de reservas de viajes para un servicio de conductores privados: sitio web público, flujo de reservas, gestión de conductores, reglas de tarifas, gestión de contenidos y registro de auditoría.

## Diagramas interactivos

[Ver ambos diagramas interactivos en una sola página](https://reyvit-cisneros.github.io/cabbie-case-study/)

La página muestra primero el flujo operativo y debajo el modelo de datos.

- [Flujo operativo — animado](https://reyvit-cisneros.github.io/cabbie-case-study/cabbie-flujo-operativo.html)
- [Modelo de datos — animado](https://reyvit-cisneros.github.io/cabbie-case-study/cabbie-modelo-datos.html)

## Visión operativa

[![Flujo operativo de Cabbie](operational-flow.png)](https://reyvit-cisneros.github.io/cabbie-case-study/cabbie-flujo-operativo.html)

[Abrir el flujo operativo animado](https://reyvit-cisneros.github.io/cabbie-case-study/cabbie-flujo-operativo.html)

## Modelo de datos

Extracto sanitizado del modelo entidad-relación. Las relaciones punteadas representan asociaciones lógicas, no necesariamente restricciones de clave foránea de la base de datos. Los campos redactados indican información omitida, no tipos de datos reales.

[![Modelo de datos de Cabbie](data-model.png)](https://reyvit-cisneros.github.io/cabbie-case-study/cabbie-modelo-datos.html)

[Abrir el modelo de datos animado](https://reyvit-cisneros.github.io/cabbie-case-study/cabbie-modelo-datos.html)

> Las etiquetas de los diagramas están en inglés. El código fuente de los diagramas (Mermaid) está en el [README en inglés](README.md).

## Problema

Los pequeños operadores de transporte pierden reservas por flujos lentos por teléfono o WhatsApp y no cuentan con un registro estructurado de viajes, calificaciones ni precios.

## Restricciones

- Mobile-first, rápido en 4G.
- Datos personales tratados bajo principios de privacidad desde el diseño.
- Contenido editable sin desarrolladores.
- Bajo costo operativo.

## Solución

Un flujo de reservas conectado que combina el sitio web público, reglas de tarifas, caché de geocodificación, controles de acceso a la base de datos, administración, contenido editable y registro de auditoría.

## Documentos

- [ARCHITECTURE.md](ARCHITECTURE.md) — capas, flujo de datos y modelo de seguridad (en inglés).
- [DATABASE.md](DATABASE.md) — modelo entidad-relación sanitizado (en inglés).
- [Diagramas interactivos](https://reyvit-cisneros.github.io/cabbie-case-study/) — flujo operativo y modelo de datos en una sola página.

## Mi rol

Definición de producto, flujos UX, modelo de datos, políticas de seguridad, SEO y entrega — con desarrollo asistido por IA y un método documentado ([Reyvit Framework](https://github.com/Reyvit-Cisneros/reyvit-framework)).

## Omitido por confidencialidad

Identidad del cliente, registros reales, código literal de las políticas de acceso, claves de API, endpoints internos y URLs de producción.

## Licencia

Documentación y diagramas: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
