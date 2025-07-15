# 🚘 Taller AutoExpert - Sitio Web Corporativo

**Taller AutoExpert** es un sitio web profesional desarrollado para representar a un taller mecánico moderno. Incluye catálogos de productos, promociones, contacto y contenido informativo, todo con un diseño responsive, limpio y centrado en la experiencia del usuario.

## 🧾 Tabla de contenido

- [📁 Estructura del proyecto](#-estructura-del-proyecto)
- [🌐 Páginas del sitio](#-páginas-del-sitio)
- [🛠️ Tecnologías utilizadas](#️-tecnologías-utilizadas)
- [📱 Diseño responsive](#-diseño-responsive)
- [⚙️ Optimización y rendimiento](#️-optimización-y-rendimiento)
- [🚀 Futuras mejoras](#-futuras-mejoras)
- [👨‍💻 Autor](#-autor)

---

## 📁 Estructura del proyecto

📦 taller-autoexpert/
├── index.html
├── ofertas.html
├── quienesSomos.html
├── contacto.html
├── accesorios.html
├── aceites.html
├── amortiguadores.html
├── baterias.html
├── frenos.html
├── neumaticos.html
├── img/
│   ├── michelin1.webp
│   ├── bridgestone1.webp
│   ├── bateriaBosch.webp
│   ├── frenosBrembo.webp
│   ├── aceiteCastrol.webp
│   └── ... (otras imágenes optimizadas)

---

## 🌐 Páginas del sitio

| Página HTML              | Descripción                                                                                  |
|--------------------------|----------------------------------------------------------------------------------------------|
| `index.html`             | Página principal con presentación del taller y navegación global.                           |
| `ofertas.html`           | Sección de promociones con **temporizador** de oferta destacada.                            |
| `quienesSomos.html`      | Información sobre el equipo, experiencia, valores y visión del taller.                      |
| `contacto.html`          | Formulario de contacto funcional + **Google Maps embebido**.                                |
| `accesorios.html`        | Catálogo de accesorios automovilísticos (tapicería, portabicicletas, alfombrillas, etc.).   |
| `aceites.html`           | Sección de aceites de motor: marcas, especificaciones y precios.                            |
| `amortiguadores.html`    | Catálogo visual de amortiguadores, con tarjetas interactivas y descripciones técnicas.      |
| `baterias.html`          | Página dedicada a baterías automotrices, con fichas técnicas y precios.                     |
| `frenos.html`            | Sección de frenos: discos, pastillas, kits completos para diferentes vehículos.             |
| `neumaticos.html`        | Catálogo profesional de neumáticos con marcas premium, precios, descripciones y valoraciones.|

---

## 🛠️ Tecnologías utilizadas

- **HTML5**: Marcado semántico y moderno.
- **Tailwind CSS**: Utilidad CSS para diseño responsive, limpio y con alto rendimiento.
- **JavaScript**: Para lógica del temporizador de cuenta regresiva (`ofertas.html`).
- **Imágenes `.webp`**: Imágenes comprimidas y optimizadas para carga rápida.

---

## 📱 Diseño responsive

Todo el sitio está construido bajo un diseño adaptable (`responsive`) para garantizar compatibilidad y legibilidad en:

- 📱 Smartphones
- 💻 Laptops
- 🖥️ Escritorios
- 📟 Tablets

Uso intensivo de `grid`, `flexbox`, media queries y clases Tailwind adaptativas como `sm:`, `lg:`, `hover:`.

---

## ⚙️ Optimización y rendimiento

- **Lazy loading** (`loading="lazy"`) en todas las imágenes.
- **Formato WebP** para menor peso y mayor eficiencia.
- **Separación visual y estructural** de los recursos (HTML en raíz, imágenes en `/img/`).
- **Reutilización de componentes visuales** como navegación, footer y tarjetas de producto.

---

## 🚀 Futuras mejoras

- [ ] Backend para gestión de citas y reservas.
- [ ] Panel de administración para actualizar el catálogo desde base de datos.
- [ ] Mejoras SEO: etiquetas `meta`, OpenGraph, `aria-labels`, sitemap.
- [ ] Internacionalización (i18n): versión en inglés y otros idiomas.
- [ ] Pruebas de accesibilidad (a11y) con Lighthouse o WAVE.

---

## 👨‍💻 Autor

Desarrollado por bogdanmstefan.  
Proyecto académico / personal para demostrar habilidades en frontend, diseño UX/UI y desarrollo web estático.

---

© BGD 2025 **Taller AutoExpert**. Todos los derechos reservados.
