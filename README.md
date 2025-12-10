# Macroviajes.com

**Descubre los secretos DE MÉXICO Y EL MUNDO**

Un blog de turismo en español dedicado a explorar los rincones menos conocidos de México y el mundo. Descubre destinos auténticos, experiencias únicas y aventuras inolvidables.

## 🌎 Acerca del Blog

Macroviajes es tu guía definitiva para explorar los lugares más fascinantes y menos conocidos de México y el mundo. Nos enfocamos en:

- ✨ Destinos auténticos fuera de las rutas turísticas tradicionales
- 🏔️ Maravillas naturales poco conocidas
- 🎨 Experiencias culturales genuinas
- 🌿 Turismo responsable y sostenible
- 📸 Consejos prácticos para viajeros

## 🚀 Tecnología

Este blog está construido con [Jekyll](https://jekyllrb.com/), un generador de sitios estáticos.

### Requisitos

- Ruby 2.7+
- Jekyll 4.3+
- Bundler

### Instalación Local

```bash
# Instalar dependencias
bundle install

# Ejecutar servidor de desarrollo
bundle exec jekyll serve

# El sitio estará disponible en http://localhost:4000
```

### Despliegue

El sitio está configurado para desplegarse automáticamente con GitHub Pages a través de GitHub Actions.

## 📁 Estructura del Proyecto

```
macroviajes/
├── _config.yml          # Configuración de Jekyll
├── _layouts/            # Plantillas del sitio
│   ├── default.html     # Plantilla base
│   ├── home.html        # Página de inicio
│   └── post.html        # Plantilla de artículos
├── _includes/           # Componentes reutilizables
│   ├── header.html      # Encabezado
│   └── footer.html      # Pie de página
├── _posts/              # Artículos del blog
├── assets/              # Recursos estáticos
│   └── css/             # Hojas de estilo
├── index.md             # Página de inicio
├── blog.html            # Lista de artículos
├── sobre-nosotros.md    # Página "Sobre Nosotros"
└── contacto.md          # Página de contacto
```

## ✍️ Crear un Nuevo Artículo

1. Crea un archivo en `_posts/` con el formato: `YYYY-MM-DD-titulo-del-articulo.md`
2. Añade el encabezado YAML:

```yaml
---
layout: post
title: "Tu Título Aquí"
subtitle: "Un subtítulo descriptivo"
date: 2025-12-10
category: México
emoji: 🏝️
tags: [México, Playa, Naturaleza]
excerpt: "Un resumen breve del artículo..."
---
```

3. Escribe tu contenido en Markdown

## 🎨 Personalización

### Colores del Tema

Edita las variables CSS en `assets/css/style.css`:

```css
:root {
  --primary-color: #2c5f2d;      /* Verde principal */
  --secondary-color: #97bc62;     /* Verde claro */
  --accent-color: #d4a574;        /* Dorado/arena */
  --text-dark: #2d3436;           /* Texto oscuro */
  --text-light: #636e72;          /* Texto claro */
}
```

### Configuración del Sitio

Edita `_config.yml` para cambiar:
- Título y descripción
- Información del autor
- URLs y rutas
- Plugins y configuraciones

## 📝 Licencia

© 2025 Macroviajes.com - Todos los derechos reservados

## 🤝 Contribuir

¿Tienes un destino secreto que compartir? ¡Nos encantaría saber de ti!

Contacto: info@macroviajes.com

---

**¡La aventura espera!** 🌍✈️
