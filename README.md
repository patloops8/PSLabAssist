[README.md](https://github.com/user-attachments/files/29579692/README.md)
# ⚡ PS Lab Assist — EAFC 26

**Automate your PlayStyles Lab evolutions. Apply 11 PlayStyles in one click instead of doing it manually one by one.**

> 🌐 [Español más abajo](#español)

---

## What does it do?

In EA Sports FC 26, applying multiple repeated PlayStyle evolutions to a player is tedious: you have to open each evolution, search for the player, confirm, repeat. If you want to apply 3 PS+ and 8 white PlayStyles, that's 11 separate trips through the same flow.

**PS Lab Assist automates all of that.** You choose the player, check the PlayStyles you want, press Start — and the script does the rest while you watch.

![PS Lab Assist panel](https://raw.githubusercontent.com/patloops8/PSLabAssist/main/preview.png)

---

## Features

- ✅ Applies multiple PlayStyle evolutions automatically, one after another
- ✅ Smart page navigation — skips pages where your player's rating isn't present
- ✅ Saves PS presets (e.g. "My CAM build") to reuse across sessions
- ✅ Resume interrupted queues — if something fails mid-run, continue from where it stopped
- ✅ Retry failed evolutions with one click
- ✅ Visual indicators on each PS card showing what was applied or failed
- ✅ Auto-confirm mode (no manual Ok clicks needed)
- ✅ 3-minute safety timeout per evolution — never gets stuck forever
- ✅ Spanish / English interface toggle
- ✅ Draggable panel, minimizable to a floating button

---

## Requirements

- EA Sports FC 26 Web App account
- [Tampermonkey](https://www.tampermonkey.net/) browser extension (Chrome, Edge, Brave, Firefox)
- **⚠️ Turn off Paletools while using this script** — both running together causes navigation errors in the Web App

---

## Installation

### Method 1 — Import via Tampermonkey (recommended, works on all browsers)

1. Copy this link:
   ```
   https://raw.githubusercontent.com/patloops8/PSLabAssist/main/pslab_assist.user.js
   ```
2. Open Tampermonkey → Dashboard → **Utilities** tab
3. Find the **"Install from URL"** section, paste the link, and confirm
4. Click **Install** when Tampermonkey shows the script preview
5. Open the [EA Sports FC 26 Web App](https://www.ea.com/ea-sports-fc/ultimate-team/web-app/) — the PS Lab Assist panel appears automatically

### Method 2 — Direct link (may be blocked by Chrome's security settings)

Click this link directly:
[**Install PS Lab Assist**](https://raw.githubusercontent.com/patloops8/PSLabAssist/main/pslab_assist.user.js)

If Chrome shows a security warning, use Method 1 instead.

> **Having trouble?** See the full installation guide: [Como_Instalar_PS_Lab_Assist.pdf](https://github.com/patloops8/PSLabAssist/blob/main/Como_Instalar_PS_Lab_Assist.pdf)

---

## How to use it

1. Open the **EA Sports FC 26 Web App** and go to **Evolutions → EvoLab**
2. The PS Lab Assist panel appears in the top-right corner of the screen
3. **Enter the player's details** — name (exactly as shown on the card), OVR, and position
4. Click **"Confirm player"**
5. **Check the PlayStyles** you want to apply (up to 3 PS+ and 8 white PS)
6. Press **▶ Start queue** — the script does everything from here

> 💡 **Tip:** Save your most-used PS combinations as presets (e.g. "CDM", "CAM") to reuse them instantly next time.

---

## Important notes

- Write the player's name **exactly as it appears on their card** — if the card says "David", write "David", not "Jonathan David"
- **Turn off Paletools** before running a queue. Running both scripts simultaneously causes the Web App's evolution filter to break
- Applied evolutions make cards **untradeable** — Auto-confirm is on by default, so cards will become untradeable without any pause
- The script works on the Web App only — not the mobile app

---

## Support & donations

If PS Lab Assist saved you time, consider supporting the project:

**[☕ Donate via PayPal](https://paypal.me/patricioversan)**

No pressure — the script is completely free. Any support helps keep it updated.

---

## Changelog

| Version | Highlights |
|---------|-----------|
| v3.5.0 | Visual PS markers reset when confirming a new player |
| v3.4.0 | Overlay always transparent during queue — see the Web App at all times |
| v3.3.0 | Previous button reset to avoid skipping tiles on page 2/3 |
| v3.0.0 | Removed Paletools scan mode — manual mode only, eliminates the conflict |
| v2.13.0 | Per-evolution timeout, resume/retry buttons, visual PS progress markers |
| v2.4.0 | Spanish/English language toggle |
| v2.0.0 | PS preset system (save, load, delete named presets) |

---

---

## Español

# ⚡ PS Lab Assist — EAFC 26

**Automatiza tus evoluciones del PlayStyles Lab. Aplica 11 PlayStyles con un solo clic en vez de hacerlo manualmente uno por uno.**

---

## ¿Qué hace?

En EA Sports FC 26, aplicar varias evoluciones repetidas del PlayStyle Lab es tedioso: tienes que abrir cada evolución, buscar al jugador, confirmar, repetir. Si quieres aplicar 3 PS+ y 8 PlayStyles blancos, son 11 viajes distintos por el mismo flujo.

**PS Lab Assist automatiza todo eso.** Eliges al jugador, marcas los PlayStyles que quieres, presionas Iniciar — y el script hace el resto mientras tú lo ves.

---

## Características

- ✅ Aplica múltiples evoluciones de PlayStyle automáticamente, una tras otra
- ✅ Navegación inteligente de páginas — salta páginas donde el rating de tu jugador no está
- ✅ Guarda presets de PS (ej. "Mi build de CAM") para reutilizarlos entre sesiones
- ✅ Reanuda colas interrumpidas — si algo falla a mitad de camino, continúa desde donde quedó
- ✅ Reintenta evoluciones fallidas con un clic
- ✅ Indicadores visuales en cada tarjeta de PS mostrando qué se aplicó o falló
- ✅ Modo de auto-confirmación (sin necesidad de hacer clic en Ok manualmente)
- ✅ Timeout de seguridad de 3 minutos por evolución — nunca se queda trabado para siempre
- ✅ Interfaz en Español / Inglés
- ✅ Panel arrastrable, minimizable a un botón flotante

---

## Requisitos

- Cuenta de la Web App de EA Sports FC 26
- Extensión [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Edge, Brave, Firefox)
- **⚠️ Apaga Paletools mientras usas este script** — ambos corriendo al mismo tiempo causan errores de navegación en la Web App

---

## Instalación

### Método 1 — Importar desde Tampermonkey (recomendado, funciona en todos los navegadores)

1. Copia este link:
   ```
   https://raw.githubusercontent.com/patloops8/PSLabAssist/main/pslab_assist.user.js
   ```
2. Abre Tampermonkey → Dashboard → pestaña **"Utilidades"**
3. Busca la sección **"Importar desde URL"**, pega el link y confirma
4. Haz clic en **"Instalar"** cuando Tampermonkey muestre el resumen del script
5. Abre la [Web App de EA Sports FC 26](https://www.ea.com/ea-sports-fc/ultimate-team/web-app/) — el panel de PS Lab Assist aparece automáticamente

### Método 2 — Link directo (puede ser bloqueado por la configuración de seguridad de Chrome)

Haz clic en este link directamente:
[**Instalar PS Lab Assist**](https://raw.githubusercontent.com/patloops8/PSLabAssist/main/pslab_assist.user.js)

Si Chrome muestra un mensaje de error de seguridad, usa el Método 1.

> **¿Problemas con la instalación?** Ver la guía completa: [Como_Instalar_PS_Lab_Assist.pdf](https://github.com/patloops8/PSLabAssist/blob/main/Como_Instalar_PS_Lab_Assist.pdf)

---

## Cómo usarlo

1. Abre la **Web App de EA Sports FC 26** y ve a **Evolutions → EvoLab**
2. El panel de PS Lab Assist aparece en la esquina de la pantalla
3. **Ingresa los datos del jugador** — nombre (exactamente como aparece en la carta), OVR y posición
4. Haz clic en **"Confirmar jugador"**
5. **Marca los PlayStyles** que quieres aplicar (hasta 3 PS+ y 8 PS blancos)
6. Presiona **▶ Iniciar cola** — el script hace todo desde aquí

> 💡 **Tip:** Guarda tus combinaciones más usadas como presets (ej. "CDM", "CAM") para reutilizarlas al instante la próxima vez.

---

## Notas importantes

- Escribe el nombre del jugador **exactamente como aparece en su carta** — si la carta dice "David", escribe "David", no "Jonathan David"
- **Apaga Paletools** antes de correr una cola. Tener ambos scripts activos simultáneamente rompe el filtro de evoluciones de la Web App
- Las evoluciones aplicadas hacen que las cartas sean **intransferibles** — el auto-confirm está activado por defecto, así que las cartas quedarán intransferibles sin ninguna pausa
- El script funciona solo en la Web App — no en la app móvil

---

## Soporte y donaciones

Si PS Lab Assist te ahorró tiempo, considera apoyar el proyecto:

**[☕ Donar via PayPal](https://paypal.me/patricioversan)**

Sin presión — el script es completamente gratis. Cualquier apoyo ayuda a mantenerlo actualizado.
