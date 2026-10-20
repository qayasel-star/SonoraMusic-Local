# Compilar Sonora Music en GitHub

1. Sube todos los archivos de esta carpeta a la raíz del repositorio `Sonora-`.
2. En GitHub abre la pestaña **Actions**.
3. Selecciona **Compilar APK Sonora Music**.
4. Pulsa **Run workflow** y confirma con el botón verde.
5. Cuando termine correctamente, abre la ejecución y descarga **Sonora-Music-APK-debug** en **Artifacts**.

El proyecto no incluye `gradlew` originalmente; el workflow genera el wrapper y después compila.
El catálogo Jamendo requiere configurar un `client_id` propio antes de activarlo.
