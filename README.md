# 🏔️ Fiambalá 2026

Landing page interactiva para el viaje grupal a **Fiambalá, Catamarca** — 4 días, 12 personas, 3 autos.

**Jueves 9 a Domingo 12 de julio de 2026**

👉 [fiambala2026.vercel.app](https://fiambala2026.vercel.app/) · [juanruiz-cv.github.io/fiambala-2026](https://juanruiz-cv.github.io/fiambala-2026/)

---

## ✨ Features

- 🕒 **Countdown** contextual al día del viaje
- 🌤️ **Clima** en vivo con pronóstico para los días del viaje (Open-Meteo) + temperatura actual
- 🗺️ **Mapa interactivo** con ruta San Juan → Fiambalá (Leaflet + OSRM)
- 🚗 **Distribución de autos** con pasajeros por vehículo
- ✅ **Checklist interactiva** por categoría con progreso
- 📸 **Galería de fotos**
- 🌙 **Modo oscuro** persistente en localStorage
- 📱 **Responsive** mobile-first, funciona offline desde archivo local
- 🎬 **Splash screen + Welcome modal**

## 🛠️ Stack

- Una sola página: `index.html` con CSS y JS embebidos
- **Fuentes:** Playfair Display + Inter (Google Fonts)
- **Iconos:** Font Awesome 6.5.1
- **Mapa:** Leaflet 1.9.4 + OSM + OSRM
- **Clima:** Open-Meteo API (fetch, sin JSONP)
- Sin frameworks, sin build tools, sin SSR

## 🚀 Uso

Abrí `index.html` en cualquier navegador o visitá el sitio en [Vercel](https://fiambala2026.vercel.app/) o [GitHub Pages](https://juanruiz-cv.github.io/fiambala-2026/).

Para desarrollo local, no necesita servidor — abrí el archivo directo.

## 📁 Estructura

```
📁 viaje/
├── index.html    # Todo el sitio (single-file)
└── README.md
```

## 🧑‍🤝‍🧑

Viaje organizado por el grupo — cada uno maneja sus consumibles y combustible.
