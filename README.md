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
