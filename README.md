# HCD Smart Solutions — Sitio web

Sitio institucional de **HCD Smart Solutions**: tecnología a medida para pymes (sistemas de gestión, CRM, tiendas en Tiendanube, automatizaciones y agentes de IA).

Es un sitio estático (HTML + CSS, sin dependencias ni build).

## Estructura

```
index.html                     Página completa
img/octopus-panel-carga.jpg    Pantalla de ejemplo: panel de carga
img/octopus-base-datos.jpg     Pantalla de ejemplo: base de datos única
img/octopus-estadisticas.jpg   Pantalla de ejemplo: panel de estadísticas
img/<nombre>.jpg               Fotos del equipo
```

## Publicar con GitHub Pages

1. Crear un repositorio nuevo en GitHub (por ejemplo `hcd-web`).
2. Subir estos archivos a la raíz del repo (arrastrándolos en *Add file › Upload files*, o con git):
   ```bash
   git init
   git add .
   git commit -m "Sitio HCD Smart Solutions"
   git branch -M main
   git remote add origin https://github.com/USUARIO/hcd-web.git
   git push -u origin main
   ```
3. En el repo: *Settings › Pages › Build and deployment › Source: Deploy from a branch*, rama `main`, carpeta `/ (root)`.
4. En unos minutos queda online en `https://USUARIO.github.io/hcd-web/`.

Para usar un dominio propio (ej. `hcdsmart.com.ar`), cargarlo en *Settings › Pages › Custom domain* y apuntar el DNS a GitHub.

## Pendientes antes de publicar

- El formulario de contacto abre WhatsApp (11 6601-2321) con el mensaje armado; no necesita servidor.

## Personalizar

- Color de acento: cambiar `--accent` en el `<style>` del `<head>` de `index.html`.
- Las pantallas de Octopus son ilustrativas, con datos de ejemplo.
