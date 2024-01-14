# Klipper Configuration Backup for Ender 3 DD 2024 Kamp

![Ender 3 DD 2024 Kamp](url_de_tu_imagen.jpg)

Este repository almacena un respaldo completo de los archivos de configuración de Klipper diseñados específicamente para una impresora 3D Ender 3 equipada con Direct Drive (DD) y modificaciones según el proyecto "Ender-3-DD-2024-Kamp". Este conjunto de configuraciones incluye macros detallados y ajustes precisos para optimizar el rendimiento, la velocidad y la calidad de impresión.

## Contenido

### Estructura del Repositorio

El repositorio sigue una estructura organizativa para facilitar la localización y comprensión de los archivos. Aquí se presenta una breve descripción de las carpetas y archivos más relevantes:

- `configs/`: Contiene archivos de configuración específicos de Klipper.
- `macros/`: Almacena macros personalizados utilizados para tareas automatizadas.
- `images/`: Guarda imágenes relacionadas con la configuración para referencia visual.

### Configuraciones Destacadas

A continuación, se destacan algunas de las configuraciones más significativas incluidas en este respaldo:

#### Macro de Purge para Direct Drive
```python
[macro_purge_dd]
    gcode:
        G92 E0 ; Reset extruder position
        G1 E20 F1200 ; Purge 20mm of filament
