# backend/

API REST del proyecto, construida con **FastAPI** (Python).

Responsabilidad: exponer los endpoints que consume el frontend y comunicarse con la base de datos PostgreSQL mediante SQLAlchemy.

## Estructura prevista

```
backend/
├── app/
│   ├── main.py          # Punto de entrada de la API
│   ├── models/          # Modelos de datos (SQLAlchemy)
│   ├── schemas/         # Validación de entrada/salida (Pydantic)
│   └── routers/         # Endpoints agrupados por dominio
└── requirements.txt
```

## Puesta en marcha (referencia)

```bash
python -m venv venv
source venv/bin/activate        # En Windows: venv\Scripts\activate
pip install fastapi uvicorn sqlalchemy psycopg2-binary
uvicorn app.main:app --reload --port 8000
```

> Carpeta preparada en el Sprint 1. La implementación se incorporará en las siguientes prácticas.
