# Marco Nacional de Domicilios Geográficos - Nominatim

## Instalación

1. Clonar el repositorio: `git clone https://github.com/guillermocegueda/mndg-nominatim`
2. Entrar a la carpeta: `cd mndg-nominatim`
3. Instalar las dependencias: `yarn install` | `npm install` | `pnpm install`

## Configuración principal

1. Editar en el archivo `dist/theme/config.theme.template.js` las variables de conexión y del mapa
2. Renombrar el archivo `dist/theme/config.theme.template.js` a `dist/theme/config.theme.js`

## Starting the frontend

**Nota: el servidor API de Nominamit ya debería estar corriendo en este punto**

1. Iniciar el modo de desarrollo: `yarn dev` | `npm run dev` | `pnpm dev`
2. Abrir en un navegador la siguiente dirección: [localhost](http://localhost:9080)

## License

The source code is available under a [GPLv2 license](LICENSE).
