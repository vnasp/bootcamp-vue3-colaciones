# Colaciones Saludables

Proyecto desarrollado como desafío del Bootcamp Frontend Developer de Talento Digital para Chile. Sitio web multipágina para una tienda de colaciones y alimentos saludables con navegación por rutas, catálogo de productos y página de contacto.

> **Nota:** Este es un proyecto académico, no un sitio comercial real.

## Vista previa

[Ver en GitHub Pages](https://vnasp.github.io/bootcamp-vue3-colaciones/)

## Funcionalidades

- Navegación entre páginas con Vue Router
- Página de inicio con catálogo de productos en tarjetas
- Vista de detalle de productos con props via router
- Página de contacto
- Navbar responsive con Bootstrap
- Componentes reutilizables (Navbar, Footer, Card, MediosPago)
- Formateo de precios en CLP

## Tecnologías

- Vue.js 3
- Vue Router 4
- Bootstrap 5 (CDN)

## Estructura

```
src/
├── App.vue              → Layout principal con Navbar, Router View y Footer
├── main.js              → Punto de entrada
├── style.css            → Estilos globales
├── assets/img/          → Imágenes de productos y logos
├── components/
│   ├── BackToHome.vue   → Botón para volver al inicio
│   ├── Card.vue         → Tarjeta de producto
│   ├── Footer.vue       → Pie de página
│   ├── MediosPago.vue   → Sección de medios de pago
│   └── Navbar.vue       → Barra de navegación con router-link
├── router/
│   └── index.js         → Configuración de rutas
└── views/
    ├── ContactView.vue  → Página de contacto
    ├── HomeView.vue     → Página de inicio
    └── ProductsView.vue → Vista de productos con props
```
