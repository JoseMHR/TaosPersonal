# ⚡ Taos Personal Hub

> **Portal unificado de aplicaciones web, guías de viaje, eventos y herramientas personales de Jose Manuel (Taos).**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-22c55e?style=for-the-badge&logo=github)](https://josemhr.github.io/TaosPersonal/)
[![License](https://img.shields.io/badge/License-Personal%20Use-blue?style=for-the-badge)](LICENSE)

---

### ⚠️ Aviso a navegantes
> Esta es la **guarida de proyectos y utilidades personales y familiares**.  
> Si has llegado hasta aquí por casualidad y no eres de la familia, amistad cercana o invitado a alguno de los eventos... ¡probablemente solo encuentres cosas sumamente cotidianas o aburridas para ti!  
> *Continúa bajo tu propia responsabilidad.*

---

## 📂 Proyectos Incluidos

Cada carpeta dentro de este repositorio representa una web o aplicación independiente, servida directamente a través de **GitHub Pages**:

| Proyecto | Carpeta | Categoría | Stack Técnico | Enlace en Producción |
| :--- | :--- | :--- | :--- | :--- |
| **Boda Elena & José** | [`/boda`](./boda/) | Evento | Tailwind CSS, Google Fonts, Vanilla JS | [Ver web](https://josemhr.github.io/TaosPersonal/boda/) |
| **Violeta FisioPlanner** | [`/fisioplanner`](./fisioplanner/) | Herramienta | React 18 (UMD), Tailwind CSS, SheetJS | [Lanzar app](https://josemhr.github.io/TaosPersonal/fisioplanner/) |
| **Juegos & Puzzles de Tati** | [`/juegos-puzzles`](./juegos-puzzles/) | Entretenimiento | Tailwind CSS, Canvas / JS Touch | [Jugar ahora](https://josemhr.github.io/TaosPersonal/juegos-puzzles/) |
| **Misión: Alsacia** | [`/viaje-alsacia`](./viaje-alsacia/) | Viaje Familiar | React 18, Tailwind CSS, Leaflet Maps | [Ver guía](https://josemhr.github.io/TaosPersonal/viaje-alsacia/) |
| **Planning Visita Madrid 2026** | [`/viaje-madrid`](./viaje-madrid/) | Viaje | Tailwind CSS, Responsive UI | [Ver ruta](https://josemhr.github.io/TaosPersonal/viaje-madrid/) |

---

## 🚀 Despliegue en GitHub Pages

Este repositorio está preparado para desplegarse automáticamente en GitHub Pages sin necesidad de compilación (*zero-build*):

1. Sube este repositorio a tu cuenta de GitHub con el nombre `TaosPersonal`.
2. En GitHub, ve a **Settings** > **Pages**.
3. En **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)`
4. Haz clic en **Save**. En 1-2 minutos, tu portal estará activo en:
   ```
   https://josemhr.github.io/TaosPersonal/
   ```

> [!NOTE]
> El archivo `.nojekyll` en la raíz garantiza que GitHub Pages sirva todas las rutas y assets directamente sin interferencia del motor Jekyll.

---

## 💻 Ejecución en Local

Todas las aplicaciones son archivos estáticos que funcionan con CDNs:

1. Puedes abrir directamente cualquier archivo `index.html` con tu navegador.
2. O bien, si tienes VS Code, utiliza la extensión **Live Server** abriendo la carpeta raíz para probar la navegación entre proyectos.
3. Con Python (desde la terminal en esta carpeta):
   ```bash
   python -m http.server 8080
   ```
   Y abre `http://localhost:8080` en tu navegador.

---

Desarrollado con ❤️ por [Jose Manuel Heredia (Taos)](https://github.com/JoseMHR).
