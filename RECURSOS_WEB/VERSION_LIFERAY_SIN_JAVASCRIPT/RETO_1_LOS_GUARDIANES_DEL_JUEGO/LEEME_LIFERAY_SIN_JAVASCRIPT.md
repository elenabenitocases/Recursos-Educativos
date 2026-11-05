# 🏛️ Comunidad de Madrid — Día de la Constitución 2026
## Reto 1: Los Guardianes del Juego · Versión 100% Sin JavaScript (HTML5 + CSS3 puro)

### 📌 ¿Por qué esta versión para Liferay / EducaMadrid?
Liferay CMS cuenta por defecto con directivas de seguridad estrictas (*OWASP / AntiSamy HTML Sanitizer*) que eliminan etiquetas `<script>`, llamadas a librerías y eventos interactivos en línea (`onclick`, `onload`, `javascript:...`).

Para superar esta limitación técnica **sin perder la riqueza pedagógica ni la interactividad visual**, se han desarrollado estas versiones que funcionan con **0 bytes de JavaScript**:
1. **Navegación por misiones con la técnica *CSS Radio Hack*:** Se emplean selectores nativos de CSS3 (`:checked ~`) vinculados a etiquetas `<label>` para alternar instantáneamente entre pestañas sin recargas de página.
2. **Exploración de los 19 juegos tradicionales con `<details>` y `<summary>`:** Estándar nativo de HTML5 soportado por todos los navegadores modernos y permitido al 100% por Liferay.
3. **Casos prácticos y Murdoku con comprobación inmediata:** Al marcar la opción correcta mediante radio buttons, el CSS activa automáticamente los paneles de felicitación y justificación constitucional.
4. **Impresión nativa del diploma oficial:** La regla `@media print` formatea automáticamente el carnet oficial a tamaño A4 horizontal apaisado al pulsar **Ctrl + P** (o seleccionar *Imprimir* en el navegador), ocultando cabeceras y menús sin requerir `window.print()`.

---

### 📂 Archivos disponibles en esta carpeta:

| Archivo | Formato | Descripción |
| :--- | :---: | :--- |
| **`reto1_web_sin_javascript.html`** | Web Portal | Versión web completa con las 4 misiones (19 juegos, laboratorio de inclusión, murdoku y carnet oficial imprimible). |
| **`reto1_canva_sin_javascript.html`** | Infografía 16:9 | Suite horizontal adaptada para PDI y pantallas panorámicas con visor de estaciones en CSS puro. |
| **`logo_comunidad_transparente.png`** | Imagen PNG | Logo institucional oficial de la Comunidad de Madrid. |
| **`logo_comunidad_bordeblanco.png`** | Imagen PNG | Variante de logo institucional con borde blanco. |
| **`Artefactos/`** | Carpeta | Ilustraciones, portadas e insignias oficiales del Reto 1. |

---

### 🚀 Cómo implementarlo en Liferay:

#### Método 1: Pegar el código en un Contenido Web (WCM)
1. En el panel de control de Liferay, crea un nuevo **Contenido Web** (o edita la página correspondiente).
2. En el editor de texto enriquecido, pulsa el botón **«Código fuente»** (o modo HTML `<>`).
3. Copia el contenido íntegro de `reto1_web_sin_javascript.html` o `reto1_canva_sin_javascript.html` y pégalo.
4. Guarda y publica. Al **no contener ninguna etiqueta `<script>` ni eventos `onclick`**, el sanitizador de Liferay **no eliminará nada** y la interactividad funcionará al 100%.

#### Método 2: Subir los archivos HTML y recursos a la Mediateca / Gestor de Documentos
1. Sube la carpeta completa a la mediateca o servidor web estático de EducaMadrid.
2. Enlaza el archivo directamente en el menú de navegación o ábrelo en una ventana nueva.

---
**Comunidad de Madrid · Consejería de Educación, Ciencia y Universidades**  
*Semanas Temáticas EducaMadrid 2026*
