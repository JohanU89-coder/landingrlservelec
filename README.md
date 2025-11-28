# landingrlservelec

❄️ R&L Servelec - Landing Page Corporativa
Descripción: Landing page moderna y de alto rendimiento diseñada para R&L Servelec, empresa peruana especializada en climatización (Aire Acondicionado). Enfocada en la conversión de leads, velocidad de carga y experiencia de usuario (UX) con animaciones suaves.

🚀 Características Principales
Diseño Responsive (Mobile First): Se adapta perfectamente a celulares, tablets y escritorio.

Animaciones de Alto Rendimiento:

Efecto de niebla/aire frío (CSS puro).

Efecto de escritura (Typewriter) en el hero.

Aparición suave al hacer scroll (AOS Library).

Interacción de Usuario:

Contadores estadísticos animados.

Scroll horizontal visual para "Antes y Después".

Botones con micro-interacciones.

Integración de Contacto: Enlace directo a WhatsApp API preconfigurado.

Tecnología Ligera: No requiere compiladores complejos ni Node.js para funcionar.

🛠️ Stack Tecnológico
El proyecto está construido utilizando tecnologías estándar y modernas mediante CDNs para facilitar la implementación rápida:

HTML5: Estructura semántica y optimizada para SEO.

Tailwind CSS (CDN): Framework de utilidades para el diseño visual.

Vanilla JavaScript (ES6+): Lógica para el menú, contadores y efectos.

Librerías Externas:

AOS (Animate On Scroll): Para las transiciones de entrada.

Phosphor Icons: Iconografía técnica y nítida.

📂 Estructura del Proyecto
Bash

/
├── index.html # Archivo principal con todo el código (HTML, CSS Config, JS)
├── README.md # Documentación del proyecto
└── assets/ # (Opcional) Carpeta para guardar imágenes locales si dejas de usar Unsplash
⚙️ Instalación y Uso Local
Este proyecto no requiere instalación de dependencias (npm/yarn) gracias al uso de scripts CDN.

Clonar o Descargar: Descarga el archivo index.html en una carpeta de tu computadora.

Ejecutar: Haz doble clic en index.html para abrirlo en tu navegador favorito (Chrome, Edge, Firefox).

Edición: Abre el archivo con cualquier editor de código (VS Code, Sublime Text, Notepad++).

🎨 Guía de Personalización
Para adaptar la plantilla a la empresa real, busca y modifica las siguientes secciones en el código:

1. Cambiar Número de WhatsApp
   Busca la línea con wa.me y reemplaza el número ficticio con el real (incluyendo el código de país 51):

HTML

<a href="https://wa.me/51999999999"...> 2. Cambiar Colores de Marca
En la sección <script> del head, puedes modificar la configuración de Tailwind:

JavaScript

colors: {
brand: {
light: '#5CACFF',
DEFAULT: '#1E90FF', // <--- Cambia este HEX por el color principal de la marca
dark: '#0056b3',
},
// ...
} 3. Reemplazar Imágenes
Actualmente se usan imágenes de stock de Unsplash. Para usar fotos reales:

Guarda tus fotos en una carpeta img o assets.

Busca la etiqueta <img src="...">.

Cambia la ruta:

De: https://images.unsplash.com/...

A: ./assets/mi-foto-real.jpg

🚢 Despliegue (Deploy)
Al ser un sitio estático (solo HTML/JS/CSS), tienes opciones gratuitas y muy rápidas:

Opción A: Netlify Drop (Recomendada)
Entra a app.netlify.com/drop.

Arrastra la carpeta que contiene tu index.html.

¡Listo! Tu sitio estará online en segundos con HTTPS incluido.

Opción B: Hosting Tradicional (cPanel)
Sube el archivo index.html a la carpeta public_html de tu servidor mediante FTP o el Administrador de Archivos.

📄 Licencia y Créditos
Desarrollado para: R&L Servelec.

Iconos: Phosphor Icons (Licencia MIT).

Imágenes Demo: Unsplash (Licencia libre para uso comercial).
