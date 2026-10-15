# Allen 3D

Entorno 3D capturado (`allen.ply`) montado en la web con three.js + WebXR para verse en Meta Quest.

**Ver:** https://elfidelon.github.io/allen-3d/

## Controles

| Dónde | Control |
|---|---|
| Meta Quest | **Enter VR** · stick izquierdo moverse (gatillo = correr) · stick derecho girar 30° y subir/bajar · **A** volver al inicio |
| PC | Orbitar: arrastrar / rueda / clic derecho · Caminar: WASD, Q/E, Shift |
| Celular | Arrastrar, pellizcar, dos dedos |

## Modelos

- `models/allen.glb` — 2.5 M triángulos (9 MB), calidad alta para PC.
- `models/allen-lite.glb` — 1 M triángulos (4 MB), por defecto en Quest y celular. Forzar con `?q=full` o `?q=lite`.

Convertidos del `.ply` original (89 MB, Open3D): se quitaron las zonas negras sin datos y se comprimieron con meshopt (gltf-transform).
