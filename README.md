# Nombre del Proyecto

Descripción breve de qué hace este proyecto y para quién está pensado.

## Requisitos

- [Node.js](https://nodejs.org/) 18 o superior
- npm (incluido con Node.js) o [pnpm](https://pnpm.io/) / [yarn](https://yarnpkg.com/)

## Instalación

```bash
git clone <url-del-repositorio>
cd <nombre-del-proyecto>
npm install
```

## Variables de entorno

Copia el archivo de ejemplo y completa los valores:

```bash
cp .env.example .env
```

| Variable | Descripción | Ejemplo |
| --- | --- | --- |
| `PORT` | Puerto del servidor | `3000` |
| `NODE_ENV` | Entorno de ejecución | `development` |

## Uso

Arranca la aplicación en desarrollo:

```bash
npm run dev
```

Arranca en producción:

```bash
npm start
```

## Scripts

| Comando | Descripción |
| --- | --- |
| `npm start` | Inicia la aplicación |
| `npm run dev` | Inicia en modo desarrollo (watch) |
| `npm test` | Ejecuta las pruebas |
| `npm run lint` | Revisa el estilo del código |
| `npm run build` | Compila el proyecto (si aplica) |

## Estructura del proyecto

```text
.
├── src/              # Código fuente
├── tests/            # Pruebas
├── package.json
└── README.md
```

## Pruebas

```bash
npm test
```

## Contribución

1. Crea una rama a partir de `main`.
2. Haz tus cambios y añade pruebas si aplica.
3. Abre un pull request con una descripción clara.

## Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo `LICENSE` para más detalles.
