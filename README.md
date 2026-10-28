# AREM S1 — Marcos y Capacidades

Material de la **Sesión 1** del curso *Arquitectura Empresarial* (AREM), Unidad 1:
**Fundamentos y Alineación Estratégica de Arquitectura Empresarial**. Maestría en Ingeniería de
Software, Universidad de La Sabana.

La unidad va de tener una organización elegida a **diagnosticarla**: con qué lente se la mira, cómo
se acota lo que se va a analizar, qué sabe hacer la organización y de dónde sale cada brecha. Marcos
de referencia: **TOGAF® Standard, 10th Edition** (el ciclo ADM) y el **Zachman Framework™**.

Las actividades de la unidad, tal como están en la plataforma:

- **Actividad 1.1 — Presentación del reto** · individual · formativa, sin calificación · 4 horas.
  - **Entregables:** una reflexión individual de **1 a 2 páginas** en PDF y norma APA 7 —cuál creen
    que es el modelo operativo de su organización y por qué, y qué marcos les parecen pertinentes y
    por qué—, y la **ficha de caracterización del negocio (F-05)**, consolidada por el grupo.
  - La retroalimentación es oral y se da con la rúbrica formativa **F-10**.
- **Actividad 1.2 — Diagnóstico de madurez y alineación estratégica** · grupal, de **3 a 4
  integrantes** · 30 % · 20 horas.
  - **Entregable:** un informe de diagnóstico en PDF, de **máximo 15 páginas**, en **norma APA 7**.
    Debe incluir: modelo operativo caracterizado con evidencias, un marco de referencia aplicado a
    las cuatro capas, el mapa de capacidades con soporte tecnológico valorado, el nivel de madurez en
    una escala de cinco niveles, tres brechas priorizadas con su impacto estratégico y cinco
    principios arquitectónicos justificados.
  - Se califica con la rúbrica publicada en el aula; los **dos criterios de mayor peso son brechas y
    principios**.
  - **Los formatos F-05 a F-12 no se suben:** son el borrador de las secciones del informe.

---

## Empiecen aquí

**Todo el material se abre desde aquí, sin descargar nada:**
<https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/>

Desde esa portada salen los documentos, las dos herramientas y la
[presentación de la sesión](https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/presentacion.html).

1. **Recorran la [presentación de la sesión](presentacion.html).** Las 21 diapositivas, con los seis
   ejemplos guiados: cada formato lleno, paso a paso, con el caso del docente.
2. **Abran las dos herramientas** mientras leen: el [ciclo ADM](interactivos/togaf_adm_interactivo.html)
   para saber qué fases entran en esta unidad, y la [matriz de Zachman](interactivos/zachman_interactivo.html)
   para encontrar qué no está escrito en su organización.
3. **Llenen los [Instrumentos F-05 a F-12](documentos/AREM_S1_Instrumentos.pdf)** en el orden en que
   los pide la presentación. El orden importa: **primero se escriben las evidencias, después se
   decide el cuadrante del modelo operativo.** Un cuadrante elegido antes de la evidencia es una
   intuición con tabla.

Para trabajar sin conexión, descarguen el repositorio (botón verde **`Code` → `Download ZIP`**),
descomprímanlo y hagan doble clic en `index.html`: la portada abre todo lo demás.

---

## Estructura del repositorio

```text
AREM-S1_Marcos_y_Capacidades-repositorio/
├── index.html          ← portada: abre desde aquí todo lo demás
├── presentacion.html   ← las 21 diapositivas de la sesión, animadas
├── README.md
├── LICENSE
├── interactivos/       ← TOGAF ADM y Zachman en HTML
└── documentos/         ← deck de la sesión e instrumentos F-05 a F-12 (PDF)
```

> Las dos herramientas estuvieron un tiempo en la raíz del repositorio. En la raíz quedan
> `togaf_adm_interactivo.html` y `zachman_interactivo.html` como **reenvíos**, para que sigan
> funcionando los enlaces que ya se repartieron. No hay que borrarlos.

### La clase

| Archivo | Descripción |
|---|---|
| [`presentacion.html`](presentacion.html) | La sesión completa en el navegador: 21 diapositivas animadas, con índice (**I**), glosario de códigos (**G**), cronómetro del taller (**T**) y modo de lectura para el teléfono (**L**). |
| [`documentos/AREM_S1_Deck_Reto_U1.pdf`](documentos/AREM_S1_Deck_Reto_U1.pdf) | Las mismas 21 diapositivas en PDF, para descargar o imprimir. |

La sesión va en tres bloques, como el resto del curso: **primero qué significa** —describir frente a
diagnosticar, los cuatro marcos, qué se toma del ciclo ADM, qué es una capacidad y cuál es la cadena
que sostiene el informe—, **después seis ejemplos guiados** —un formato por ejemplo, recorrido con el
caso del docente— y **después el taller en salas**, del que cada grupo sale con el F-05 y el F-06 en
borrador.

### Recursos interactivos — carpeta `interactivos/`

| Archivo | Descripción |
|---|---|
| [`togaf_adm_interactivo.html`](interactivos/togaf_adm_interactivo.html) | Ciclo **TOGAF ADM** (fases A–H más Requirements Management). Cada fase muestra entradas, salidas, artefactos y ejemplos. En la Unidad 1 solo entran la preliminar, la A y la B; las demás se muestran para explicar por qué quedan fuera. Se reutiliza en la Sesión 2. |
| [`zachman_interactivo.html`](interactivos/zachman_interactivo.html) | Matriz 6×6 del **Zachman Framework**. Cada celda muestra el artefacto que debería existir y su aplicación práctica. Es la base de la rejilla **F-12**: una celda vacía no es un problema de documentación, es una dependencia de personas. |

### Documentos — carpeta `documentos/`

| Archivo | Tipo | Descripción |
|---|---|---|
| [`AREM_S1_Instrumentos.pdf`](documentos/AREM_S1_Instrumentos.pdf) | PDF · se llena | Los ocho formatos **F-05 a F-12**: caracterización y modelo operativo, mapa de capacidades, madurez de alineación negocio–TI, brecha arquitectónica, principios, rúbrica formativa, verificación previa y rejilla de vacíos documentales (Zachman). |
| [`AREM_S1_Deck_Reto_U1.pdf`](documentos/AREM_S1_Deck_Reto_U1.pdf) | PDF | Las 21 diapositivas del encuentro sincrónico y el planteamiento del reto de la Unidad 1. |

---

## Las otras sesiones del curso

| Unidad | Repositorio |
|---|---|
| Unidad 2 · Modelado y decisión | [AREM-S2_Modelado_y_Decision](https://github.com/CesarAVegaF312/AREM-S2_Modelado_y_Decision) |
| Unidad 3 · Gobierno y control | [AREM-S3_Gobierno_y_Control](https://github.com/CesarAVegaF312/AREM-S3_Gobierno_y_Control) |
| Unidad 4 · Transformación y roadmap | [AREM-S4_Transformacion_y_Roadmap](https://github.com/CesarAVegaF312/AREM-S4_Transformacion_y_Roadmap) |

---

## Cómo abrir los archivos

Los `.html` de este repositorio —la presentación y las dos herramientas— son **autocontenidos**: todo
el HTML, el CSS y el JavaScript va dentro de un solo archivo. No requieren instalación, ni servidor,
ni conexión a internet, ni dependencias externas.

### Opción 1 — En línea, con un solo enlace (recomendada)

Todo está publicado con GitHub Pages:

| | Enlace |
|---|---|
| Portada con todo | <https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/> |
| Presentación de la sesión | <https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/presentacion.html> |
| TOGAF ADM | <https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/interactivos/togaf_adm_interactivo.html> |
| Zachman | <https://cesaravegaf312.github.io/AREM-S1_Marcos_y_Capacidades-repositorio/interactivos/zachman_interactivo.html> |

### Opción 2 — Desde el computador

1. Descarguen el repositorio: botón verde **`Code` → `Download ZIP`**, y descomprímanlo.
   (O clónenlo: `git clone https://github.com/CesarAVegaF312/AREM-S1_Marcos_y_Capacidades-repositorio.git`)
2. Entren a la carpeta y hagan **doble clic** sobre `index.html`.

> Si el doble clic abre otro programa (por ejemplo un editor de texto): clic derecho →
> **Abrir con** → Chrome / Edge / Firefox.

> **Atención:** al hacer clic sobre un `.html` **dentro de GitHub no se ve el contenido**: GitHub muestra el
> código fuente, no lo ejecuta. Hay que abrirlo desde los enlaces de la Opción 1 o descargarlo.

---

## Cómo usarlos

**Presentación** — Se avanza con las flechas, con la barra espaciadora o tocando la pantalla.
**I** abre el índice, **G** el glosario de códigos, **T** el cronómetro del taller, **F** la pantalla
completa y **?** la lista de atajos. En el teléfono, el botón **Lectura** muestra las 21 diapositivas
una debajo de otra.

**TOGAF ADM interactivo** — Clic en cualquier **fase** del ciclo (A a H) o en la banda central de
**Requirements Management** para ver sus entradas, salidas, artefactos y ejemplos prácticos.

**Zachman interactivo** — Clic en cualquier **celda** de la matriz para ver qué artefacto produce y
cómo se aplica en la práctica. Las columnas son las preguntas (*Qué, Cómo, Dónde, Quién, Cuándo, Por
qué*) y las filas los niveles de perspectiva. En pantallas pequeñas la matriz se desplaza
horizontalmente.

---

## Requisitos

Cualquier navegador moderno: Chrome, Edge, Firefox o Safari (versiones recientes). No se requiere
internet una vez descargados los archivos.

---

## Licencia

Este material se distribuye bajo la licencia [Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es) — ver [`LICENSE`](LICENSE).

Pueden **usar, adaptar o compartir** este contenido, incluido el código de los interactivos, con fines educativos, siempre que:

1. Se reconozca la autoría del profesor **César Augusto Vega Fernández**.
2. No se utilice con fines comerciales.
3. Las obras derivadas se distribuyan bajo la misma licencia.

*Nota: TOGAF® es marca registrada de The Open Group y el Zachman Framework™ de Zachman
International. Este repositorio contiene material docente que los explica; la licencia aplica a
estos materiales, no a los marcos originales.*
