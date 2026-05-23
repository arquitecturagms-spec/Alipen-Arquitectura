# Alipen.cl — Arquitectura & Taller IA

Sitio web oficial de **Alipen**, un estudio vanguardista enfocado en la fusión entre la arquitectura tradicional, el diseño generativo y flujos de trabajo avanzados potenciados por Inteligencia Artificial.

## 🚀 Características del Sitio
- **Diseño Moderno e Inmersivo:** Interfaz oscura optimizada con fuentes elegantes (*Syne* y *Outfit*) de Google Fonts.
- **Portafolio Automatizado:** Cuadrícula responsiva que se adapta a computadoras y dispositivos móviles.
- **Taller IA (Laboratorio Digital):** Carrusel de imágenes automatizado mediante JavaScript nativo para mostrar diseños espaciales y conceptuales.

---

## 📂 Estructura del Repositorio

Para asegurar el correcto funcionamiento del dominio en **GitHub Pages**, los archivos deben organizarse de la siguiente manera:

```text
├── index.html       # Código fuente principal (HTML, CSS y JS)
├── CNAME            # Configuración del dominio personalizado (alipen.cl)
├── readme.md        # Este archivo con la documentación
├── obra1.jpg        # Imagen del proyecto residencial 1
├── obra2.jpg        # Imagen del proyecto comercial 2
├── ia1.jpg          # Diapositiva 1 del carrusel del taller
├── ia2.jpg          # Diapositiva 2 del carrusel del taller
└── ia3.jpg          # Diapositiva 3 del carrusel del taller
```

---

## 🛠️ Notas de Mantenimiento e Imágenes

### ⚠️ Regla de Oro para las Imágenes
GitHub es **estrictamente sensible** a las mayúsculas y minúsculas en las rutas de los archivos. 

Si en el archivo `index.html` el código busca `obra1.jpg`, el archivo en el repositorio **debe** llamarse exactamente igual (en minúsculas y con extensión `.jpg`). Si se sube como `Obra1.JPG` u `obra1.png`, el navegador lanzará un error y no la cargará.

### Actualización de Contenido
- **Para añadir más obras:** Abre el archivo `index.html`, busca la sección `#portafolio` y duplica el bloque de código `<div class="portfolio-card">` cambiando la ruta de la imagen y los textos.
- **Para cambiar el tiempo del carrusel:** En la etiqueta `<script>` al final de `index.html`, modifica el valor de `slideInterval` (definido por defecto en `4000` milisegundos o 4 segundos).

---
*Desarrollado de forma limpia, sin frameworks y optimizado para una carga ultra rápida.*
