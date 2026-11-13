# 🐧 LinuxMind Lab

**LinuxMind Lab** es un laboratorio educativo e interactivo para comenzar a aprender Linux desde cero, practicar conceptos básicos y explorar fundamentos relacionados con la ciberseguridad desde el navegador.

Creado por **Eminent24 | The CyberMind Lab**, el proyecto combina explicaciones, módulos interactivos, una terminal simulada y un cuestionario final con una interfaz inspirada en terminales y paneles tecnológicos.

> **Importante:** la terminal de este proyecto es una simulación educativa. Los comandos que escribes dentro de ella no se ejecutan en el sistema operativo real ni modifican los archivos de tu computadora.

## 📚 Contenido

El laboratorio está organizado en seis módulos:

1. **¿Qué es Linux?** — conceptos básicos, código abierto, usos y relación con la ciberseguridad.
2. **Probar sin miedo** — introducción a Live USB, máquinas virtuales y arranque dual.
3. **Anatomía interactiva** — explicación del kernel, la shell, el entorno de escritorio, los gestores de paquetes y las carpetas del sistema.
4. **Distribuciones y recomendador** — presentación de Linux Mint, Ubuntu, Kali Linux, Debian, Fedora y Arch Linux, más un test para orientar la elección.
5. **Simulador de terminal** — práctica guiada con comandos básicos y pequeños easter eggs.
6. **Desafío final** — cuestionario introductorio para repasar lo aprendido.

## ✨ Características

- Interfaz en español con tema oscuro y detalles de estilo neón.
- Diseño adaptable a distintos tamaños de pantalla.
- Módulos interactivos para explorar conceptos de Linux.
- Sistema de puntos de experiencia (XP) y rangos.
- Terminal simulada con historial de comandos.
- Cuestionario con respuestas y explicaciones.
- Easter eggs como `neofetch`, `matrix`, `hack`, `credits` y `tux`.
- Aplicación en un único archivo HTML que puede abrirse localmente.

## 🚀 Cómo usarlo

### Ejecutarlo en tu computadora

1. Abre la pestaña **Code** de este repositorio.
2. Descarga el archivo HTML que quieras probar.
3. Abre el archivo con Firefox, Chrome, Edge u otro navegador moderno.

El proyecto está diseñado para funcionar localmente, sin instalar paquetes ni configurar un servidor.

### Archivos del repositorio

- **`LinuxMind_Lab.html`**: conserva el archivo original.
- **`LinuxMind_Lab_sintaxis_corregida.html`**: copia con correcciones de sintaxis JavaScript para continuar las pruebas. Aún debe probarse funcionalmente en un navegador antes de considerarse una versión estable.

## ⌨️ Comandos disponibles en la terminal simulada

Entre los comandos y acciones disponibles en el simulador se encuentran:

| Comando | Función dentro del laboratorio |
|---|---|
| `help` | Muestra una lista de comandos disponibles. |
| `ls` | Muestra los archivos ficticios del directorio. |
| `pwd` | Muestra una ruta simulada. |
| `whoami` | Muestra el usuario ficticio. |
| `cat` | Simula la lectura de algunos archivos de ejemplo. |
| `mkdir` | Añade una carpeta al sistema de archivos simulado. |
| `uname -a` | Muestra información ficticia del sistema. |
| `sudo apt update` | Presenta una salida simulada de actualización. |
| `puertos` | Presenta puertos de ejemplo. |
| `clear` | Limpia la salida de la terminal. |

También hay comandos de demostración para los easter eggs. **No uses esta terminal como si fuera una consola real de Linux:** su objetivo es practicar conceptos en un entorno ficticio.

# 🐧 LinuxMind Lab v7.0 — Laboratorio Interactivo de Linux & Pentesting

![Version](https://img.shields.io/badge/Version-v7.0-00ff9d?style=for-the-badge)
![Architecture](https://img.shields.io/badge/Single--File-HTML%20%7C%20CSS%20%7C%20JS-00e5ff?style=for-the-badge)
![Mode](https://img.shields.io/badge/Ejecución-100%25%20Offline%20%26%20Portátil-b56bff?style=for-the-badge)
![Focus](https://img.shields.io/badge/Ciberseguridad-Pentesting%20%26%20CTF-ff3864?style=for-the-badge)

**LinuxMind Lab** es una plataforma educativa interactiva, gamificada y autocontenida en un **único archivo `.html`** sin dependencias externas. Diseñada para estudiantes de informática, administración de sistemas y ciberseguridad, permite aprender desde los fundamentos de GNU/Linux hasta auditorías ofensivas en un entorno seguro dentro del navegador.

---

## 🚀 Novedades en v7.0: Laboratorio de Pentesting

La actualización **v7.0** incorpora un entorno práctico de seguridad ofensiva sincronizado en tiempo real con el simulador de consola:

* **🖥️ Red de Laboratorio (`10.10.10.0/24`):** 3 máquinas virtuales ficticias con control de encendido/apagado en vivo (`ONLINE` / `OFFLINE`).
* **🔍 Escaneo y Enumeración Simulada:** Soporte para `nmap` (`-sV`, `-p-`), `gobuster`, `ftp`, `smbclient`, `hydra`, `curl` y `ssh`.
* **🏷️ Vulnerabilidades Etiquetadas (CWE):** 6 hallazgos reales clasificados por severidad (`MEDIA`, `ALTA`, `CRÍTICA`) con evidencia técnica y plan de remediación.
* **🚩 Retos Tipo CTF:** Búsqueda y validación de banderas (`CYBERMIND{...}`) mediante enumeración web/API, abuso de servicios mal configurados, diccionarios de contraseñas débiles y escalada de privilegios a `root`.
* **📋 Generador de Reportes Profesionales:** Constructor de informes técnicos con vista previa en vivo y exportación directa en **Markdown (`.md`)** y **Reporte Ejecutivo (`.html`)**.

---

## 🧩 Módulos Incluidos

| Módulo | Título | Descripción |
| :--- | :--- | :--- |
| **01** | **¿Qué es Linux?** | Fundamentos del sistema operativo libre, código abierto, mitos vs. realidad y ventajas en seguridad. |
| **02** | **Probar sin Miedo** | Comparativa guiada de **Live USB** (Ventoy/Rufus), **Máquinas Virtuales** y **Dual Boot** con indicador de riesgo. |
| **03** | **Anatomía Interactiva** | Explorador de las 4 capas (Kernel, Shell, Entorno de Escritorio, Gestor de Paquetes) y jerarquía de directorios (`/`, `/home`, `/etc`, `/bin`, `/root`, `/var`, `/dev`) comparada con Windows. |
| **04** | **Distros + Test** | Asistente interactivo de 3 preguntas para elegir distribución + catálogo de 9 distros (Linux Mint, Ubuntu, Kali Linux, Debian, Fedora, Arch Linux, Pop!_OS, Manjaro y Tails/NixOS). |
| **05** | **Simulador Terminal** | Consola multi-distro en vivo (**Ubuntu `apt`**, **Arch `pacman`**, **Fedora `dnf`**), modo superusuario (`sudo su` / `exit`), árbol de archivos persistente (`ls -la`, `cd`, `mkdir`, `touch`, `cat`, `cp`, `mv`, `rm`, `grep`, `chmod`, `./script.sh`), cambio entre **Bash** y **Zsh**, autocompletado con `Tab`, 10 paquetes instalables y 10 misiones guiadas. |
| **06** | **Desafío Final** | Cuestionario de evaluación con retroalimentación inmediata y registro de récord histórico. |
| **07** | **Lab Pentesting** | Gestión de VMs objetivo, telemetría de escaneos, catálogo de vulnerabilidades CWE, validación de Flags CTF y exportador de reportes. |
| **08** | **Update News** | Historial completo de versiones (`v1.0` a `v7.0`) y hoja de ruta de próximas funciones. |

---

## 🎯 Topología del Laboratorio Pentesting (`10.10.10.0/24`)

| Máquina Virtual | IP Objetivo | Sistema Operativo | Dificultad | Vectores de Auditoría |
| :--- | :--- | :--- | :--- | :--- |
| **VM 01 // Alpha-WebFTP** | `10.10.10.11` | Ubuntu Server 22.04 LTS | 🟢 Fácil | Enumeración de directorios web (`gobuster`) y acceso FTP anónimo (`ftp`). |
| **VM 02 // Bravo-CorpSSH** | `10.10.10.22` | Debian 12 (Bookworm) | 🟡 Media | Exposición de configuración en recurso público SMB (`smbclient`) y fuerza bruta SSH (`hydra`). |
| **VM 03 // Omega-Vault** | `10.10.10.33` | Arch Linux Hardened | 🔴 Difícil | Escaneo completo de puertos (`nmap -p-`), API interna sin autenticación (`curl`) y escalada de privilegios vía `sudo` (`find`). |

---

## ⚡ Cómo Usarlo

### Opción 1: Ejecución Local (Sin Internet)
1. Descarga el archivo `LinuxMind_Lab-v7.0-Public.html` desde este repositorio.
2. Haz **doble clic** sobre el archivo para abrirlo en cualquier navegador moderno (Chrome, Firefox, Brave, Waterfox, Edge).
3. No requiere instalación, servidores ni conexión a internet.

### Opción 2: Despliegue en GitHub Pages
1. Sube el archivo a tu repositorio y renómbralo a `index.html` (o enlázalo desde tu página principal).
2. Ve a **Settings → Pages** en tu repositorio y activa la rama principal (`main`).

---

## 🏆 Sistema de Progreso y Persistencia

* **Escala de 0 a 1000 XP:** 8 rangos progresivos desde *Novato Curioso (Nivel 1)* hasta *Operador Red Team (Nivel MAX)*.
* **Guardado Automático:** Todo el progreso (XP, misiones, carpetas/archivos creados en consola, paquetes instalados, flags CTF y vulnerabilidades detectadas) se guarda localmente mediante `localStorage` y `window.name`.
* **Portabilidad:** Incluye exportación e importación de partidas mediante código de respaldo en Base64 desde el panel **Stats / Progreso**.

---

## 👨‍💻 Autor

Desarrollado por **Eminent24** | **The CyberMind Lab**  
* GitHub: [@Eminent24](https://github.com/Eminent24)

> ⚠️ **Aviso Educativo:** Todos los escaneos, direcciones IP (`10.10.10.x`), servicios y vulnerabilidades dentro de LinuxMind Lab son simulaciones aisladas creadas exclusivamente con fines de aprendizaje y entrenamiento ético.

## 🧭 Tecnologías

- HTML5
- CSS3
- JavaScript
- `localStorage` no está implementado en esta versión, por lo que el progreso no se conserva al recargar la página.

## 🛠️ Próximas mejoras previstas

Estas son ideas para futuras versiones; todavía no forman parte de la versión actual:

- **v3 — Progreso Persistente:** guardar XP y avances entre sesiones.
- **v4 — Misiones:** retos guiados con pistas y recompensas.
- **v5 — Terminal Avanzada:** ampliar el sistema de archivos simulado y los comandos.
- **v6 — Red y Seguridad:** añadir conceptos y prácticas introductorias de redes.
- **v7 — CiberLab:** crear laboratorios de seguridad y retos tipo CTF simulados.
- **v8 — Scripting:** ejercicios introductorios de Bash y Python.

## 🌐 Publicar con GitHub Pages

Para abrir el laboratorio desde la página principal del repositorio, coloca el HTML que quieras publicar con el nombre **`index.html`** en la raíz del repositorio. Después, ve a **Settings → Pages** y configura la publicación desde la rama `main` y la carpeta `/(root)`.

La publicación solo estará lista cuando GitHub Pages indique que el sitio está disponible. Comprueba también la página en el navegador para confirmar que los módulos interactivos funcionan correctamente.

## 👨‍💻 Autor

**Eminent24 | The CyberMind Lab**

- GitHub: [@Eminent24](https://github.com/Eminent24)
- Repositorio: [Eminent24/LinuxMindLab](https://github.com/Eminent24/LinuxMindLab)

## 📄 Licencia

Este repositorio todavía no especifica una licencia de uso. Si deseas permitir formalmente que otras personas reutilicen, modifiquen o distribuyan el proyecto, añade un archivo `LICENSE` con la licencia que elijas.
