# EGIPTO VIDEO STUDIO

Editor de video para Windows basado en **Drift v0.6.0**, adaptado al flujo de trabajo de EGIPTO VIDEO STUDIO.

## Primera build de prueba

La compilación de Windows parte del tag oficial `v0.6.0` de Drift y aplica el parche mantenido en `patches/`.

Incluye:

- **Media | Audio | Texto | Subtítulos | Transiciones | Animaciones | Fish Audio**
- Animaciones nativas de Drift y automatización aleatoria sobre clips visuales.
- Transiciones nativas de Drift.
- Subtítulos nativos de Drift, separados de Fish Audio.
- Fish Audio integrado dentro del editor.
- `/v1/tts/stream/with-timestamp`.
- Alineación de timestamps contra el guion original.
- Bloques visuales aproximadamente de 2–4 segundos.
- Preroll visual de **100 ms**.
- Pistas `Voz Fish` y `Visual Fish`.
- Colocación automática de imágenes/videos sobre los bloques de tiempo.
- Portable de Windows con **EGIPTO VIDEO STUDIO.exe**.
- Instalador de Windows.

## Build

GitHub Actions → **Build Windows · EGIPTO VIDEO STUDIO**.

Al terminar correctamente genera dos artifacts:

- `EGIPTO-VIDEO-STUDIO-Portable-v0.1`
- `EGIPTO-VIDEO-STUDIO-Setup-v0.1`

## Base y licencia

Proyecto derivado de CutWire-Studios/Drift v0.6.0. Drift se distribuye bajo GPL-3.0; esta adaptación conserva las obligaciones de esa licencia.
