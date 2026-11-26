# Titulo: Análisis dentro del sector de movilidad urbana, como se utiliza y se desperdicia el tiempo en cada trayecto.  

**Curso:** Samsung Innovation Campus – Módulo de Python (Ecuador 2026)  
**Sección:** EC-A


---

## 👥 Integrantes del Grupo
- Galileo Donoso
- Carlos Manotoa
- Bryan Guerra
- Gabriela Galarza
- Mateo Cevallos

---

## 📝 Descripción del Proyecto
Es un proyecto de ciencia de datos enfocado en analizar el impacto de la movilidad urbana en el tiempo cotidiano de los habitantes de Nueva York, tomando como punto de partida el funcionamiento de su sistema de transporte público y particular. La iniciativa surge de una problemática presente en las grandes ciudades: el tiempo que las personas destinan a sus desplazamientos y cómo los retrasos, las variaciones en los tiempos de recorrido y la imprevisibilidad del transporte pueden afectar sus actividades diarias.

Mediante el uso de Python y técnicas de análisis de datos, se recopilará, procesará y estudiará información proveniente de fuentes públicas relacionadas con la movilidad de Nueva York. Se aplicarán procedimientos de limpieza y transformación de datos, análisis exploratorio (EDA), estadística descriptiva y visualización, con el propósito de identificar patrones de comportamiento, tendencias temporales y diferencias en la eficiencia de los desplazamientos según el tipo de transporte y horarios.

Uno de los elementos centrales del proyecto será el desarrollo de un indicador propio denominado Índice de Tiempo Perdido, orientado a cuantificar las diferencias entre los tiempos de desplazamiento esperados y los observados. Este indicador permitirá estudiar no solamente la duración de los recorridos, sino también la variabilidad e imprevisibilidad que experimentan los habitantes.

Como resultado, se busca desarrollar un dashboard interactivo que permita explorar los hallazgos mediante gráficos, comparaciones e indicadores estadísticos. De esta manera, la información obtenida podrá convertirse en conocimiento útil para comprender las dinámicas de movilidad urbana e identificar oportunidades de mejora en la planificación y gestión del transporte.

El propósito principal es demostrar cómo la ciencia de datos puede transformar registros cotidianos en información significativa para la toma de decisiones. Más allá de medir cuánto tarda una persona en llegar a su destino, el proyecto busca responder una pregunta fundamental: ¿cuánto tiempo de nuestras vidas estamos perdiendo debido a la forma en que nos movilizamos por la ciudad

---

## ⚙️ Instrucciones de Instalación y Ejecución

### Requisitos
- **Python 3.13+**
- **Librerías:** incluidas en `requirements.txt`
- **Jupyter Notebook** o **VS Code** con la extensión de Jupyter

---

### 🪜 Pasos de Ejecución

1. **Clonar el repositorio o ubicarte en la carpeta del proyecto:**
   ```bash
   git clone 
   ```

2. **Instalar dependencias:**
   ```bash
   pip install -r requirements.txt
      ```

3. **Abrir el notebook principal:**
   ```bash
   jupyter notebook main.ipynb
      ```
   o directamente desde VS Code con la extensión de Jupyter.

---

## 📂 Estructura del Código (sugerida)
```
ANÁLISIS Y VISUALIZACIÓN DE LA CALIDAD DEL AIRE/
│
├── data/                       # Archivos de datos
│   └── raw/
|       └── .csv 
│   └── processed/
|       └── .csv
├── graphs/                     # Gráficos generados automáticamente
│   ├── .png
│
├── src/                        # Código fuente de los módulos
│   ├── .py
│
├── main.ipynb                  # Notebook principal del proyecto
├── requirements.txt            # Dependencias del entorno
├── .gitignore
└── README.md

```

---

## ✅ Herramientas Implementadas
- **Lenguaje:** Python 3.13+
- **Librerías principales:** `pandas, numpy, matplotlib, seaborn`
- **Otras herramientas:** `Jupyter Notebook / VS Code, Git + GitHub`

---

## 🌱 Impacto del Proyecto
El proyecto busca generar un impacto social e informativo al visibilizar la perdida temporal que representa la movilidad urbana en la vida cotidiana de los habitantes de Nueva York. Sus resultados permitirán comprender mejor las dificultades asociadas a los desplazamientos y reconocer cómo estas pueden influir en el aprovechamiento del tiempo personal, académico y laboral.

Asimismo, pretende aportar una perspectiva diferente sobre la planificación urbana, ofreciendo información que pueda servir de referencia para usuarios, investigadores y entidades relacionadas con el transporte. De esta manera, el proyecto busca promover una mayor conciencia sobre el valor del tiempo y la importancia de construir ciudades con sistemas de movilidad más eficientes y predecibles.
