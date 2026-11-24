# Gym Count: de web a app de Android

Este paquete mete tu app dentro de una app real de Android. Todo va dentro del móvil: no necesita internet ni ninguna web, y tus datos se guardan en el propio teléfono.

El APK (el archivo que se instala) se compila gratis en la nube de GitHub, así que no hace falta instalar nada en tu ordenador.

## Pasos

1. Crea una cuenta gratuita en github.com.
2. Arriba a la derecha pulsa **+ → New repository**. Ponle de nombre `gym-count`, déjalo en **Private** y pulsa **Create repository**.
3. En la página del repositorio pulsa **uploading an existing file**. Arrastra todo el contenido de esta carpeta descomprimida (`www`, `package.json`, `capacitor.config.json`, `.github`...) y pulsa **Commit changes**.
   - Si no ves la carpeta `.github` (en Mac está oculta: Cmd + Mayús + punto la muestra), crea el archivo a mano: **Add file → Create new file**, escribe como nombre `.github/workflows/android.yml` y pega dentro el texto de `android.yml.txt`.
4. Entra en la pestaña **Actions**. Si no ha empezado solo, elige **Compilar APK → Run workflow**. Tarda unos 5-10 minutos.
5. Cuando salga el check verde, abre esa ejecución y baja hasta **Artifacts**. Descarga **Gym-Count-APK**, descomprime el zip y tendrás `app-debug.apk`.
6. Pásalo al móvil (cable, Drive, email...) y ábrelo. Android te pedirá permiso para instalar apps de fuera de la Play Store. Es normal: acéptalo, y si sale un aviso de seguridad pulsa **Instalar de todos modos**.

## Importante

- Los datos están solo en el móvil. Si desinstalas la app o borras sus datos, se pierden.
- Este APK sirve para uso personal. Para subirlo a la Play Store hace falta una versión firmada distinta; se puede preparar después.
