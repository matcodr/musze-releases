# Musze — descargas / downloads

**Musze** es un gestor de biblioteca musical para DJs, en **Mac** (Apple Silicon o Intel) y **Windows 10 / 11 de 64 bits**: biblioteca local, análisis de BPM, tonalidad (Camelot), sonoridad y energía, Sound Check, géneros, carpetas de playlists, metadatos y carátulas de catálogos libres, y exportación a Rekordbox, Traktor, Engine DJ, djay Pro y **memorias USB que los CDJ y los reproductores Engine OS leen directamente**.

Todo el análisis ocurre **en tu computadora**. Sin cuenta, sin publicidad, sin telemetría.

Este repositorio contiene **solo los instaladores y las notas de versión**.

---

## Descargar / Download

Hay dos ediciones: **Musze Free** y **Musze Pro**. Son la misma app, se instalan igual y usan la misma biblioteca. Baja **un solo archivo**: el de tu edición y tu sistema.

| Sistema / System | Musze Free | Musze Pro |
|---|---|---|
| Mac · Apple Silicon (M1–M4) | [`Musze-Free-Silicon.dmg`](https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Silicon.dmg) | [`Musze-Pro-Silicon.dmg`](https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Pro-Silicon.dmg) |
| Mac · Intel (antes de 2020) | [`Musze-Free-Intel.dmg`](https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Intel.dmg) | [`Musze-Pro-Intel.dmg`](https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Pro-Intel.dmg) |
| Windows 10 / 11 (64 bits) | [`Musze-Free-Windows.exe`](https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Windows.exe) | [`Musze-Pro-Windows.exe`](https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Pro-Windows.exe) |

¿No sabes qué Mac tienes? Menú  → **Acerca de este Mac**. *Chip Apple M…* es Silicon; *Procesador Intel* es Intel.

**No hace falta instalar nada más.** Todo lo que Musze necesita para leer, analizar e identificar tu música viene dentro de la app.

---

## 📘 Instructivo de instalación (español)

**→ [Cómo instalar Musze, paso a paso](INSTALACION.md)** — Mac, Windows, el primer arranque, cómo pasar de Free a Pro, cómo actualizar y qué hacer si algo falla.

### Resumen rápido

- **Mac:** abre el `.dmg` → arrastra **Musze** a **Applications** → la primera vez, **clic derecho sobre la app → Abrir → Abrir**.
- **Windows:** ejecuta el `.exe` → **Más información → Ejecutar de todas formas** → **Instalar**. No pide contraseña de administrador.
- **Musze Pro no necesita clave**: se desbloquea por ser la edición Pro. Se instala encima de Free sin perder nada.

En Mac el primer doble clic es rechazado porque la app todavía no está firmada con una cuenta de desarrollador de Apple; en Windows aparece el panel azul de SmartScreen por la misma razón. Es un aviso sobre la firma, no sobre el archivo.

---

## 📗 Install guide (English)

- **Mac:** open the `.dmg`, drag **Musze** into **Applications**, then **right-click the app → Open → Open** the first time.
- **Windows:** run the `.exe`, then **More info → Run anyway** → **Install**. It installs for your user only, so it never asks for an administrator password.
- **Musze Pro needs no licence key** — it is unlocked by being the Pro edition. Install it over Free and your library, playlists and settings are kept; both editions share the same data folder.
- Have a licence key from before? Paste it in the **Free** build, under **Settings → Sources → Licence**.

Musze is not yet signed with an Apple Developer ID, and the Windows installer is not code-signed, so the first launch is refused on both systems. That is a message about the signature, not about the file. On a Mac, if it still refuses, open Terminal and run:

```sh
xattr -dr com.apple.quarantine /Applications/Musze.app
```

The full step-by-step guide is in Spanish: **[INSTALACION.md](INSTALACION.md)**.

---

## Actualizaciones / Updates

Musze busca versiones nuevas **cada pocas horas y al abrir la app**, y muestra una franja encima de la biblioteca con un botón **Descargar**. Nunca se actualiza solo: siempre instalas tú, igual que la primera vez, y tu biblioteca queda intacta. El interruptor y el botón **Check now** están en **Settings → About**.

Musze checks for new versions every few hours and at launch, and shows a notice above the library with a **Download** button. It never updates itself — you always install it yourself, exactly as the first time, and your library is untouched. The switch and a **Check now** button are in **Settings → About**.

---

## Tu música no se toca / Your music is safe

Musze lee tu música **donde está**. Nunca mueve, renombra ni borra un archivo de audio por su cuenta. Escribir BPM, tonalidad o carátula dentro de un archivo solo ocurre cuando tú lo activas, y las copias limpias y las memorias USB se escriben como **copias**: el original se abre solo para leer.

Musze reads your music **where it already is**. It never moves, renames or deletes an audio file on its own. Writing BPM, key or artwork into a file only happens when you turn it on, and clean copies and USB exports are written as **copies** — the original is opened read-only.

---

## Problemas / Problems

En Musze: **Settings → General**, hasta abajo, **Copy diagnostic report**. Envíalo a **hello@musze.app** contando qué estabas haciendo. El informe no incluye tu música ni datos personales.

In Musze: **Settings → General**, at the bottom, **Copy diagnostic report**. Send it to **hello@musze.app** with what you were doing. The report contains no music and no personal data.
