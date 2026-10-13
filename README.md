# Asesoría Social RGA — sitio web

Sitio web de **Asesoría Social RGA**, equipo de Trabajadoras Sociales de la Región del Maule.
Es una sola página (`index.html`) con HTML, CSS y JavaScript en el mismo archivo, sin backend
ni dependencias que instalar.

**Publicado en:** https://www.asesoriasocialrga.cl (GitHub Pages, con HTTPS)

## Contenido

| Sección | Ancla | Qué muestra |
|---|---|---|
| Inicio | `#inicio` | Presentación |
| Servicios | `#servicios` | Servicios por ámbito: beneficios y trámites, educacional, salud y discapacidad, y judicial. También las modalidades de atención: presencial, virtual y visitas a domicilio |
| Cómo trabajamos | `#proceso` | Los 4 pasos: primer contacto, evaluación, visita o entrevista, y soluciones |
| Nosotros | `#nosotros` | Presentación del equipo |
| Contacto | `#contacto` | Correo, teléfono/WhatsApp e Instagram |

Además tiene un botón flotante de WhatsApp, un botón para volver arriba y un menú
desplegable para celulares.

## Archivos

```
index.html   Todo el sitio: estilos (<style>), contenido y scripts (<script>)
CNAME        Dominio propio para GitHub Pages: www.asesoriasocialrga.cl
```

- **Tipografías:** Google Fonts (Playfair Display y Cormorant Garamond, entre otras).
- **Colores:** variables CSS al inicio de `<style>` (`--cream`, `--sage`, `--rose`, `--ink`, etc.).
  Para cambiar la paleta, se editan ahí.
- **Scripts:** al final del archivo. Manejan el menú en celulares, el botón para volver
  arriba y las animaciones de aparición al hacer scroll.

## Cambios frecuentes

- **Teléfono / WhatsApp:** aparece en **3 lugares**: el enlace `tel:`, el WhatsApp de la
  sección Contacto y el botón flotante. Los dos enlaces `wa.me` llevan además un mensaje
  predefinido en el parámetro `text=`. Busca `56942710560` para encontrarlos todos.
- **Correo:** aparece en 2 lugares (busca `info@asesoriasocialrga.cl`).
- **Servicios:** cada ámbito es una tarjeta dentro de `<section id="servicios">`.
- **Año del pie de página:** está escrito a mano (`© 2026`).
- **Descripción para buscadores:** `<meta name="description">` al inicio del archivo.

## Publicar cambios

1. Para probar cambios, abre `index.html` en el navegador.
2. Haz commit y `git push` a `main`.
3. GitHub Pages publica la nueva versión en uno o dos minutos.

> Cada push a `main` **cambia el sitio público**. No borres ni modifiques `CNAME`: si falta,
> el dominio `www.asesoriasocialrga.cl` deja de apuntar al sitio.
