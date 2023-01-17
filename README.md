### Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

### Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

### QUE ES VUE.JS?
Framework de JS para creación de interfaces de usuario
Instalar Vue.js -> VueCLI, create-vue, Vite

npm create vite@latest
npm install
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

Para subir a Netlify -> npm run build

Escribir @recommended -> Y va a recomendar las extensiones para este proyecto

### SINGLE FILE COMPONENTS
Vue tiene su propio estilo para crear proyectos y estructurarlos
SFC es una convención en la cual cada componente tiene 3 partes: <script> <style> y <template>

- <script>: se coloca toda la logica de JS de ese componente
- <style>: se coloca todo el código CSS de ese componente
- <template>: se coloca todo el código HTML de ese componente

### Componentes:
Te permiten dividir tu código en partes reutilizables
extensión .vue

Con <scrip setup> cualquier componente que es importado se hace disponible en el template
Usan props

### API Styles
Los componentes de Vue se pueden escribir en 2 API's diferentes:
Options API -> sintaxis de tipo Objetos
Composition API -> se definen los componentes utilizando imports y escribiendo las funciones directamente en el componente

### EVENTOS
Se agregan con la directiva v-on:evento
o la sintaxis corta: @evento

## STATE
Es la fuente de la verdad (source of truth)
Administrar state: 
ref -> toma valores primitivos
reactive -> siempre toma un objeto
Recomendado usar Pinia (sustituto de VueX)

### COMPUTED PROPERTIES
codigo más ordenado y seguir teniendo actualizaciones en tu código
Es una función, que está al pendiente de los cambios de tu state, y realiza los cambios necesarios cuando este cambia.

### WATCHERS
Un watch va a tomar uno o multiples valores como dependecia, y cuando estas cambian, entonces podremos llamar a otra función o realizar una validación.

## Resultado final: https://silly-syrniki-8ab569.netlify.app/# Vue.js
