# GUÍA DE PUBLICACIÓN EN EDUCAMADRID
## RETO 1: LOS GUARDIANES DEL JUEGO · VERSIÓN VIDEOJUEGO GENIALLY
**Día de la Constitución Española 2026**  
**Subdirección General de Formación del Profesorado · Consejería de Educación, Ciencia y Universidades · Comunidad de Madrid**

---

### 🎮 Descripción de esta Versión

Esta carpeta contiene la **Versión Videojuego Interactivo (Tipo Genially)** del Reto 1. Ha sido creada como una alternativa dinámica e inmersiva pensada para **Pizarras Digitales Interactivas (PDI)**, tablets y aulas de informática.

A diferencia del portal web convencional:
* **Estructura en Diapositivas 16:9:** Navegación por pantallas fluidas sin scroll vertical, como una presentación gamificada de Genially o un videojuego de consola.
* **HUD Superior de Videojuego:** Barra superior con avatar seleccionado, corazones de vitalidad (❤️❤️❤️), puntos de experiencia (XP), mochila de inventario flotante y controles de audio.
* **Audio Retro Sintetizado (Web Audio API):** Sin archivos de audio externos; genera efectos sonoros (monedas, golpes, forja, victoria) y música ambiental chiptune 8-Bit en tiempo real.
* **Mecánicas Lúdicas:**
  1. *Selección de Personaje:* Aisha (Estrategia), Hugo (Deporte), Lola (Alquimista Verde) e Iker (Inclusión).
  2. *Cristales Constitucionales:* Activación de los Artículos 14, 43.3, 45 y 46 de la C.E.
  3. *Mapa Mundial de 19 Regiones:* Rescate de los 19 juegos populares en un mapa vectorial SVG interactivo.
  4. *Taller de Fabricación con materiales de reciclaje y Ecodiseño:* Crisol de transmutación para combinar residuos domésticos con módulos de accesibilidad.
  5. *Criptograma de la Mazmorra:* Murdoku lógico gamificado con botones táctiles.
  6. *Boss Battle:* Combate por turnos contra "La Sombra del Olvido".
  7. *Salón de la Victoria:* Emisión del Carnet / Diploma Oficial de Guardián/a listo para imprimir.

---

### 📦 Contenido de esta Carpeta

* **`index.html` (o `reto1_videojuego_genially.html`):** Videojuego completo autónomo en HTML5/CSS3/JS puro.
* **`Artefactos/`:** Ilustración oficial del *Bosque de los Derechos* e insignias de la Semana Constitucional.
* **`LOGOS_v1/`:** Logotipos oficiales de la Comunidad de Madrid.
* **`PDFs_Imprimibles_Aula/`:** Cuadernos complementarios de aula en PDF.

---

### 🚀 Opciones de Despliegue en EducaMadrid

#### Opción 1: Embebido en Iframe (Recomendada para Aulas Virtuales)
```html
<div style="position: relative; width: 100%; max-width: 1240px; aspect-ratio: 16 / 9; margin: 20px auto;">
  <iframe 
    src="URL_ALOJAMIENTO/index.html" 
    width="100%" 
    height="100%" 
    style="border: none; border-radius: 16px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);" 
    allow="fullscreen; autoplay"
    title="Reto 1: Los Guardianes del Juego - Modo Videojuego">
  </iframe>
</div>
```

#### Opción 2: Ejecución Local / Offline en el Aula
1. Descarga la carpeta.
2. Haz doble clic en `index.html`.
3. Funciona al 100% sin conexión a internet y sin descargas externas.
