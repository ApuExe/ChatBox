# ChatBox

ChatBox es una landing page interactiva desarrollada con tecnologías web nativas, enfocada en presentar una interfaz moderna, visualmente atractiva y con animaciones suaves.

El proyecto utiliza HTML, CSS y JavaScript puro, sin depender de frameworks de frontend.

---

## Demo

Puedes visualizar el proyecto desde GitHub Pages:

[Ver ChatBox](https://apuexe.github.io/ChatBox/)

---

## Características

- Diseño moderno y visual.
- Landing page dividida en diferentes secciones.
- Animaciones durante el desplazamiento.
- Efectos visuales mediante JavaScript.
- Uso de imágenes optimizadas en formato WebP.
- Organización modular de estilos CSS.
- Estructura simple y fácil de mantener.
- Compatible con navegadores web modernos.
- Preparado para despliegue mediante GitHub Pages.

---

## Tecnologías utilizadas

El proyecto fue construido utilizando:

- HTML5
- CSS3
- JavaScript
- AOS / animaciones basadas en scroll
- Git
- GitHub
- GitHub Pages

No requiere frameworks como React, Vue o Angular.

---

## Estructura del proyecto

```text
ChatBox/
│
├── CSS/
│   ├── ClasesGenerales.css
│   ├── Colores.css
│   ├── FirstSection.css
│   ├── SecondSection.css
│   ├── ThirdSection.css
│   ├── FourthSection.css
│   ├── FifthSection.css
│   ├── SixthSection.css
│   ├── SeventhSection.css
│   ├── ReajustadorDeMargenes.css
│   └── mainStyle.css
│
├── JS/
│   ├── aos.js
│   ├── background-apply.js
│   ├── mainScript.js
│   └── observer.js
│
├── RECURSOS/
│   ├── ChatBoxPics/
│   ├── Iconos/
│   └── Logos/
│
├── .vscode/
│   └── settings.json
│
├── index.html
└── README.md

Funcionamiento

La aplicación está construida como una página web estática.

El archivo principal es:

index.html

Desde este archivo se cargan los diferentes estilos CSS, scripts JavaScript e imágenes utilizadas por la interfaz.

Los estilos están separados por secciones con el objetivo de mantener una estructura más organizada y facilitar futuras modificaciones.

Instalación
1. Clonar el repositorio
git clone https://github.com/ApuExe/ChatBox.git
2. Entrar al proyecto
cd ChatBox
3. Ejecutar la aplicación

Puedes abrir directamente:

index.html

en tu navegador.

También puedes utilizar una extensión como Live Server en Visual Studio Code.

Ejecución con Visual Studio Code

Si utilizas Visual Studio Code:

Abre la carpeta del proyecto.
Instala la extensión Live Server.
Abre index.html.
Haz clic derecho.
Selecciona:
Open with Live Server

La página se abrirá automáticamente en el navegador.

Arquitectura CSS

Los estilos fueron separados en distintos archivos para evitar concentrar todo el diseño en una sola hoja de estilos.

Por ejemplo:

FirstSection.css
SecondSection.css
ThirdSection.css
FourthSection.css
...

Esto permite trabajar individualmente sobre cada sección de la landing page.

También existen archivos destinados a estilos globales:

mainStyle.css
ClasesGenerales.css
Colores.css
ReajustadorDeMargenes.css
JavaScript

La lógica del proyecto se encuentra dentro de:

JS/
mainScript.js

Contiene parte de la lógica principal de la interfaz.

observer.js

Gestiona comportamientos relacionados con elementos visibles dentro del viewport.

background-apply.js

Controla determinados efectos visuales y fondos de la interfaz.

aos.js

Gestiona animaciones asociadas al desplazamiento de la página.

Recursos gráficos

Los recursos visuales se encuentran dentro de:

RECURSOS/

La carpeta está organizada principalmente en:

ChatBoxPics/
Iconos/
Logos/

Se utilizan imágenes WebP para reducir el peso de los recursos manteniendo una buena calidad visual.

Objetivos del proyecto

El proyecto permite practicar y aplicar conceptos relacionados con:

Maquetación web.
HTML semántico.
Arquitectura CSS.
Organización modular de estilos.
Manipulación del DOM.
Animaciones web.
Intersection Observer.
Responsive design.
Optimización de recursos gráficos.
Publicación de sitios estáticos mediante GitHub Pages.
Mejoras futuras

Entre las mejoras previstas para el proyecto se encuentran:

Mejorar completamente la responsividad.
Optimizar la visualización en dispositivos móviles.
Revisar los breakpoints del diseño.
Mejorar accesibilidad.
Optimizar contraste y legibilidad.
Reducir dependencias de dimensiones fijas.
Mejorar las animaciones.
Añadir soporte para prefers-reduced-motion.
Optimizar rendimiento.
Mejorar estructura semántica.
Implementar mejores estados interactivos.
Realizar pruebas en diferentes navegadores.
Optimizar Core Web Vitals.
Responsive Design

El objetivo es que ChatBox pueda adaptarse correctamente a diferentes tamaños de pantalla:

320px
480px
768px
1024px
1440px+

Esto incluye:

teléfonos móviles;
tablets;
laptops;
monitores de escritorio;
pantallas de alta resolución.
Compatibilidad

El proyecto está pensado para funcionar correctamente en navegadores modernos como:

Google Chrome
Microsoft Edge
Mozilla Firefox
Safari
Opera
Despliegue

El proyecto puede desplegarse directamente mediante GitHub Pages.

En GitHub:

Settings
→ Pages
→ Deploy from a branch
→ main
→ /root

La aplicación quedará disponible aproximadamente en:

https://apuexe.github.io/ChatBox/
Autor

ApuExe

GitHub:

github.com/ApuExe

Estado del proyecto

Actualmente el proyecto se encuentra en proceso de revisión y mejora, principalmente en:

responsividad;
experiencia de usuario;
animaciones;
accesibilidad;
mantenibilidad del código;
optimización visual.
Licencia

Este proyecto se distribuye bajo la licencia MIT.
