# Planos 3D de Aulas

Editor web para diseñar en **3D** espacios educativos (modelos genéricos) con mobiliario editable.
Depto. de Estudios Territoriales · SEGEY.

**App en vivo:** https://f1zero.github.io/planos-3d-aulas/

## Qué hace

- Plantillas por tipo de espacio con su mobiliario por defecto: **aula** (30 mesas y sillas + escritorio y silla del maestro + pizarrón), **biblioteca**, **aula de cómputo**, **laboratorio**, **área administrativa**, **área docente**, **baños**, **cocina/comedor** y **bodega**.
- Elige el tipo y el tamaño (salones estándar **8×8** o **6×8** m) y aparece el espacio con muros y mobiliario, en vista 360°.
- Edición: seleccionar, **mover** (arrastrar), **girar** (R / 90°), **duplicar** (D), **borrar** (Supr), agregar mobiliario desde el catálogo y ajustar medidas/posición.
- **Fichas / Galería**: una tarjeta por tipo de espacio que abre un ejemplo editable (para presentación).
- Exportar a **GLB** (Blender, visores web, etc.), imagen **PNG**, o guardar/abrir el proyecto en **JSON**.

## Uso

Abre `index.html` en un navegador moderno (Chrome/Edge). No requiere instalación ni servidor.
Requiere conexión a internet la primera vez para cargar la librería 3D (Three.js) desde CDN.

## Archivos

- `index.html` — editor 3D.
- `galeria.html` — fichas de los espacios (abre ejemplos genéricos editables).

## Tecnología

HTML + JavaScript (un solo archivo por página) y [Three.js](https://threejs.org/) (WebGL).
