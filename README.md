# Proyecto de Realidad Aumentada

Aplicación AR usando A-Frame y AR.js con marcador Hiro.

## Despliegue en Vercel

1. Instala Vercel CLI (opcional):
   ```bash
   npm i -g vercel
   ```

2. Desde la carpeta del proyecto:
   ```bash
   vercel
   ```

3. O despliega desde el dashboard de Vercel conectando tu repositorio Git.

## Requisitos

- Asegúrate de tener el archivo `models.glb` en la raíz del proyecto.
- Usa un navegador compatible con WebXR/AR (Chrome en Android recomendado).
- Imprime o muestra el marcador Hiro desde tu cámara.

## Estructura

```
/
├── index.html      # Página principal AR
├── models.glb      # Modelo 3D (asegúrate de agregarlo)
└── vercel.json     # Configuración de Vercel
```
