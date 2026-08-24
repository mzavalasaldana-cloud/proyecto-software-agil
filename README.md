# proyecto-software-agil

Repositorio de prácticas — Ingeniería de Software II
**Guía de Laboratorio Nº 01 — Metodologías Ágiles vs. Tradicionales y Manifiesto Ágil**

## Nombre: Zavala Saldaña Marco Antonio

## Estructura del repositorio

```
proyecto-software-agil/
├── backend/          # API FastAPI (Python)
├── frontend/         # Interfaz Next.js
├── docs/             # Documentación del proyecto
│   ├── comparativa.md    # Cuadro comparativo + estudio de 3 casos
│   ├── manifiesto.md     # 4 valores y aplicación de 3 principios ágiles
│   └── arquitectura.md   # Esquema Next.js → FastAPI → PostgreSQL
├── .gitignore
└── README.md
```

## Entregables de la práctica

|#|Entregable|Ubicación|
|-|-|-|
|1|Cuadro comparativo tradicionales vs. ágiles|[`docs/comparativa.md`](docs/comparativa.md)|
|2|Análisis y justificación metodológica de los 3 proyectos|[`docs/comparativa.md`](docs/comparativa.md)|
|3|Aplicación de 3 principios ágiles al caso de comercio electrónico|[`docs/manifiesto.md`](docs/manifiesto.md)|
|4|Estructura de carpetas creada + esquema tecnológico|Este repositorio · [`docs/arquitectura.md`](docs/arquitectura.md)|

## Esquema tecnológico

```
Cliente Next.js  →  API FastAPI  →  Base de datos PostgreSQL
  (puerto 3000)     (puerto 8000)        (puerto 5432)
      HTTP/JSON        SQLAlchemy
```

