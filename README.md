# ForceGreen

> 🌿 A dark, minimalist VS Code theme with **lime green** as the hero color.
> 🌿 Tema oscuro y minimalista con **verde lima** como color protagonista.

Dark theme built around a near-black, graphite background with a punchy lime accent, complemented by **aquamarine** (`#66d9ef`) for content and **purple** (`#ae81ff`) for special values — designed for long coding sessions without eye fatigue.

> ⚠️ **AI-generated**: This theme and its README were created with the assistance of AI. / Tema y README generados con ayuda de IA.

---

## English

### Features

- **High-contrast minimalism** — near-black backgrounds (`#121212` / `#161616`) make text pop while keeping the UI calm.
- **Semantic color hierarchy** — every code category has a stable, recognizable color:
  - 💚 **Lime** = action & structure (keywords, tags, accents)
  - 🔷 **Aquamarine** = content (functions, strings, methods)
  - 💜 **Purple** = special values (constants, `this`, imports, decorators)
- **Fine-tuned UI** — matching cursor, selection, bracket-highlight, indent guides and line numbers.
- **Dark only** — built on `vs-dark`, no glare.

### Palette

| Role | Color | Usage |
|------|-------|-------|
| Background | `#121212` | Editor, bars |
| Surface | `#161616` | Sidebar, tabs |
| **Lime** | `#a6e22e` | Keywords, structure, tags, accents |
| Bright lime | `#b4f70f` | Classes, types |
| **Aquamarine** | `#66d9ef` | Functions, strings, methods |
| **Purple** | `#ae81ff` | Constants, `this`, imports, decorators |
| Text | `#d6e6d6` | Variables, prose |
| Comment gray | `#6a6a6a` | Comments, muted code |

### Installation

1. Open the **Extensions** view (`Ctrl+Shift+X`).
2. Search for `ForceGreen` and click **Install**.
3. Press `Ctrl+K Ctrl+T` and select **ForceGreen**.

> Marketplace listing coming soon. Until then, install from the packaged `.vsix` or run it from source (see *Development*).

### Development

```bash
npm install -g vsce          # VS Code extension packager
vsce package                 # build the .vsix
code --install-extension forcegreen-1.0.0.vsix
```

For live editing, open this folder in VS Code, press `F5` to launch an Extension Development Host, then reload and switch to **ForceGreen**.

### License

[MIT](LICENSE) © 2026 ForceGreen

---

## Español

### Características

- **Minimalismo de alto contraste** — fondos casi negros (`#121212` / `#161616`) que hacen resaltar el texto manteniendo la interfaz tranquila.
- **Jerarquía semántica de colores** — cada categoría de código tiene un color estable y reconocible:
  - 💚 **Verde lima** = acción y estructura (keywords, tags, acentos)
  - 🔷 **Aguamarina** = contenido (funciones, strings, métodos)
  - 💜 **Morado** = valores especiales (constantes, `this`, imports, decoradores)
- **UI afinada** — cursor, selección, colores de estructuras (brackets), guías de indentación y números de línea a juego.
- **Solo oscuro** — construido sobre `vs-dark`, sin deslumbramientos.

### Paleta

| Rol | Color | Uso |
|-----|-------|-----|
| Fondo | `#121212` | Editor, barras |
| Superficie | `#161616` | Sidebar, pestañas |
| **Verde lima** | `#a6e22e` | Keywords, estructura, tags, acentos |
| Lima brillante | `#b4f70f` | Clases, tipos |
| **Aguamarina** | `#66d9ef` | Funciones, strings, métodos |
| **Morado** | `#ae81ff` | Constantes, `this`, imports, decoradores |
| Texto | `#d6e6d6` | Variables, prosa |
| Gris tenue | `#6a6a6a` | Comentarios, código atenuado |

### Instalación

1. Abre la vista de **Extensiones** (`Ctrl+Shift+X`).
2. Busca `ForceGreen` y pulsa **Instalar**.
3. Pulsa `Ctrl+K Ctrl+T` y selecciona **ForceGreen**.

> Publicación en el Marketplace próximamente. Hasta entonces, instálalo desde el `.vsix` empaquetado o ejecútalo desde el código fuente (ver *Desarrollo*).

### Desarrollo

```bash
npm install -g vsce          # empaquetador de extensiones
vsce package                 # genera el .vsix
code --install-extension forcegreen-1.0.0.vsix
```

Para edición en vivo: abre esta carpeta en VS Code, pulsa `F5` para lanzar el Host de Desarrollo de Extensiones, recarga y cambia a **ForceGreen**.

### Licencia

[MIT](LICENSE) © 2026 ForceGreen