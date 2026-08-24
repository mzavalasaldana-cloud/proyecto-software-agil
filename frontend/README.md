# frontend/

Interfaz web del proyecto, construida con **Next.js** (React).

Responsabilidad: presentar la interfaz al usuario y consumir la API FastAPI mediante peticiones HTTP/JSON.

## Estructura prevista

```
frontend/
├── app/                 # Rutas y páginas (App Router)
├── components/          # Componentes reutilizables
├── lib/                 # Cliente HTTP hacia la API
└── package.json
```

## Puesta en marcha (referencia)

```bash
npx create-next-app@latest .
npm run dev                     # Disponible en http://localhost:3000
```

> Carpeta preparada en el Sprint 1. La implementación se incorporará en las siguientes prácticas.
