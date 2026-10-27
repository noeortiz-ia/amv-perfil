# Alejandro Mendoza Victorica — sitio de marca personal

Sitio de una página para el perfil profesional de Alejandro Mendoza Victorica.
HTML y CSS en un solo archivo, sin dependencias de compilación. Las animaciones
corren con GSAP y ScrollTrigger desde CDN.

## Contenido

- `index.html` — sitio completo (estructura, estilos y animaciones).
- `alejandro-mendoza.webp` — retrato, 372×466, recortado a 4:5 desde el original.

## Estructura de la página

1. **Portada** — nombre, posicionamiento y retrato enmarcado.
2. **Perfil** — trayectoria en prosa y tres indicadores.
3. **En qué trabajo** — seis frentes: datos, analítica, automatización,
   inteligencia artificial aplicada, atención y dirección comercial.
4. **Cómo trabajo** — método en cuatro pasos.
5. **Trayectoria** — línea de tiempo y países de operación.
6. **Contacto** — enlace directo a LinkedIn.

## Detalles técnicos

- Navegación con índice lateral que marca la sección activa.
- Revelado por scroll, contadores animados y línea de tiempo que se dibuja.
- Retrato con inclinación 3D al pasar el cursor y parallax al desplazar.
- Respeta `prefers-reduced-motion`: sin animaciones cuando el sistema lo pide.
- Tipografías: Satoshi y General Sans.
- Paleta: hueso `#f6f3ed`, verde petróleo `#0f4c46`, tinta `#12100c`.

## Publicación

Sitio estático: cualquier servidor que entregue archivos lo publica sin
configuración adicional. La raíz del repositorio es la raíz del sitio.
