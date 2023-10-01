# Lazmaniento de SpaceX V5 - Astro 3.0


![screen-shots](./assets\spacex-launches.jpeg)

## 🚀 Estructura del proyecto

La estructura del proyectos es la siguiente:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   │   └── Header.astro
│   │   └── HeaderBtn.astro
│   │   └── Launches.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│   │   └── launch/
│   │   │   └── [id].astro
│   │   └── index.astro
│   └── service/
│   │   └── spacex-service.ts
│   └── types/
│   │   └── api.ts
└── package.json
```

Practicas con el framework de Astro en su versión 3.0 consumiendo la API de SpaceX en su versión #5 [SpaceX REST API](https://github.com/r-spacex/SpaceX-API) y siguiendo el tutorial de [Midudev](https://www.youtube.com/watch?v=RB5tR_nqUEw)

## 👷‍♂️ Como usar este repositorio

Sirvete de descargar y replicar el proyecto, tambien si quieres agregar tu aporte para mejorar el mismo solo crea un fork y haz un PR para su previa revisión.

| Commando                  | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Para instalar las dependecias                    |
| `npm run dev`             | Para desplegar el proyecto `localhost:4321`      |
| `npm run build`           | Para construit el proyecto en `./dist/`          |


