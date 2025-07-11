
# Puente Condell: Memoria Proyectada

## 🎯 Descripción General

**Puente Condell: Memoria Proyectada** es una instalación audiovisual que reconstruye la historia del entorno del río Mapocho bajo el Puente Condell en Santiago de Chile. A través de proyecciones conceptuales en su base, se reaniman memorias sociales, políticas y culturales, desde la década de 1940 hasta el 2020, abordando temas como protestas, violencia, marginalidad, migración y transformación urbana.

## 🎥 Concepto

La propuesta utiliza **sombras animadas proyectadas** para representar escenas clave a lo largo del tiempo. Estas proyecciones no muestran eventos de forma literal, sino mediante siluetas simbólicas que evocan la atmósfera de cada época, instalando así una reflexión poética sobre la memoria urbana y su permanencia en los márgenes.

## 🧠 Contexto Teórico

- El proyecto se sitúa en la intersección entre **arte urbano, memoria colectiva** y **visualización crítica**.
- Se inspira en el uso del espacio público como soporte narrativo.
- Toma referentes de instalaciones audiovisuales, mapping, teatro de sombras y archivo histórico.
- Utiliza elementos de la **cibernética del diseño** y del **diseño especulativo** para crear una interfaz simbólica de interacción.

## 🧩 Escenas Históricas Incluidas

1. Solo el Mapocho (1940) ✅  
2. Construcción inicial del puente (1950) ❓  
3. Reparación estructural (1960) ❓  
4. Regatas universitarias (1965) ✅  
5. Bromas de ahorcados universitarios (1965) ⏳  
6. Construcción de la iluminación (1980) ✅  
7. Marcha del “No” con canto “Porque diga lo que diga...” (1988) ✅  
8. Robos en la noche (1990) ✅  
9. Candados del amor (2000–2010) ⏳  
10. Retiro de candados por sobrepeso (2018) ❓  
11. Muñecos colgando (2018) ⏳  
12. Marchas del estallido social (2019) ⏳  
13. Carpas y consumo de drogas bajo el puente (2019–2021) ✅  

## 🛠️ Proceso Técnico

### 🧱 Modelado y Animación 3D
- Software: **Blender**
- Se realizaron modelados de entorno urbano, personajes, elementos simbólicos (candados, fogatas, pancartas).
- Uso de materiales texturizados tipo cemento envejecido.
- Iluminación direccional tipo "sol" para sombras realistas.
- Renderizado en formato secuencia y video (.mp4).

### 🎛️ Proyección e Interacción
- Software: **RESOLUME**
- Integración con control OSC.
- Diseño de interfaz de control para escenas.
- Comunicación establecida vía **Python (Flask + python-osc)**.

### 🌐 Interfaz Digital
- Interfaz HTML desarrollada para debug/control local.
- Comunicación vía WebSocket o HTTP con servidor Python.

### 🧠 Inspiración y Estado del Arte

Una de las principales referencias para este proyecto es la obra **"The Visitors" (2012)** del artista islandés **Ragnar Kjartansson**, expuesta en el SFMOMA y otros museos del mundo. Esta instalación de video multicanal presenta a músicos tocando una composición en vivo desde habitaciones separadas dentro de una casa, grabados simultáneamente y proyectados en pantallas independientes que rodean al espectador. La posibilidad de enfocarse en distintas escenas según la posición o la intención del visitante genera una experiencia fragmentada, íntima y altamente emocional. 

Inspirado por esta lógica de navegación entre capas narrativas, el presente proyecto incorpora una **interfaz HTML** que permite activar escenas específicas de forma puntual, otorgando al espectador cierto grado de agencia sobre la narrativa y replicando la experiencia de recorrer una memoria distribuida en el espacio.


## 🧪 Ejecución del Prototipo

1. Servidor Python activo en red local.
2. RESOLUME escucha señales OSC en el puerto 8010.
3. Python interpreta la zona y envía señal a RESOLUME.
5. RESOLUME cambia de escena proyectada.

## 🖼️ Fotografías del proceso y recursos visuales

### Modelos 3D de grafitis (texturas para las animaciones)

<img src="fotos/grafiti1.png" alt="Grafiti 1" width="200"/>
<img src="fotos/grafiti2.png" alt="Grafiti 2" width="200"/>
<img src="fotos/grafiti3.png" alt="Grafiti 3" width="200"/>
<img src="fotos/grafiti4.png" alt="Grafiti 4" width="200"/>
<img src="fotos/grafiti5.png" alt="Grafiti 5" width="200"/>

### Prototipos del tambor metálico intervenido para proyección

<img src="fotos/p1 .jpg" alt="Tambor pintado" width="200"/>
<img src="fotos/p2 .jpg" alt="Tambor negro" width="200"/>

### Texturas y referencias de muros intervenidos

<img src="fotos/p4 .jpg" alt="Muro intervenido 1" width="200"/>
<img src="fotos/p5 .jpg" alt="Muro intervenido 2" width="200"/>
<img src="fotos/p6 .jpg" alt="Muro intervenido 3" width="200"/>
<img src="fotos/p7 .jpg" alt="Muro intervenido 4" width="200"/>

### Texturas urbanas utilizadas en las escenas

<img src="fotos/t1.jpg" alt="Textura 1" width="200"/>
<img src="fotos/t2.jpg" alt="Textura 2" width="200"/>
<img src="fotos/t3.jpg" alt="Textura 3" width="200"/>
<img src="fotos/t6 .jpg" alt="Textura 4" width="200"/>
<img src="fotos/t8 .jpg" alt="Textura 5" width="200"/>



## 🔊 Sonido

- Cada escena incluye **paisajes sonoros realistas**: agua, viento, gritos de protesta, pájaros o fuego según la escena.
- Audios obtenidos de bibliotecas de stock gratuitas como [Freesound.org](https://freesound.org) y [Pixabay Audio](https://pixabay.com/sound-effects/).

# Descripción de Escenas – Puente Condell: Memoria Proyectada

Este documento contiene una descripción conceptual y narrativa de cada una de las escenas proyectadas en el proyecto audiovisual interactivo "Puente Condell: Memoria Proyectada".

---

## ✅ Escena 1: Solo el Mapocho – 1940
Una proyección de sombras abstractas muestra la silueta del Mapocho. 

---

## ✅ Escena 2: Regatas Universitarias – 1965
Se proyectan sombras de botes remando en conjunto, evocando las tradicionales regatas de estudiantes universitarios en el río. Las figuras se coordinan rítmicamente, remarcando el espíritu deportivo y académico de la época.

---

## ⏳ Escena 3: Bromas de suicidio universitarios – 1965
Sombras suspendidas representan los cuerpos ficticios utilizados por estudiantes en protestas o bromas. El tono es ambiguo, entre lo lúdico y lo inquietante. Las sombras cuelgan en silencio desde la estructura del puente.

---

## ✅ Escena 4: Construcción de iluminación del puente – 1980
La escena muestra siluetas de trabajadores instalando focos y postes, iluminando progresivamente el espacio. Las sombras de escaleras y herramientas acompañan el gesto de modernización nocturna del puente.

---

## ✅ Escena 5: Joven en marcha del “No” cantando – 1988
Una figura juvenil proyecta su sombra caminando con determinación, mientras en su mano se eleva un cartel con la frase “Porque diga lo que diga, yo soy libre de pensar”. Se alude a las manifestaciones contra la dictadura de Pinochet.

---

## ✅ Escena 6: Robos en la noche – 1990
Siluetas rápidas y tensas cruzan la escena: una persona se acerca sigilosamente a otra, en un gesto de asalto. Las sombras se proyectan de forma parcial y fragmentada, insinuando el carácter clandestino del acto.

---


## ✅ Escena 7: Carpas y droga bajo el puente – 2019–2021
Una sombra estática muestra una tienda de campaña mal armada, mientras figuras humanas se desplazan en actitud errática a su alrededor. Proyección sombría y lenta que refleja marginalidad y abandono urbano.

---


## 🗂️ Estructura del Repositorio

```
PuenteCondell_MemoriaProyectada/
├── blender_scenes/        # Archivos .blend y renders
├── madmapper/             # Presets y archivos de proyecto MadMapper
├── python_server/         # Código para comunicación OSC y visión computacional
├── interface/             # HTML, CSS y JS para interfaz de control
├── audio/                 # Clips de sonido utilizados
├── docs/                  # Láminas y textos de apoyo
└── README.md
```

## 📚 Créditos

- Proyecto desarrollado por **Emilio Abarca**  
- Carrera: **Diseño en Interacción Digital** – Universidad del Desarrollo  
- Software libre y herramientas utilizadas: Blender, Python, MadMapper, OpenCV, Audacity, HTML/CSS/JS

---

> “Las ciudades también sueñan. Este proyecto proyecta esas sombras que persisten bajo el concreto.”
