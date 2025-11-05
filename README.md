# PowerFit Gym (FitLife) 🏋️‍♂️

Una landing page estática y responsive para un gimnasio (PowerFit Gym, también referido como FitLife en el código). El objetivo es ofrecer una presentación moderna de los planes de membresía, el equipo de entrenadores y los datos de contacto.

## Tecnologías

- HTML5 — Estructura semántica de las páginas.
- CSS3 (Vanilla CSS) — Estilos y diseño responsive sin frameworks.

## Estructura de archivos

```
/ (raíz)
├── index.html          # Página de Inicio
├── planes.html         # Página detallada de Planes y Ejercicios
├── entrenadores.html   # Página del Equipo de Entrenadores
├── contactos.html      # Página de Contacto y Formulario
└── estilo.css          # Archivo de estilos global (CSS principal)
```

## Características clave

- Diseño responsive: Media queries para móviles, tablets y escritorio.
- Paleta de colores moderna: degradados morado→azul (ej. #667eea → #764ba2) para header y elementos interactivos.
- Navegación fija (sticky): la barra superior se mantiene visible al hacer scroll.
- Página de Planes (`planes.html`): descripción de membresías (Básico, Premium, Elite) y secciones por tipo de entrenamiento (Musculación, CrossFit, etc.).
- Tarjetas modulares: uso de `.plan-card` para presentar planes y ejercicios.
- Fichas de entrenadores: tarjetas `.entrenador-card` con imagen, especialidad y descripción.
- Formulario de contacto en `contactos.html` con campos obligatorios (Nombre, Email, Mensaje).

## Instalación y uso

Este proyecto es estático—no requiere servidor ni instalación compleja. Para verlo localmente basta con abrir los archivos HTML en un navegador.

Clonar el repositorio (opcional):

```bash
git clone <URL-DEL-REPOSITORIO>
cd proyecto-gym-
# Abrir `index.html` en tu navegador preferido
```

## Notas de desarrollo

- Todos los estilos están escritos en `estilo.css`, salvo algunos estilos específicos que pueden estar inyectados localmente en ciertas páginas (por ejemplo, estilos adicionales en `contactos.html`).
- Convenciones: clases como `.plan-card` y `.entrenador-card` se usan para tarjetas reutilizables.

## Flujo de trabajo sugerido

- Usar Git/GitHub para control de versiones.
- Metodología ágil (p. ej. sprints en Trello) para organizar tareas y backlog.

## Equipo

Proyecto desarrollado en un entorno colaborativo. Herramientas típicas: Trello, Git/GitHub.

---

mientas como Trello (para sprints y backlog) y Git/GitHub (para control de versiones), en un entorno de Trabajo Colaborativo.
