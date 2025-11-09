# 🐺 Husky Digital — Marketing para Negocios Locales

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success)](https://elias-abdala02.github.io/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Landing page moderna y completamente interactiva para **Husky Digital**, una agencia de marketing digital especializada en restaurantes, cafés, bares y tiendas locales.

## 🌐 Demo en Vivo

**[Ver sitio web →](https://elias-abdala02.github.io/)**

## ✨ Características

### 🎨 Diseño y Animaciones
- **Esquema de colores claro** con tonos cyan/azul profesionales
- **Smooth scroll** para navegación fluida
- **AOS (Animate On Scroll)** para animaciones al hacer scroll
- **Parallax scrolling** con múltiples capas
- **Morphing SVG shapes** en el fondo con animaciones orgánicas
- **Efecto ripple** en todos los botones principales
- **Tarjeta interactiva** con gráfica animada de crecimiento
- **Gradiente animado** en texto principal

### 🎯 Secciones
1. **Hero** - Con tarjeta interactiva que muestra estadísticas al hacer hover
2. **Servicios** - 3 tarjetas animadas (Landing express, Anuncios locales, Marca & redes)
3. **Demo Python** - Calculadora de envío interactiva usando Pyodide
4. **Contacto** - Información de correo y WhatsApp

### 🛠️ Tecnologías Utilizadas

#### Open Source Stack
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS via CDN
- **[Three.js](https://threejs.org/)** - Gráficos 3D para el fondo del hero
- **[Pyodide](https://pyodide.org/)** - Python en el navegador para la demo interactiva
- **[AOS](https://michalsnik.github.io/aos/)** - Animate On Scroll library

#### Características Técnicas
- ✅ 100% HTML/CSS/JavaScript vanilla
- ✅ No requiere compilación ni build
- ✅ Responsive design (mobile-first)
- ✅ Optimizado para GitHub Pages
- ✅ Sin dependencias de servidor

## 🚀 Despliegue

Este sitio está desplegado automáticamente en **GitHub Pages**.

### Configuración de GitHub Pages
1. Ve a **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** → **/root**
4. Save

El sitio se actualiza automáticamente con cada push a la rama `main`.

## 📁 Estructura del Proyecto

```
.
├── index.html          # Página principal (todo en uno)
└── README.md          # Este archivo
```

## 🎯 Características Interactivas

### Tarjeta Hero Interactiva
- **Estado normal**: Muestra estrella con mensaje "Hover aquí para ver resultados"
- **Al hacer hover**: 
  - Gráfica de barras animada con crecimiento progresivo
  - Estadísticas: +200% clientes, 48h implementación, 0% costos ocultos
  - Efecto de elevación y glow

### Demo de Python
- Ejecuta Python directamente en el navegador
- Calcula costo de envío basado en distancia y ticket
- Interfaz con inputs responsivos y feedback en tiempo real

### Efectos Visuales
- **Shimmer**: Destello que recorre elementos periódicamente
- **Float**: Elementos que suben y bajan suavemente
- **Pulse**: Anillo expansivo tipo radar
- **Morphing**: Formas que cambian continuamente

## 🎨 Paleta de Colores

```css
/* Principales */
Cyan 500:    #06b6d4
Cyan 600:    #0284c7
Blue 500:    #3b82f6

/* Fondos */
Gray 50:     #f9fafb
White:       #ffffff

/* Textos */
Slate 900:   #0f172a
Slate 600:   #475569
Slate 500:   #64748b
```

## 💻 Desarrollo Local

Para ver el sitio localmente, simplemente abre `index.html` en tu navegador:

```bash
# Opción 1: Abrir directamente
open index.html

# Opción 2: Con servidor local (recomendado)
python3 -m http.server 8000
# Luego visita: http://localhost:8000
```

## 📝 Personalización

### Cambiar información de contacto
Busca en `index.html`:
```html
<a href="mailto:eabdalaa@outlook.com">
<a href="https://wa.me/529836?text=Hola%20Husky%20Digital">
```

### Modificar colores
Edita las clases de Tailwind o los estilos CSS personalizados en `<style>`.

### Ajustar animaciones
Modifica los `@keyframes` en la sección de estilos.

## 🤝 Contribuciones

Este es un proyecto personal, pero las sugerencias son bienvenidas.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

## 👤 Autor

**Elias Abdala**
- GitHub: [@Elias-Abdala02](https://github.com/Elias-Abdala02)
- Email: eabdalaa@outlook.com

---

Hecho con 💙 usando tecnologías open-source
