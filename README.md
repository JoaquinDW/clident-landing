# CliDent Corrientes — propuesta de rediseño

Landing estática con HTML, CSS y JavaScript, tipografías y fotografías locales. Dirección gráfica: tipografía Outfit de gran escala, azul profundo, naranja y superficies claras. Diseñada como una propuesta independiente para CliDent.

## Abrir localmente

`python3 -m http.server 4174 --directory dist`, luego http://localhost:4174.

## Funciones

- Doce tratamientos disponibles sin JavaScript, con información desplegable.
- Filtros por categoría de tratamiento y preselección al solicitar consulta.
- Galería de cinco fotografías de las instalaciones.
- Búsqueda de obras sociales que reconoce acentos y mayúsculas.
- Formulario validado que prepara una consulta por WhatsApp, sin almacenarla ni enviarla automáticamente.
- Menú móvil, enlaces de teléfono, ubicación y redes, foco visible y reducción de movimiento.

## Vercel

Importar desde la raíz del repositorio. `vercel.json` configura framework Other, sin instalación ni compilación, con Output Directory `dist`. No se necesita `package.json`.

## Fuentes del contenido

Información comercial, tratamientos, fotografías, logo, dirección y WhatsApp: https://www.clidentcorrientes.com.ar/, consultado el 13 de octubre de 2026. Ver `PRODUCT.md` y `ASSETS.md`. Se utilizó el número del encabezado y de los enlaces oficiales de WhatsApp (3794624642), que difiere de un número escrito en el pie del sitio original.

No se inventaron testimonios, nombres de especialistas, resultados clínicos, horarios ni tiempos de respuesta. Confirmar coberturas, tratamientos y contactos con la clínica antes de un lanzamiento público en su dominio.

La publicación en Sites es una propuesta privada independiente del dominio original. Las fotografías son las publicadas por la propia clínica; no hay imágenes generadas de pacientes o profesionales.

## Validación realizada

Revisión visual en escritorio (1440 px), móvil (390 px) y vista del usuario. Sin desbordamiento horizontal en móvil. Probados menú, filtros, despliegue de tratamientos, preselección de consulta, galería, búsqueda y caso sin coincidencias, validación de nombre y preparación del mensaje de WhatsApp. Se verificaron HTML, anclas, recursos locales y sintaxis JavaScript. Contraste comprobado de 4.9:1 o más en los pares de colores principales de texto.
