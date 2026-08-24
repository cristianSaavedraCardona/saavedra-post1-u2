# Post-contenido — Unidad 2: HTML5 Básico

## Descripción

Este repositorio contiene las dos partes del laboratorio de HTML5 de la Unidad 2 de Programación Web.

La Parte 1 consiste en la construcción de un portafolio personal utilizando etiquetas semánticas de HTML5, multimedia, accesibilidad, enlaces y elementos interactivos nativos.

La Parte 2 corresponde a un formulario de registro universitario utilizando diferentes tipos de input de HTML5, agrupación mediante fieldset y legend, validación nativa y atributos de accesibilidad.

## Parte 1 — Página semántica

La Parte 1 se encuentra en:

parte-1-pagina-semantica/

La página contiene:

- Estructura semántica con header, nav, main, section, article, aside y footer.
- Jerarquía de encabezados.
- Listas ordenadas y desordenadas.
- Enlaces internos y externos.
- Atributos de seguridad en enlaces externos.
- Imagen de perfil con texto alternativo.
- Audio de presentación personal.
- Transcripción del audio para accesibilidad.
- Elementos interactivos details y summary.
- Meta tags para SEO.

## Parte 2 — Formulario de registro

La Parte 2 se encuentra en:

parte-2-formulario-registro/

El formulario corresponde al registro de estudiantes de la Facultad de Ingeniería de Sistemas.

Incluye más de 10 tipos de controles HTML5:

- text
- email
- password
- tel
- url
- date
- number
- range
- color
- file
- checkbox
- radio
- hidden
- textarea
- select

También utiliza:

- fieldset y legend para agrupación semántica.
- label correctamente vinculados mediante for e id.
- Validación HTML5 mediante required, pattern, min, max, minlength y maxlength.
- Mensajes personalizados mediante title.
- autocomplete.
- aria-describedby.
- optgroup.
- Método POST.
- Acción /api/registro.

## Decisiones de diseño

### 1. Estructura semántica de "Logros y Certificaciones" — Parte 1

Se eligió la Opción B, utilizando una lista <ul> sin un <article> independiente para cada logro.

Esta decisión se tomó porque los logros y certificaciones funcionan principalmente como elementos de una colección dentro del portafolio. Cada elemento complementa la información profesional y no necesita funcionar como un contenido independiente fuera del sitio.

### 2. Formato multimedia de la introducción personal — Parte 1

Se eligió la Opción B, utilizando audio con una transcripción dentro de details y summary.

El audio permite realizar una presentación personal de manera sencilla y adecuada para el contenido del portafolio. Como estrategia de accesibilidad, la transcripción permite que las personas que no puedan escuchar el audio también puedan acceder a la información presentada.

### 3. Marcado del campo opcional "teléfono" — Parte 2

Se eligió la Opción A, utilizando el texto (opcional) directamente en el label del campo teléfono.

Esta alternativa permite que cualquier usuario pueda identificar inmediatamente que el teléfono no es obligatorio, sin depender de tecnología de asistencia. Además, mantiene una indicación clara y visible dentro del formulario.

## Tecnologías utilizadas

- HTML5
- Git
- GitHub
- Visual Studio Code
- Live Server

## Estructura del proyecto

```text
saavedra-post1-u2/
│
├── parte-1-pagina-semantica/
│   ├── index.html
│   ├── img/
│   │   ├── perfil.jpg
│   │   └── captura-01.png
│   └── audio/
│       └── intro.mp3
│
├── parte-2-formulario-registro/
│   ├── registro.html
│   └── img/
│       └── captura-01.png
│
├── .gitignore
└── README.md