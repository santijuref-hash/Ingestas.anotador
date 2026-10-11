# Ingestas

Aplicación Android de prueba para organizar ocho ingestas diarias y crear recordatorios personales de medicación.

## Funciones
- Registro por fecha de ocho ingestas, horario y notas de lo que comiste.
- Vista de historial/calendario y exportación del día a `.txt`.
- Recordatorios diarios de medicación y marca de toma realizada.
- Avisos opcionales para horarios de ingestas.
- Retención configurable de anotaciones (1, 3, 7, 15 o 30 días) y borrado manual.
- Datos guardados localmente en el teléfono.

## Obtener el APK
1. Abrí **Actions** en este repositorio.
2. Ejecutá **Build Android APK** con **Run workflow** (también se ejecuta al subir cambios).
3. Al terminar, descargá el artefacto `Ingestas-debug-apk`, descomprimilo e instalá `app-debug.apk` en Android.

Es un APK de depuración para pruebas, no firmado para Google Play. Los avisos dependen de permisos y restricciones de batería de Android. Las notificaciones del sistema se pueden descartar; dentro de la app se registra la toma al marcarla como realizada. Los datos locales pueden perderse si se desinstala la app o se borran sus datos. El borrado automático del historial se ejecuta al abrir la app, no como servicio en segundo plano. Los recordatorios son organizadores de horarios ingresados por el usuario, no indicaciones médicas.
