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

Si quieres que añada secciones adicionales (licencia, contribuciones, badges, instrucciones de build con herramientas) dime qué prefieres y lo actualizo.
🏋️‍♂️ Proyecto Web: PowerFit Gym (FitLife)📌 Resumen del ProyectoEste proyecto consiste en el desarrollo de una Landing Page/Web estática para un gimnasio, denominada PowerFit Gym (también referida como FitLife en el código). El objetivo principal es ofrecer una plataforma informativa, moderna y totalmente responsive para que los usuarios puedan conocer los planes de membresía, el equipo de entrenadores y la información de contacto del gimnasio.🚀 Tecnologías UtilizadasTecnologíaPropósitoHTML5Estructura semántica de las páginas web.CSS3Estilizado, diseño responsive y efectos visuales.Vanilla CSSTodos los estilos fueron escritos manualmente, sin el uso de frameworks CSS como Bootstrap.📁 Estructura de ArchivosEl proyecto se organiza en una estructura plana y clara:/
├── index.html          # Página de Inicio.
├── planes.html         # Página detallada de Planes y Ejercicios.
├── entrenadores.html   # Página del Equipo de Entrenadores.
├── contactos.html      # Página de Contacto y Formulario.
└── estilo.css          # Archivo de estilos global (CSS principal).
✨ Características Clave1. Diseño y EstiloDiseño Responsive: Implementación de Media Queries en estilo.css para asegurar la correcta visualización en dispositivos móviles, tabletas y escritorios.Paleta de Colores: Uso de degradados (linear-gradient) con tonos morados y azules (#667eea a #764ba2) para el header y elementos interactivos, proporcionando un look moderno y vibrante.Navegación Fija (Sticky): La barra de navegación superior (nav.navbar) permanece visible al hacer scroll, mejorando la accesibilidad.2. Contenido DestacadoPágina de Planes (planes.html): Detalla los planes de membresía (Básico, Premium, Elite) y organiza la información en categorías como Musculación y CrossFit.Tarjetas Modulares: Se utiliza la clase .plan-card para presentar la información de planes y ejercicios de manera uniforme y atractiva.Fichas de Entrenadores (entrenadores.html): Cada entrenador se presenta con una tarjeta (.entrenador-card) que incluye imagen, especialidad y una breve descripción.3. InteracciónFormulario de Contacto: Incluido en contactos.html, permite a los usuarios enviar consultas con campos obligatorios para Nombre, Email y Mensaje.Estilos en Contactos: Notablemente, la página contactos.html define sus propios estilos CSS dentro de la etiqueta <style>, aunque el header mantiene el estilo global.🛠️ Instalación y UsoEste es un proyecto estático, por lo que no requiere de instalación o servidores complejos.Clonar el repositorio (si está alojado en Git):Bashgit clone [URL-DEL-REPOSITORIO]
Abrir el proyecto:Simplemente haga doble clic en el archivo index.html en su navegador web preferido para comenzar a navegar por el sitio.👥 Equipo de DesarrolloEste proyecto sigue la metodología de un equipo ágil. El desarrollo y gestión del proyecto se habrían llevado a cabo utilizando herramientas como Trello (para sprints y backlog) y Git/GitHub (para control de versiones), en un entorno de Trabajo Colaborativo.