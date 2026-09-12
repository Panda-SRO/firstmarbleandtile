# First Marble & Tile Inc

Página web (ES/EN) para First Marble & Tile Inc — instalación de mármol, cerámica, encimeras y remodelaciones.

## Estructura

```
index.html          sitio completo (HTML + CSS + JS)
assets/img/          fotos de materiales (mármol blanco, negro, dorado, cerámica subway, mosaico, formato grande)
```

Las fotos en `assets/img/` son de stock (Unsplash, uso libre) como referencia de catálogo, mientras se agregan fotos reales de proyectos terminados.

## Cómo ver el sitio localmente

```bash
start index.html
```

## Secciones

- **Hero** + barra de estadísticas de confianza (proyectos, años, satisfacción).
- **Servicios** y **Proceso de trabajo** (Consulta → Cotización → Instalación → Entrega).
- **Materiales** (catálogo) y comparador **Antes / Después** con control deslizante.
- **Marcas** de materiales, **Nosotros**, **Garantías y certificaciones**.
- **Preguntas frecuentes (FAQ)**, **Contacto** con horario de atención y formulario.
- Animaciones sutiles al hacer scroll (respetan `prefers-reduced-motion`).

## Pendientes

1. **Datos de contacto reales**: el sitio tiene WhatsApp, teléfono y correo marcados como "pendiente por confirmar" en la sección de contacto y en el footer. Busca `pendiente por confirmar` / `to be confirmed` en `index.html` y reemplaza con los datos reales, además del número en `wa.me/10000000000` y `tel:+10000000000`.
2. **Cifras de confianza**: los números de la barra de estadísticas (`+150` proyectos, `+10` años, `5.0`) son de referencia. Ajústalos a los valores reales del negocio en la sección `STATS / TRUST BAR` de `index.html`.
3. **Marcas de materiales**: los logos de la sección `MARCAS` son nombres de referencia (Daltile, Porcelanosa, MSI, etc.). Reemplázalos por las marcas reales con las que trabajas — idealmente con imágenes de logo en `assets/img/`.
4. **Garantía y horario**: el plazo de garantía y el horario de atención están marcados como "pendiente por confirmar". Actualízalos con los datos reales (secciones `GARANTÍAS` y `Horario de atención`).
5. **Zonas de cobertura**: la FAQ menciona zonas "pendientes por confirmar"; indica las áreas reales que cubres.
6. **Fotos reales de proyectos**: reemplazar las fotos de stock en `assets/img/` con fotos reales de trabajos terminados. El comparador Antes/Después usa dos fotos de referencia (`formato-grande.jpg` y `marmol-dorado.jpg`); lo ideal es una misma toma antes y después de la remodelación.
7. **Formulario de contacto**: hoy usa un enlace `mailto:` como método simple. Si se quiere que llegue a un correo o CRM sin depender del cliente de correo del visitante, se puede conectar a un servicio de formularios.

## Publicar en GitHub Pages

Mismo proceso que MeryanShop: crear repositorio en GitHub, subir estos archivos, y activar Pages en Settings → Pages.
