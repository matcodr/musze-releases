# Cómo instalar Musze

Musze funciona en **Mac** (Apple Silicon o Intel) y en **Windows 10 / 11 de 64 bits**. Hay dos ediciones, **Musze Free** y **Musze Pro**, y las dos son la misma app: se instalan igual, usan la misma biblioteca y se pueden reemplazar una por otra sin perder nada.

> La app está en inglés. En este instructivo, los nombres de los botones y de las pestañas van **en inglés entre paréntesis**, tal como los vas a ver en pantalla.

---

## 1. Elige tu descarga

Hay seis archivos. Baja **uno solo**: el de tu edición y tu sistema.

| Sistema | Musze Free | Musze Pro |
|---|---|---|
| Mac con Apple Silicon (M1, M2, M3, M4…) | `Musze-Free-Silicon.dmg` | `Musze-Pro-Silicon.dmg` |
| Mac con Intel (anteriores a 2020) | `Musze-Free-Intel.dmg` | `Musze-Pro-Intel.dmg` |
| Windows 10 / 11 (64 bits) | `Musze-Free-Windows.exe` | `Musze-Pro-Windows.exe` |

¿No sabes qué Mac tienes? Menú  → **Acerca de este Mac**. Si dice *Chip Apple M1/M2/M3/M4*, es Silicon; si dice *Procesador Intel*, es Intel.

Enlaces directos (siempre apuntan a la versión más reciente):

- Free · Mac Silicon → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Silicon.dmg
- Free · Mac Intel → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Intel.dmg
- Free · Windows → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Free-Windows.exe
- Pro · Mac Silicon → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Pro-Silicon.dmg
- Pro · Mac Intel → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Pro-Intel.dmg
- Pro · Windows → https://github.com/matcodr/musze-releases/releases/latest/download/Musze-Pro-Windows.exe

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

## 4. Free y Pro: cómo cambiar de una a otra

- **Musze Pro no necesita ninguna clave.** Se desbloquea solo por ser la edición Pro.
- **Pasar de Free a Pro:** baja el archivo Pro de tu sistema e instálalo **encima** de la Free (en Mac, arrastra de nuevo a Applications y acepta **Reemplazar**; en Windows, ejecuta el instalador Pro en la misma carpeta). Biblioteca, playlists, etiquetas y ajustes se conservan porque las dos ediciones usan la misma carpeta de datos.
- **Si ya tienes una clave de licencia** de antes, pégala en la edición **Free**, en **Ajustes (Settings) → Sources**, en la sección **Licence** al final de esa pestaña. Ahí desbloquea Pro exactamente como siempre. La edición Pro no tiene dónde pegar una clave porque no la necesita.

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
- **Pro** no usa clave; se instala encima de Free sin perder nada.
- **Ayuda:** hello@musze.app
