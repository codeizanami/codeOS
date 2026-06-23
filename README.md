<div align="center">

```
  ██████╗ ██████╗ ██████╗ ███████╗ ██████╗ ███████╗
 ██╔════╝██╔═══██╗██╔══██╗██╔════╝██╔═══██╗██╔════╝
 ██║     ██║   ██║██║  ██║█████╗  ██║   ██║███████╗
 ██║     ██║   ██║██║  ██║██╔══╝  ██║   ██║╚════██║
 ╚██████╗╚██████╔╝██████╔╝███████╗╚██████╔╝███████║
  ╚═════╝ ╚═════╝ ╚═════╝ ╚══════╝ ╚═════╝ ╚══════╝
```

**Windows 10 Pro optimizado.**

[![Version](https://img.shields.io/badge/versión-1.0_WIP-6366f1?style=flat-square&labelColor=0d0d0f)](https://codeOS.codeizanami.es)
[![Base](https://img.shields.io/badge/base-Windows_10_Pro-6366f1?style=flat-square&labelColor=0d0d0f)](https://codeOS.codeizanami.es)
[![Tool](https://img.shields.io/badge/herramienta-NTLite-6366f1?style=flat-square&labelColor=0d0d0f)](https://www.ntlite.com)
[![License](https://img.shields.io/badge/uso-personal_·_educativo-6366f1?style=flat-square&labelColor=0d0d0f)](LICENSE)
[![Made in Spain](https://img.shields.io/badge/hecho_en-España_🇪🇸-6366f1?style=flat-square&labelColor=0d0d0f)](https://codeizanami.es)

<br/>

> Sin bloatware. Sin telemetría. Sin compromisos.<br/>
> **build · learn · run**

<br/>

**[🌐 Web](https://codeOS.codeizanami.es)** · **[⬇ Descargar ISOs](https://codeOS.codeizanami.es/#isos)** · **[🔧 codeUtils](https://github.com/codeizanami/codeUtils)**

</div>

---

## ¿Qué es codeOS?

codeOS es un proyecto personal de Windows 10 Pro modificado desde la ISO oficial de Microsoft usando **NTLite**. El objetivo es tener un sistema operativo limpio, rápido y enfocado según el uso que le vayas a dar, sin necesidad de configurar nada después de instalarlo.

Cada versión parte de la misma base limpia y añade únicamente lo necesario para su propósito. No hay menú de selección de edición, no hay scripts previos: instalas y ya tienes el sistema listo.

```
  ISO oficial Microsoft
       │
       ▼  NTLite — eliminación de componentes + tweaks en imagen
  codeOS Gaming  ──▶  Steam · Epic · Roblox · latencia mínima
  codeOS Estudio ──▶  trabajo · diseño · universidad   [próximamente]
  codeOS Max  ──▶  IIS · Hyper-V · RDP · SMB        [próximamente]
       │
       ▼  post-instalación
  codeUtils.exe  ──▶  tweaks finales · apps · Windows Update
```

---

## Versiones

| Versión | Enfoque | Estado |
|:---|:---|:---:|
| **codeOS Gaming** | Máximo rendimiento para juegos | ✅ Disponible |
| **codeOS Estudio** | Limpio y estable para trabajar y estudiar | 🔜 Próximamente |
| **codeOS Max** | Máximo rendimiento, LTSC | 🔜 Próximamente |

---

## Eliminado en todas las versiones

Independientemente de la versión, lo siguiente no existe en ninguna ISO de codeOS:

- Cortana
- Telemetría y diagnósticos de Microsoft
- Bloatware preinstalado — Candy Crush, News, Weather, Maps, Solitaire…
- Internet Explorer
- Mixed Reality
- Paint 3D y 3D Viewer
- OneDrive *(se puede reinstalar manualmente si se necesita)*

---

## codeOS Gaming

> Orientado a Steam, Epic Games, Roblox y gaming en general.

**Optimizaciones incluidas en la imagen:**

- Plan de energía alto rendimiento
- Hardware-Accelerated GPU Scheduling (HAGS) activado
- GPU priority = 8
- Core Parking desactivado
- Timer resolution optimizado
- Nagle Algorithm desactivado
- TCP/IP tuneado para latencia mínima
- DNS Cloudflare 1.1.1.1 preconfigurado
- SysMain (Superfetch) desactivado
- Windows Search desactivado
- Sin Xbox Game Bar — conserva Xbox runtime para compatibilidad con Steam y Game Pass
- Windows Defender activo

---

## codeOS Estudio *(próximamente)*

> Orientado a diseño, administración de empresas y uso general universitario o profesional.

**Incluirá:**

- Microsoft Store completa
- Windows Search activo
- Impresoras y periféricos sin fricción
- Remote Desktop habilitado
- Portapapeles histórico activo
- DNS Cloudflare 1.1.1.1
- Sin telemetría · Sin bloatware
- Windows Defender activo

---

## codeOS Max *(próximamente)*

> Orientado al máximo rendimiento, ejemplo servidores de juegos, web, etc.

**Incluirá:**

- IIS — servidor web preconfigurado
- Hyper-V — virtualización habilitada
- Remote Desktop habilitado
- SMB — servidor de archivos en red
- Servidor de impresión en red
- DNS y DHCP configurados
- Reglas de firewall para HTTP, HTTPS, RDP y SMB
- Plan de energía alto rendimiento permanente
- Sin suspensión ni hibernación

---

## Instalación

### 1 — Descarga la ISO

Desde **[codeOS.codeizanami.es](https://codeOS.codeizanami.es)**, sección ISOs.

### 2 — Grábala en un USB

Usa [Rufus](https://rufus.ie) o [Balena Etcher](https://etcher.balena.io) con un USB de mínimo 8 GB.

### 3 — Instala Windows

Arranca desde el USB y sigue el instalador normal de Windows. No necesitas clave de producto durante la instalación.

### 4 — Ejecuta codeUtils

Al iniciar sesión por primera vez, **codeUtils** se lanzará automáticamente para aplicar los tweaks finales. Si no arranca, descárgalo manualmente desde la web:

```
clic derecho sobre codeUtils.exe → Ejecutar como administrador
```

codeUtils aplica tweaks de red, registro y servicios según el perfil que elijas, instala las apps que quieras via winget, y reinicia el sistema al terminar.

> **codeUtils** también funciona sobre cualquier instalación limpia de Windows 10 Pro estándar — no necesitas codeOS para usarlo.
>
> 🔗 [github.com/codeizanami/codeUtils](https://github.com/codeizanami/codeUtils)

---

## Herramientas utilizadas

| Herramienta | Uso |
|:---|:---|
| [NTLite](https://www.ntlite.com) | Modificación de imágenes Windows — eliminación de componentes y tweaks en la ISO |
| [Windows ADK](https://learn.microsoft.com/es-es/windows-hardware/get-started/adk-install) | `oscdimg` para generar ISOs booteables |
| [Rufus](https://rufus.ie) | Grabación del USB de arranque |

---

## Notas legales

- Las ISOs de codeOS parten de imágenes oficiales de Microsoft.
- codeOS es un proyecto de uso **personal y educativo**.
- No se distribuye ninguna clave de activación de Windows.
- Microsoft Windows requiere licencia válida para su uso.
- No se permite la redistribución comercial.

---

<div align="center">

*codeizanami · España · 2026*

</div>
