# Lima Oscuro

Tema oscuro para VS Code, minimalista en **negro casi gris** con **verde lima** como color protagonista, más acentos **morado** (`#ae81ff`) y **aguamarina** (`#66d9ef`).

## Paleta

| Rol | Color | Uso |
|-----|-------|-----|
| Fondo | `#121212` | Editor, barras |
| Superficie | `#161616` | Sidebar, pestañas |
| **Lima** | `#a6e22e` | Keywords, estructura, tags, acentos |
| Lima brillante | `#b4f70f` | Clases, tipos |
| **Aguamarina** | `#66d9ef` | Funciones, strings, métodos |
| **Morado** | `#ae81ff` | Constantes, this, imports, decoradores |
| Gris verdoso | `#d6e6d6` | Variables, texto |
| Gris tenue | `#6a6a6a` | Comentarios |

## Criterios de diseño (UI/UX)
- **Contraste alto** entre texto y fondo para reducir fatiga visual en sesiones largas.
- **Jerarquía semántica**: cada categoría de código tiene un color estable.
- **Lima = acción/estructura** (lo que dirige el flujo), **aguamarina = contenido** (funciones y strings), **morado = valores especiales/constantes**.

## Instalación
1. Copia la carpeta en `~/.vscode/extensions/lima-oscuro`.
2. Recarga VS Code.
3. Selecciona **Lima Oscuro** en `Ctrl+K Ctrl+T`.

## Desarrollo
La extensión es legible por VS Code desde la carpeta `lima-oscuro/` abierta con **Run Extension** (necesita extensiones de desarrollo de temas), o empaquetada con `vsce package`.
