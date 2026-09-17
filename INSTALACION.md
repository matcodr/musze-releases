# Cómo instalar Musze

Musze funciona en **Mac** (Apple Silicon o Intel) y en **Windows 10 / 11 de 64 bits**. Hay **una sola descarga**, **Musze Free**, que es la app completa. **Musze Pro es una clave de licencia** que se pega dentro de esa misma app: no hay un segundo instalador, no se descarga nada otra vez y no se pierde nada.

> La app está en inglés. En este instructivo, los nombres de los botones y de las pestañas van **en inglés entre paréntesis**, tal como los vas a ver en pantalla.

---

## 1. Elige tu descarga

Hay tres archivos. Baja **uno solo**: el de tu sistema.

| Sistema | Archivo |
|---|---|
| Mac con Apple Silicon (M1, M2, M3, M4…) | `Musze-Free-Silicon.dmg` |
| Mac con Intel (anteriores a 2020) | `Musze-Free-Intel.dmg` |
| Windows 10 / 11 (64 bits) | `Musze-Free-Windows.exe` |

¿No sabes qué Mac tienes? Menú  → **Acerca de este Mac**. Si dice *Chip Apple M1/M2/M3/M4*, es Silicon; si dice *Procesador Intel*, es Intel.

Enlaces directos (siempre apuntan a la versión más reciente):

- Mac Silicon → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Silicon.dmg
- Mac Intel → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Intel.dmg
- Windows → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Windows.exe

No hace falta instalar nada más: todo lo que Musze necesita para leer, convertir, analizar e identificar tu música viene dentro de la app.

---

## 2. Instalar en Mac

1. **Abre el archivo `.dmg`** que descargaste (doble clic en Descargas). Se abre una ventana con el ícono de **Musze** y una carpeta **Applications**.
2. **Arrastra Musze sobre la carpeta Applications** dentro de esa ventana. Espera a que termine de copiar.
3. Abre **Finder → Aplicaciones**, busca **Musze** y haz **clic derecho (o Control + clic) sobre Musze → Abrir**.
4. macOS muestra un aviso diciendo que no puede verificar al desarrollador. Pulsa **Abrir** en ese aviso.
5. Listo. Desde ahora Musze se abre con doble clic normal, desde Aplicaciones, el Dock o Launchpad.

**¿Por qué el clic derecho?** Musze todavía no está firmado con una cuenta de desarrollador de Apple, así que macOS bloquea el **primer** doble clic con un mensaje tipo *"Musze está dañado"* o *"no se puede abrir porque no se puede verificar el desarrollador"*. Es un aviso sobre la firma, no sobre el archivo. Solo tienes que hacer el clic derecho → Abrir **una vez**.

**Si aun así no abre:**

- Abre **Terminal** (Aplicaciones → Utilidades → Terminal), pega esta línea y pulsa Enter:
  `xattr -dr com.apple.quarantine /Applications/Musze.app`
- Vuelve a abrir Musze desde Aplicaciones.

**Primer uso:**

- La primera vez que Musze lea tu carpeta de música, macOS pedirá permiso para acceder a esa carpeta. Pulsa **Permitir** (si lo negaste, ve a **Ajustes del Sistema → Privacidad y seguridad → Archivos y carpetas** y activa Musze).
- macOS también puede pedirte **la contraseña del llavero** la primera vez que Musze guarde una clave de API o una cuenta conectada. Es el llavero del sistema, no una cuenta de Musze.
- Puedes **expulsar el disco del DMG** (el ícono blanco "Musze" en el escritorio o en la barra lateral del Finder → botón ⏏) y borrar el `.dmg` de Descargas. La app ya está en Aplicaciones.

**Datos:** tu biblioteca, playlists y ajustes viven en `~/Library/Application Support/MUSZE`. Si arrastras una edición encima de la otra, esa carpeta no se toca.

---

## 3. Instalar en Windows

1. **Ejecuta el `.exe`** que descargaste (doble clic en Descargas).
2. Windows muestra un panel azul **"Windows protegió tu PC"**. Pulsa **Más información** y luego **Ejecutar de todas formas**. Solo pasa la primera vez.
3. El instalador pregunta **dónde instalar Musze**. Deja la carpeta propuesta o elige otra y pulsa **Instalar**. Se instala **solo para tu usuario**, por eso nunca pide contraseña de administrador.
4. Al terminar, deja marcada la casilla para abrir Musze y pulsa **Finalizar**. El instalador también deja un acceso directo en el **Escritorio** y una entrada en el **menú Inicio**.

**¿Por qué el panel azul?** El instalador todavía no lleva certificado de firma de código. SmartScreen avisa de eso, no de que el archivo tenga algo malo.

**Datos:** tu biblioteca, playlists y ajustes viven en `%APPDATA%\MUSZE`. Si algún día desinstalas Musze (Configuración → Aplicaciones), esa carpeta se queda intacta y al reinstalar sigues donde estabas.

---

## 4. Pasar de Free a Pro

**Musze Pro es una clave**, no otra descarga.

1. Compra la licencia en [musze.app](https://musze.app). La clave llega por correo con el recibo.
2. En Musze, abre **Ajustes (Settings) → Sources** y baja hasta la sección **Licence**, al final de esa pestaña.
3. Pega la clave y presiona **Activate**. Listo: las funciones Pro se desbloquean en la misma copia que ya tienes, sin descargar ni mover nada.

Cualquier clave comprada antes sigue sirviendo, en Mac y en Windows.

**Qué agrega Pro:** la tonalidad musical y la rueda Camelot, las medidas de volumen (LUFS), *More like this*, *Keep this folder tidy*, Sound Check, Duplicates, Correct gain, la sección de efectos (FX), el filtro y **Match Gain** del reproductor, el tema claro **Daylight**, y las búsquedas en **Discogs** y **SoundCloud**. Todo lo demás es gratis y sin límites: biblioteca de cualquier tamaño, reproductor, BPM, energía, géneros, Your taste, For you, carátulas y etiquetas, búsqueda en la web (incluido YouTube), playlists y playlists inteligentes, y **todas las exportaciones**, incluida la memoria USB para CDJ y Engine.

**¿Ya tenías instalado un archivo `Musze-Pro-…`?** Esa copia sigue funcionando. Una vez te va a avisar, en la franja de arriba de la ventana, que las actualizaciones ahora llegan por Musze Free: baja la versión Free de esta misma página, instálala encima y pega tu clave.

---

## 5. Actualizar

- Musze busca versiones nuevas **cada pocas horas y al abrir la app**. Cuando hay una, aparece **una franja encima de la biblioteca** con el botón **Update** (actualizar).
- **Update** descarga el archivo correcto para tu sistema y tu edición, lo comprueba (tamaño y suma de verificación contra lo que dice la versión publicada) y luego te ofrece **Restart now** (reiniciar ahora). Al pulsarlo, Musze se cierra, se reemplaza por la versión nueva y se vuelve a abrir en unos segundos. Tu biblioteca, playlists, carpetas y ajustes quedan intactos.
- Musze **no descarga nada hasta que pulsas Update, y no se reinicia hasta que pulsas Restart now**. Si pulsas **Later** (luego), el archivo descargado se guarda y el mismo botón **Restart now** te espera en **Ajustes (Settings) → About → Updates**.
- Si Musze **no puede reemplazarse a sí mismo** donde está (por ejemplo, lo abriste directamente desde la descarga en vez de desde Applications, o la carpeta Applications pertenece a otro usuario del Mac), la franja lo dice en una línea y ofrece **Download** (descargar) como antes: se abre en tu navegador e instalas igual que la primera vez.
- Si una actualización desde la app falla, vuelve sola la versión anterior y la siguiente vez que aparezca la franja te dice qué pasó.
- En Mac, después de una actualización puede volver a pedir **clic derecho → Abrir** la primera vez, y macOS puede volver a pedir la contraseña del llavero.
- ¿Quieres buscar ahora, o apagar el aviso? **Ajustes (Settings) → About**: ahí están el interruptor de búsqueda automática y el botón **Check now**.
- **Si tienes la versión 1.0.11 o anterior**, esta vez toca instalar a mano una última vez: esa versión todavía no sabe actualizarse sola. A partir de 1.0.12 son dos clics.

---

## 6. Si algo no funciona

- **La app abre pero no ve mi música:** revisa el permiso de carpeta (Mac: Ajustes del Sistema → Privacidad y seguridad → Archivos y carpetas → Musze).
- **Mac dice que la app está dañada incluso después del clic derecho → Abrir:** usa la línea de Terminal del punto 2.
- **Cualquier otro problema:** en Musze ve a **Ajustes (Settings) → General**, baja hasta el final y pulsa **Copy diagnostic report**; pega eso en un correo a **hello@musze.app** contando qué estabas haciendo. El informe no incluye tu música ni datos personales, solo versiones y el estado de la app.

---

## Resumen rápido

- **Mac:** abre el `.dmg` → arrastra Musze a Applications → **clic derecho → Abrir** la primera vez.
- **Windows:** ejecuta el `.exe` → **Más información → Ejecutar de todas formas** → Instalar.
- **Pro** es una clave: **Ajustes (Settings) → Sources → Licence**, pegar y **Activate**.
- **Ayuda:** hello@musze.app
