# Rueda Libre

Rueda Libre es un proyecto de sitio web institucional y de campañas para una empresa de alquiler de bicicletas y rutas guiadas en Medellín. El proyecto combina una base visual personalizada con Bootstrap y una exploración de diseño en Tailwind para campañas y prototipos.

## Descripción del proyecto

La propuesta busca comunicar la marca de forma clara y moderna, mostrando servicios, rutas, precios, reservas y una narrativa visual más dinámica para campañas especiales. La estructura está orientada a una navegación simple y una identidad visual consistente con los siguientes elementos:

- paleta de marca basada en verde, azul, crema y naranja
- tipografías Montserrat y Open Sans
- diseño responsive
- uso de Bootstrap para grillas y componentes
- uso de Tailwind para prototipos y librería de componentes
- enfoque en accesibilidad, foco visible y consistencia visual

## Tecnologías utilizadas

- HTML5
- CSS3
- Bootstrap 5
- Tailwind CSS
- JavaScript
- Google Fonts
- Bootstrap Icons
- Node.js + npm para Tailwind CLI

## Estructura del proyecto

```text
rueda_libre/
├─ index.html
├─ context-proyecto.md
├─ README.md
├─ bitacora.txt
├─ css/
│  └─ styles.css
├─ img/
├─ paginas/
│  ├─ tarifas.html
│  └─ reservas.html
├─ pruebas/
│  └─ catalogo-bootstrap.html
├─ nocturna/
│  ├─ index.html
│  ├─ componentes.html
│  ├─ prototipo.html
│  ├─ package.json
│  ├─ .gitignore
│  └─ src/
│     ├─ input.css
│     └─ output.css
└─ .gitignore
```

## Requisitos

Para visualizar el proyecto en el navegador, solo necesitas un servidor local o abrir los archivos HTML directamente en el navegador.

Para la parte de Tailwind CLI en `nocturna/`, necesitas tener instalado:

- Node.js 18 o superior
- npm

## Instalación

1. Clona el repositorio.
2. Abre una terminal en la raíz del proyecto.
3. Si quieres trabajar con la carpeta `nocturna/`:

```bash
cd nocturna
npm install
npm run build
```

4. Si deseas observar cambios en tiempo real:

```bash
npm run watch
```

## Cómo ejecutar el proyecto

### Proyecto principal

Puedes abrir directamente `index.html` en el navegador o usar un servidor local como Live Server en VS Code.

### Proyecto Tailwind

En la carpeta `nocturna/`:

```bash
npm run watch
```

Luego abre `nocturna/index.html` en el navegador.

## Características principales

- marca consistente en páginas principales
- diseño responsive y mobile-first
- menú de navegación accesible
- llamadas a la acción estandarizadas
- flota y rutas con cards visualmente consistentes
- formularios con validación y mensajes útiles
- prototipos de campaña con Tailwind
- librería de componentes visuales en una página separada

## Convenciones de desarrollo

- No se usan estilos en línea ni etiquetas `<style>` en el HTML.
- La identidad visual se centraliza en archivos CSS específicos.
- Las páginas usan estructura semántica con HTML limpio.
- Se prioriza la accesibilidad, el contraste y el foco visible.
- Se mantiene consistencia entre botones, alertas, inputs y cards.
- Los componentes reutilizables se documentan y se prueban visualmente.

## Buenas prácticas aplicadas

- separacióndo de responsabilidades entre estructura, estilos y prototipos
- uso de nombres descriptivos y claros
- enfoque en mantenibilidad del código
- carga de recursos desde CDN cuando aplica
- uso de utilidades y clases reutilizables en Tailwind
- documentación de decisiones y evolución del proyecto en `bitacora.txt`
- archivo de contexto para continuidad del proyecto

## Documentación adicional

- `contexto-proyecto.md`: contexto y evolución del proyecto.
- `bitacora.txt`: decisiones, pruebas, validaciones y observaciones del proceso.

## Autor y estado

Proyecto académico / de práctica visual y de desarrollo frontend para la empresa ficticia Rueda Libre.

## Licencia

Este proyecto se entrega con fines educativos y de práctica académica.
