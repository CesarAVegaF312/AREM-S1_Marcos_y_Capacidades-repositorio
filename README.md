# AREM S1 — Marcos y Capacidades

Material de la **Sesión 1** del curso *Arquitectura Empresarial* (AREM): marcos de
referencia de arquitectura (Zachman, TOGAF ADM) y capacidades organizacionales.

Incluye dos **recursos interactivos en HTML** para explorar los marcos en clase,
además del deck y los instrumentos de evaluación de la unidad.

---

## Contenido

| Archivo | Tipo | Descripción |
|---|---|---|
| [`zachman_interactivo.html`](zachman_interactivo.html) | Interactivo | Matriz 6×6 del **Zachman Framework**. Cada celda muestra el artefacto que produce y su aplicación práctica. |
| [`togaf_adm_interactivo.html`](togaf_adm_interactivo.html) | Interactivo | Ciclo **TOGAF ADM** (fases A–H + Requirements Management). Cada fase muestra entradas, salidas, artefactos y ejemplos. |
| [`AREM_S1_Deck_Reto_U1.pdf`](AREM_S1_Deck_Reto_U1.pdf) | PDF | Deck de la sesión y planteamiento del reto de la Unidad 1. |
| [`AREM_S1_Instrumentos_1.pdf`](AREM_S1_Instrumentos_1.pdf) | PDF | Instrumentos de evaluación (rúbricas / criterios) de la sesión. |

---

## Cómo abrir los interactivos

Los dos archivos `.html` son **autocontenidos**: todo el HTML, CSS y JavaScript va
dentro de un solo archivo. No requieren instalación, ni servidor, ni conexión a
internet, ni dependencias externas.

### Opción 1 — Desde el computador (recomendada)

1. Descarga el repositorio: botón verde **`Code` → `Download ZIP`**, y descomprímelo.
   (O clónalo: `git clone https://github.com/CesarAVegaF312/AREM-S1_Marcos_y_Capacidades-repositorio.git`)
2. Entra a la carpeta y haz **doble clic** sobre `zachman_interactivo.html` o
   `togaf_adm_interactivo.html`.
3. Se abrirá en tu navegador por defecto. Listo.

> Si el doble clic abre otro programa (por ejemplo un editor de texto): clic derecho →
> **Abrir con** → Chrome / Edge / Firefox.

### Opción 2 — Descargar un solo archivo

En GitHub, abre el archivo `.html`, entra a la vista **Raw** y guarda la página con
`Ctrl + S` (`Cmd + S` en Mac). Luego ábrela con doble clic.

> ⚠️ Al hacer clic sobre un `.html` **dentro de GitHub no se ve el interactivo**:
> GitHub muestra el código fuente, no lo ejecuta. Hay que descargarlo o publicarlo
> con GitHub Pages (Opción 3).

### Opción 3 — En línea con GitHub Pages

Con **GitHub Pages** los interactivos se abren con un solo link, sin descargar nada.
Requiere activarlo una vez (lo hace el dueño del repositorio):

1. En el repositorio, entra a la pestaña **`Settings`** (arriba a la derecha).
2. En el menú lateral izquierdo, baja hasta **`Pages`** (sección *Code and automation*).
3. En **Build and deployment → Source**, elige **`Deploy from a branch`**.
4. En **Branch**, selecciona **`main`** y carpeta **`/ (root)`**. Pulsa **`Save`**.
5. Espera 1–2 minutos (se lanza un despliegue; puedes seguirlo en la pestaña
   **`Actions`**). Al terminar, la misma página de *Pages* muestra el enlace del sitio
   con un aviso verde: *"Your site is live at …"*.

Una vez activado, estos son los enlaces para compartir con los estudiantes:

- **Zachman:** https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/zachman_interactivo.html
- **TOGAF ADM:** https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/togaf_adm_interactivo.html

> **Notas**
> - El repositorio debe ser **público** para usar Pages con una cuenta gratuita.
> - Si obtienes **404**, revisa que el despliegue haya terminado y que el nombre del
>   archivo en el link esté escrito exactamente igual (distingue mayúsculas).
> - Cada `git push` a `main` vuelve a desplegar el sitio automáticamente.
---

## Cómo usarlos

**Zachman interactivo** — 👆 Haz clic en cualquier **celda** de la matriz para ver qué
artefacto produce y cómo se aplica en la práctica. Las columnas son las preguntas
(*Qué, Cómo, Dónde, Quién, Cuándo, Por qué*) y las filas los niveles de perspectiva.
La leyenda de colores identifica cada columna.

**TOGAF ADM interactivo** — 👆 Haz clic en cualquier **fase** del ciclo (A a H) o en la
banda central de **Requirements Management** para ver sus entradas, salidas,
artefactos y ejemplos prácticos.

En pantallas pequeñas la matriz de Zachman se desplaza horizontalmente.

---

## Requisitos

Cualquier navegador moderno: Chrome, Edge, Firefox o Safari (versiones recientes).
No se requiere internet una vez descargados los archivos.

---

## Licencia

Publicado bajo la **Licencia MIT** — ver [`LICENSE`](LICENSE).

Puedes usar, adaptar y redistribuir este material (incluido el código de los
interactivos) libremente, conservando el aviso de copyright y la atribución.

*Nota: TOGAF® es marca registrada de The Open Group y el Zachman Framework™ de
Zachman International. Este repositorio contiene material docente que los explica;
la licencia MIT aplica a estos materiales, no a los marcos originales.*
