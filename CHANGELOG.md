# Historial de versiones

## [0.56.0] — Primera versión pública

### Añadido

- Setup oficial para Windows con selección de carpeta de instalación.
- Accesos directos en escritorio y menú Inicio.
- Sistema interno de actualizaciones con detección, descarga, validación, sustitución de archivos y reapertura automática.
- Conservación de rutas, estados, herramientas, descargas, mods, copias de seguridad y registros.
- Interfaz en español e inglés.
- Catálogos PCVR Mods, UEVR, Nativo PCVR, Quest, Pico y Steam Frame.
- Detección automática de juegos instalados.
- Instalación desde la plataforma oficial cuando el juego no está detectado.
- Localización manual de instalaciones existentes.
- Bloqueo de los procesos del VR Mod mientras el juego base no esté instalado.
- Desinstalación con opción de conservar o eliminar los datos.
- Herramienta común DLSS Swapper.

### Juegos incluidos

#### PCVR Mods

- Resident Evil 2
- Metroid Prime VR

#### UEVR

- Silent Hill 2

#### Nativo PCVR

- Half-Life: Alyx

#### Quest

- Return to Castle Wolfenstein
- Doom 3 y contenidos compatibles

#### Pico

- Doom 3 y contenidos compatibles

### Seguridad y fiabilidad

- Aplicación diseñada para funcionar sin permisos administrativos durante su uso normal.
- UPX desactivado para reducir falsos positivos.
- Eliminación de claves y materiales de firmado APK obsoletos.
- Verificación de tamaño y SHA-256 de las actualizaciones.
- Validación de la estructura del paquete antes de actualizar.
- Protección frente a rutas inseguras y extracciones maliciosas.
- Copias temporales y restauración ante fallos de actualización.
- Validación de 7-Zip y ADB únicamente cuando son necesarios.
- Batería automatizada de pruebas y testeo real de los principales procesos.

### Validado en pruebas reales

- Setup e instalación.
- Actualización interna desde 0.56.0 a una versión superior.
- Resident Evil 2.
- Metroid Prime VR.
- Silent Hill 2.
- Half-Life: Alyx.
- Return to Castle Wolfenstein en Quest.
- DLSS Swapper.
