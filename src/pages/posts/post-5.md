---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Mi primer día con Astro'
pubDate: 2026-09-25
description: 'Cómo construí y publiqué mi primer sitio web con Astro en un solo día.'
author: 'Moises'
image:
  url: 'https://docs.astro.build/default-og-image.png'
  alt: 'La palabra astro sobre una ilustración de planetas y estrellas.'
tags: ["astro", "aprendiendo", "primeros pasos"]
---
Hoy empecé el tutorial oficial de Astro y, para mi sorpresa, al final del día ya tenía un sitio publicado en internet.

## Lo que logré

1. **Preparar mi entorno**: instalé Node.js (v26), VS Code y creé mi primer proyecto con `npm create astro@latest`.
2. **Publicar en internet**: subí mi código a GitHub y conecté el repositorio con Netlify. Ahora cada vez que hago *push*, mi sitio se actualiza solo.
3. **Crear páginas**: hice las páginas Home, About y Blog, y aprendí que cualquier archivo en `src/pages/` se convierte en una página.
4. **Usar componentes**: separé el menú, el header y el footer en componentes reutilizables.
5. **Layouts**: creé un layout base y otro para los posts, para no repetir el mismo código en cada página.

## Los problemas que resolví

- **PowerShell no me dejaba correr `npm`** porque los scripts estaban deshabilitados. La solución fue usar `npm.cmd run dev`.
- **Git no me dejaba hacer commit** hasta que configuré mi nombre y correo con `git config`.
- **Astro no encontraba mi `global.css`** porque había creado la carpeta `styles` dentro de `pages` en lugar de dentro de `src`.

Cada error me enseñó algo nuevo sobre cómo está organizado un proyecto.

## Lo que sigue

Voy a terminar el tutorial: páginas de etiquetas, un feed RSS y, más adelante, componentes interactivos. Puedes ver mi código en [mi GitHub](https://github.com/XDAura67).
