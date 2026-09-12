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

## Datos de contacto (ya configurados)

- **WhatsApp / Teléfono**: +1 (239) 877-8232 (enlaces `wa.me/12398778232` y `tel:+12398778232`).
- **Correo**: firstmarblefl@gmail.com (botón de correo y destino del formulario).
- **Zona de servicio**: suroeste de Florida (Fort Myers, Cape Coral, Naples, Bonita Springs, Estero).

## Pendientes / por revisar

1. **Cifras de confianza**: los números de la barra de estadísticas (`+150` proyectos, `+10` años, `100%`, `5.0`) son valores de referencia. Verifícalos y ajústalos a los datos reales del negocio en la sección `STATS / TRUST BAR` de `index.html`.
2. **Garantía**: la página indica "hasta 1 año de garantía en la mano de obra" (secciones `GARANTÍAS` y FAQ). Ajusta el plazo si el real es distinto.
3. **Marcas de materiales**: los logos de la sección `MARCAS` son nombres de referencia (Daltile, Porcelanosa, MSI, etc.). Confírmalos o reemplázalos por las marcas reales — idealmente con imágenes de logo en `assets/img/`.
4. **Horario de atención**: Lun–Vie 8:00–18:00, Sáb 9:00–14:00, Dom cerrado. Ajústalo si tu horario real es otro.
5. **Fotos reales de proyectos**: reemplazar las fotos de stock en `assets/img/` con fotos reales de trabajos terminados. El comparador Antes/Después usa dos fotos de referencia (`formato-grande.jpg` y `marmol-dorado.jpg`); lo ideal es una misma toma antes y después de la remodelación.
6. **Formulario de contacto**: hoy usa un enlace `mailto:` (abre el correo del visitante). Si quieres que llegue directo a firstmarblefl@gmail.com o a un CRM sin depender del cliente de correo del visitante, se puede conectar a un servicio de formularios.

## Publicar en GitHub Pages

Mismo proceso que MeryanShop: crear repositorio en GitHub, subir estos archivos, y activar Pages en Settings → Pages.
