# DashboardLayoutIcon
![Image](https://github.com/user-attachments/assets/028904cb-f02d-4f68-8726-3a54b431553e)
Un componente de React que muestra un ícono de “Layout” con tres variaciones (Dashboard, Grid, Panel Left). Cambia de estado secuencialmente al hacer hover, animando cada rectángulo con un efecto de *fade-in* y *scale* diferido.

## Características

- **3 estados**: 
  1. Layout “Dashboard”  
  2. Layout “Grid”  
  3. Layout “Panel Left”  
- **Transición secuencial**: cada vez que pasas el mouse sobre el ícono, avanza al siguiente estado (0 → 1 → 2 → 0).  
- **Animación**: Los rectángulos aparecen con un efecto de `fadeIn` y `scale` (0.8 a 1) con retrasos escalonados (`0ms`, `100ms`, `200ms`, `300ms`).

## Uso

1. **Instalación**  
   Asegúrate de tener un proyecto con React (16.8 o superior, ya que se usan *Hooks*). Copia el archivo `DashboardLayoutIcon.tsx` (o `.jsx`) en tu proyecto.

2. **Importación**  
   ```tsx
   import DashboardLayoutIcon from "./DashboardLayoutIcon";
