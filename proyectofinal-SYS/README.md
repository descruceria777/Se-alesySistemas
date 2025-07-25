 # Proyecto Final: De Fourier al WiFi/5G - Anatomía de una Señal Inalámbrica

## Descripción del Proyecto
Este proyecto tiene como objetivo analizar, sintetizar y exponer los principios fundamentales del procesamiento de señales en el contexto de las comunicaciones inalámbricas modernas (Wi-Fi/5G). A través de simulaciones y visualizaciones, se exploran conceptos clave como la Transformada de Fourier, filtrado digital, señales analíticas, modulación QAM y su aplicación en tecnologías como WiFi y 5G. El resultado final incluye un dashboard interactivo en Streamlit y un video explicativo.

## Objetivos
- **Objetivo General:**  
  Analizar y sintetizar los principios del procesamiento de señales en comunicaciones inalámbricas utilizando herramientas de simulación y visualización.

- **Objetivos Específicos:**  
  - Aplicar la Transformada Discreta de Fourier (DFT/FFT) para analizar señales.  
  - Diseñar e implementar filtros digitales (Paso-Bajo, Paso-Banda).  
  - Generar señales analíticas con la Transformada de Hilbert.  
  - Simular modulación y demodulación QAM, incluyendo diagramas de constelación.  
  - Desarrollar un dashboard interactivo en Streamlit.  
  - Producir un video explicativo dirigido a una audiencia con conocimientos básicos de ingeniería.  

## Tecnologías Utilizadas
- **Lenguaje de Programación:** Python  
- **Bibliotecas Principales:**  
  - NumPy, SciPy (para procesamiento de señales)  
  - Matplotlib, Plotly (para visualización)  
  - Streamlit (para el dashboard interactivo)  
  - Librosa, PyAudio (opcional, para manejo de señales de audio)
  - 
## Estructura del Repositorio

Proyecto_Final/
├── 📄 README.md                 # Este archivo
├── 📂 codigo/                   # Códigos Python
│   ├── 📜 fft_filtros.py        # Análisis espectral
│   ├── 📜 modulacion_qam.py     # Generación de señales I/Q
│   └── 📜 app_streamlit.py      # Dashboard principal
├── 📂 entregables/              # Resultados finales
│   ├── 📜 video_explicativo.mp4 # Enlace a YouTube
│   └── 📜 presentacion.pdf      # Slides opcionales
└── 📜 requirements.txt          # Dependencias


 ##Explorar Simulaciones:**  
   - Abrir los cuadernos de Jupyter/Colab en `([https://github.com/descruceria777/Se-alesySistemas/blob/main/proyectofinal-SYS/PROYECTO_.ipynb]) para ver ejemplos de FFT, filtros, QAM, etc.

## Entregables
- **Resumen Teórico:** Cuaderno Colab con conceptos clave y simulaciones.  
- **Dashboard Interactivo:** Aplicación Streamlit para experimentar con parámetros del sistema.  
- **Video Explicativo:** Disponible en YouTube (enlace en la carpeta `entregables/`).  

## Autores
- [Daniel Santiago Escruceria Resero CC:1087107563]
- [Darwin Arias CC:1053776364] 
- [Alexis Valencia CC:1088588394]

---

### Notas Adicionales
- Para contribuciones o reporte de errores, abrir un *issue* en el repositorio.  
- El video debe explicar claramente la relación entre QAM, WiFi y 5G usando diagramas o animaciones.


