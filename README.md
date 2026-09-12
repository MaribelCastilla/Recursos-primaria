# 🗺️ España: Geografía Escolar

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![SVG](https://img.shields.io/badge/SVG-Vector_Graphics-FFB13B?style=flat-square&logo=svg&logoColor=white)](https://www.w3.org/Graphics/SVG/)
[![Autocontenido](https://img.shields.io/badge/Single--File-100%25_Autónomo-10b981?style=flat-square)](https://github.com/)
[![Licencia](https://img.shields.io/badge/Licencia-Educativa-blue?style=flat-square)](LICENSE)

> Aplicación web interactiva y didáctica para el aprendizaje, repaso y evaluación de la **geografía política y física de España**, diseñada específicamente para estudiantes de Educación Primaria y Secundaria, adaptable a pizarras digitales, ordenadores, tablets y dispositivos móviles.

---

## 🌟 Características Principales

### 🏛️ 1. Mapa Político Interactivo
- **Comunidades Autónomas**: Delineación precisa de las 17 comunidades autónomas y las 2 ciudades autónomas (Ceuta y Melilla), con sus respectivas capitales autonómicas.
- **Provincias de España**: Visualización de las 52 provincias con sus capitales señaladas con estrella dorada (⭐) en su ubicación geográfica exacta.
- **Alto contraste cromático**: Paleta de colores didáctica optimizada para facilitar la diferenciación territorial inmediata:
  - **Madrid**: Azul índigo (`#4338ca` / `#4f46e5`).
  - **Asturias**: Azul ultramar (`#1d4ed8` / `#2563eb`).
  - **Cantabria**: Chocolate (`#78350f` / `#92400e`).
  - **Aragón**: Verde musgo con tres tonalidades armónicas para sus provincias (Huesca `#65a30d`, Zaragoza `#4d7c0f` y Teruel `#365314`).
  - **Extremadura**: Café con tonos diferenciados para Cáceres (`#8c5a3c`) y Badajoz (`#54331c`).
- **Contorno realista de Portugal**: Geometría cartográfica de alta definición (*Natural Earth 10m*) con encaje continuo a lo largo de la frontera peninsular.
- **Fronteras y países limítrofes**: Representación de Portugal, Francia, Marruecos, Andorra y recuadro proporcional para las Islas Canarias.

### ⛰️ 2. Mapa Físico y Relieve Esculpido
- **Relieve en plastilina**: Mapa base visual artístico en textura de plastilina esculpida, codificado directamente en la aplicación.
- **Relieve y Cumbres**: Sistemas montañosos y cordilleras delimitados por polígonos interactivos (Pirineos, Cordillera Cantábrica, Sistema Central, Sistema Ibérico, Sierra Morena, Cordilleras Béticas, etc.) y cumbres principales con sus altitudes (Teide, Mulhacén, Aneto, Veleta, Torre Cerredo, Almanzor...).
- **Ríos y Cuencas Hidrográficas**: Los 8 grandes ríos españoles (Miño, Duero, Tajo, Guadiana, Guadalquivir, Ebro, Júcar, Segura) con trazado vectorial sutil de 1px discontinuo que no interfiere con el relieve y **cuencas iluminables** que facilitan el clic y el aprendizaje de la vertiente correspondiente (Atlántica o Mediterránea).
- **Costas y Accidentes Litorales**: Cabos (Finisterre, Ortegal, Creus, de la Nao, de Palos, de Gata), golfos (Vizcaya, Valencia, Cádiz), el Delta del Ebro, el Estrecho de Gibraltar y las aguas marítimas (Océano Atlántico, Mar Cantábrico y Mar Mediterráneo).
- **Superposición vectorial de límites políticos en el mapa físico**: Selector exclusivo que permite superponer sobre el relieve:
  - 🏛️ **Límites de Comunidades Autónomas** en línea continua blanca (`2.2px`).
  - 📍 **Límites Provinciales** en línea discontinua blanca (`1.2px`).
  - Sin etiquetas de texto para mantener la pureza visual y el rigor topográfico.

### 🎮 3. Modos Pedagógicos de Aprendizaje
| Modo | Descripción |
| :--- | :--- |
| 📖 **Estudio** | Muestra los nombres, capitales y etiquetas. Ideal para una primera toma de contacto guiada o explicaciones docentes en clase. |
| 🔍 **Repaso** | Mapa "mudo" sin textos. El alumno explora libremente y, al pulsar sobre cualquier territorio o accidente, se desvela su ficha educativa. |
| 🎯 **Examen** | Juego interactivo de preguntas aleatorias. Cuenta con contador de aciertos, fallos, racha de respuestas correctas (🔥) y barra de progreso. Permite **2 intentos por pregunta**; al segundo fallo, una pista luminosa parpadeante señala el objetivo para consolidar el aprendizaje. |

### 💡 4. Fichas Didácticas con Datos Curiosos y Gastronómicos
- Cada una de las **52 provincias** y las **19 comunidades/ciudades autónomas** cuenta con una píldora educativa que relaciona el territorio con su historia, monumentos emblemáticos, tradiciones o gastronomía típica (las murallas y yemas de Ávila, Atapuerca y la morcilla de Burgos, el turrón en Alicante, la cuna de la paella en Valencia, el acueducto de Segovia, el queso Idiazábal en Guipúzcoa, etc.).
- En la ficha de cada comunidad autónoma se muestran botones interactivos con todas las provincias que la integran para navegar directamente a ellas.

---

## 🚀 Cómo Empezar

La aplicación está diseñada bajo el principio **Zero-Setup / Single-File App**: no requiere instalación de programas, terminal, servidores locales ni conexión permanente a internet.

1. **Descargar el repositorio** o simplemente el archivo [`index.html`](index.html).
2. **Hacer doble clic** en [`index.html`](index.html) para abrirlo en cualquier navegador web moderno (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari, Opera...).
3. ¡Listo para estudiar y jugar!

---

## 💻 Tecnologías y Arquitectura

- **HTML5 Semántico**: Estructura accesible y navegación limpia.
- **Gráficos Vectoriales SVG**:
  - Proyección cartográfica cónica conforme de Lambert (*Lambert Conformal Conic*) para el mapa político y cálculo geométrico de centroides.
  - Proyección polinómica calibrada para superponer con precisión submétrica los límites políticos sobre el mapa de relieve en plastilina.
- **CSS3 Moderno**: Diseño *Responsive*, variables CSS (*Custom Properties*), efectos de desenfoque (*backdrop-filter*) y animaciones de retroalimentación (*pulse*, *shake*).
- **JavaScript Vanilla (ES6+)**: Lógica reactiva sin dependencias ni *frameworks* pesados (React, Vue, etc.).
- **Web Audio API**: Efectos de sonido sintetizados dinámicamente mediante osciladores nativos del navegador (tonos de acierto, error y fanfarria de victoria), sin necesidad de descargar archivos de audio externos.
- **Base64 Embedding**: Las texturas e imágenes de relieve van incrustadas directamente dentro del código, garantizando la autonomía total del archivo.

---

## 📁 Estructura del Proyecto

```text
Materiales-Repaso-Primaria/
├── index.html                   # Aplicación web completa y autocontenida (archivo principal)
└── README.md                    # Documentación del proyecto
```

---

## 🎯 Contenidos Curriculares Cubiertos

### Mapa Político
- **17 Comunidades Autónomas**: Andalucía, Aragón, Principado de Asturias, Illes Balears, Canarias, Cantabria, Castilla-La Mancha, Castilla y León, Cataluña, Extremadura, Galicia, La Rioja, Comunidad de Madrid, Región de Murcia, Comunidad Foral de Navarra, País Vasco, Comunidad Valenciana.
- **2 Ciudades Autónomas**: Ceuta y Melilla.
- **52 Provincias**: Con sus nombres y capitales de provincia correspondientes.

### Mapa Físico
- **Sistemas Montañosos**: Pirineos, Cordillera Cantábrica, Sistema Central, Sistema Ibérico, Sierra Morena, Cordillera Subbética, Cordillera Penibética, Macizo Galaico, Montes de Toledo, Sierra de Guadarrama.
- **Picos y Cumbres**: Teide (3.718 m), Mulhacén (3.479 m), Pico Aneto (3.404 m), Pico Veleta (3.396 m), Picos de Europa / Torre Cerredo (2.650 m), Pico Almanzor (2.591 m).
- **Ríos y Cuencas**: Río Miño, Río Duero, Río Tajo, Río Guadiana, Río Guadalquivir, Río Ebro, Río Júcar, Río Segura.
- **Costas y Accidentes Marítimos**: Cabo de Finisterre, Cabo Ortegal, Cabo de Creus, Cabo de la Nao, Cabo de Palos, Cabo de Gata, Golfo de Vizcaya, Golfo de Valencia, Golfo de Cádiz, Delta del Ebro, Estrecho de Gibraltar, Mar Cantábrico, Océano Atlántico y Mar Mediterráneo.

---

## 📄 Licencia

Proyecto de libre uso educativo y pedagógico. Desarrollado con fines de apoyo escolar y refuerzo en el aula y en casa.
