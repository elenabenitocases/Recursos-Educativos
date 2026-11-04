# GUÍA DE IMPLEMENTACIÓN EN EDUCAMADRID
## Reto 1: Los Guardianes del Juego · Día de la Constitución 2026
**Subdirección General de Formación del Profesorado**  
**Consejería de Educación, Ciencia y Universidades · Comunidad de Madrid**

---

### 📦 Contenido de este Paquete de Entrega (Versión Original Web)

Esta carpeta contiene todo lo necesario para publicar el **Reto 1 interactivo en su Versión Original Web** en el entorno de **EducaMadrid** (apartado de *Semanas Temáticas de Innovación y Formación*):

1. **`index.html` (o `reto1_guardianes_juego.html`):**
   - **Aplicación Web Interactiva Oficial:** Portal educativo estructurado por misiones mediante pestañas de navegación institucional.
   - **Misión 1 (Mapa de España):** Mapa vectorial SVG interactivo con las 17 Comunidades Autónomas y las 2 Ciudades Autónomas, permitiendo explorar y rescatar los 19 juegos tradicionales.
   - **Misión 2 (Laboratorio de Ecodiseño e Inclusión):** Fichas técnicas para construir materiales con residuos reciclados (Art. 45 CE) y adaptaciones inclusivas para diversidad funcional (Art. 14 CE).
   - **Misión 3 (Murdoku Lógico):** Criptograma de deducción lógica 8x8 con verificación en tiempo real y modalidad adaptada para Educación Infantil.
   - **Misión 4 (Consagración y Carnet):** Desbloqueo de la Insignia Oficial y generación del Carnet de Guardián/a imprimible.
   - **Autónoma y ligera:** Sin dependencias externas ni librerías pesadas (100% compatible con cortafuegos escolares).

2. **`Artefactos/`:**
   - `insignia_reto1.png`: Insignia digital oficial del reto (*Escudo del Bosque de los Derechos*).
   - `Reto 1_El Bosque de los derechos.jpg`: Ilustración del mundo narrativo.
   - `Insignias retos.jpg`: Lámina con los 4 emblemas de la Semana Constitucional.

3. **`LOGOS_v1/` y logos institucionales:**
   - `logo_comunidad_transparente.png` y `logo_comunidad_bordeblanco.png`: Identidad visual oficial de la Comunidad de Madrid.
   - Banners de cabecera en varias resoluciones para el portal de Innovación y Formación.

4. **`PDFs_Imprimibles_Aula/` (Documentación Oficial por Etapas):**
   - `RETO 1_ACTIVIDADES INFANTIL_LOS GUARDIANES DEL JUEGO.pdf`: Cuaderno adaptado a Educación Infantil.
   - `RETO 1_ACTIVIDADES PRIMARIA_LOS GUARDIANES DEL JUEGO.pdf`: Cuaderno adaptado a Educación Primaria.
   - `RETO 1_ACTIVIDADES SECUNDARIA_LOS GUARDIANES DEL JUEGO.pdf`: Cuaderno adaptado a Educación Secundaria.
   - `RETO 1_INSTRUCCIONES GENERALES_LOS GUARDIANES DEL JUEGO.pdf`: Guía docente con temporización y metodologías.
   - `RETO 1_MATERIALES (ÍNDICE)_LOS GUARDIANES DEL JUEGO.pdf`: Catálogo índice de recursos del Reto 1.
   - `RETO 1_FICHAS_JUEGOS TRADICIONALES.pdf`: Fichas de investigación de juegos populares por CCAA.
   - `RETO 1_MURDOKU CONSTITUCIONAL.pdf`: Matriz lógica Murdoku de aula fotocopiable.
   - `RETO 1_CARNET_GUARDIANES DEL JUEGO.pdf`: Carnets oficiales de agente guardián.
   - `RETO 1_ANEXOS Y MATERIALES POR ETAPAS.pdf`: Hojas de trabajo complementarias.

---

### 🚀 Opciones de Publicación en EducaMadrid

#### Opción 1: Inserción embebida mediante `<iframe>` (Recomendada)
Para integrar el reto interactivo directamente dentro de un artículo, noticia o página web de EducaMadrid (Drupal, Liferay o WordPress de centros):

```html
<div style="position: relative; width: 100%; max-width: 1360px; margin: 20px auto;">
  <iframe 
    src="URL_DONDE_SE_ALOJE/index.html" 
    width="100%" 
    height="920" 
    style="border: none; border-radius: 14px; box-shadow: 0 4px 20px rgba(0,0,0,0.12); width: 100%; min-height: 850px;" 
    allow="autoplay; fullscreen"
    title="Reto 1: Los Guardianes del Juego - Semana de la Constitución 2026">
  </iframe>
</div>
```

#### Opción 2: Alojamiento en la Mediateca / Espacio Web
1. Subir la carpeta completa `ENTREGA_EDUCAMADRID_RETO_1` al gestor de archivos o mediateca de EducaMadrid.
2. Crear un botón o enlace directo en el portal:
   * **Texto del enlace:** `🎮 Jugar al Reto 1: Los Guardianes del Juego (Interactivo PDI)`
   * **Destino:** Enlace al archivo `index.html`.

#### Opción 3: Paquete descargable para centros (Uso Offline / Local)
- El archivo comprimido `ENTREGA_EDUCAMADRID_RETO_1.zip` se puede ofrecer como botón de descarga directa para el profesorado:
  > *"¿No tienes buena conexión a internet en el aula o pabellón? Descarga este paquete ZIP, descomprímelo en un pendrive o PC y haz doble clic en `index.html` para jugar sin conexión."*

---

### 🎯 Ficha Pedagógica del Recurso
* **Etapas:** Educación Primaria (3º a 6º) y 1º-2º ESO (con modalidad adaptada para Educación Infantil 3-6 años).
* **Duración estimada:** 25 – 30 minutos (sesión única).
* **Artículos Constitucionales:**
  * **Artículo 46 CE:** Deber cívico y garantía pública de conservar y enriquecer el patrimonio cultural e histórico (el patrimonio lúdico inmaterial de los pueblos de España).
  * **Artículo 43.3 CE:** Fomento de la educación física, el deporte y la adecuada utilización del ocio.
  * **Artículo 14 CE:** Igualdad e inclusión sin discriminación (aplicada en las adaptaciones para movilidad reducida o diversidad sensorial).
  * **Artículo 45 CE:** Cuidado del medio ambiente y reciclaje creativo de materiales.
* **Recompensa final:** Desbloqueo de la Insignia Oficial y emisión personalizada del **Carnet Oficial de Guardián/a del Juego 2026**, imprimible directamente en PDF desde el navegador.

---
*Subdirección General de Formación del Profesorado · Dirección General de Bilingüismo y Calidad de la Enseñanza · Comunidad de Madrid*
