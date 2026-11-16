# AXIS-Z · Biología IB

Herramientas gratuitas para preparar los exámenes de Biología del IB (programa con primera evaluación en 2025, NM y NS, español e inglés).

| Carpeta | Herramienta | Qué hace |
|---|---|---|
| `artemis/` | **Artemis** | Trainer completo: opción múltiple, preguntas escritas, tarjetas con repaso espaciado, simulacros con nota estimada, cálculos, diagramas y juegos. |
| `examinador/` | **Examinador** | Corrector de la Prueba 1B y la Prueba 2: revisión instantánea con el esquema y mensaje listo para una corrección completa con IA. |

`index.html` es la página de inicio que enlaza ambas.

## Publicar en GitHub Pages
1. Sube todo el contenido de esta carpeta (incluido `.nojekyll`) a la raíz de un repositorio.
2. En el repositorio: **Settings → Pages → Build and deployment → Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos el sitio estará en `https://<usuario>.github.io/<repositorio>/`.

## Notas
- Son páginas estáticas: no hay servidor ni claves de API, y las respuestas de los alumnos no salen de su navegador.
- El progreso se guarda en el navegador de cada alumno (localStorage); si borra los datos del navegador, se pierde.
- Artemis carga sus fuentes desde Google Fonts; sin internet usa las fuentes del sistema.
- La corrección automática del Examinador es una estimación por palabras clave, no una nota oficial.

«IB» e «International Baccalaureate» son marcas de la Organización del Bachillerato Internacional, que no ha producido, avalado ni se ha afiliado a estas herramientas.
