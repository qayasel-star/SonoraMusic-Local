# Integración Sonora Music 1.5.2

## Integrado
- Diseño de inicio futurista con panel destacado, identidad visual S y acentos cian/violeta.
- Icono de aplicación integrado en el manifiesto y recursos adaptativos.
- Controles y panel de reproducción con estilo visual actualizado.
- Proyecto Android colocado en la raíz del repositorio para que GitHub Actions encuentre `settings.gradle` y `app/build.gradle`.
- `versionCode` incrementado a 8 y `versionName` a 1.5.2 para permitir la actualización sobre la instalación 1.5.1, siempre que se use la misma firma de APK.

## Verificaciones y límites
- Se preservaron las clases de reproducción y la estructura de biblioteca/listas del ZIP corregido 1.5.2.
- Este entorno no dispone de Gradle instalado y no se ha ejecutado una compilación Android real. La compilación debe confirmarse en GitHub Actions.
- El código contiene `YOUR_JAMENDO_CLIENT_ID` como marcador de posición. La integración de catálogo Jamendo requiere configurar un identificador válido; sin él, no puede garantizarse la búsqueda online.
- La APK de depuración de GitHub Actions puede instalarse sobre una versión previa solo si la firma coincide. No se debe desinstalar la app si se quiere conservar sus datos. Si la firma es distinta, Android rechazará la actualización.
- No se incluye ninguna clave privada de firma ni contraseña en el repositorio.
