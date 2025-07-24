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
ProyFinal_SyS_2025/
├── README.md # Este archivo
├── resumen_conceptos_clave/ # Cuaderno Colab con resumen teórico y simulaciones
│ └── Resumen_Conceptos.ipynb
├── codigo_fuente/ # Código Python del proyecto
│ ├── dominio_frecuencia.py # Simulación básica (FFT, filtros)
│ ├── señales_iq.py # Transformada de Hilbert y señales I/Q
│ ├── modulacion_qam.py # Implementación de QAM
│ └── dashboard/ # Código del dashboard en Streamlit
│ └── app.py
├── entregables/ # Archivos finales
│ ├── video_explicativo/ # Enlace al video (YouTube)
│ └── dashboard_streamlit/ # Cuaderno Colab para ejecutar el dashboard
└── referencias/ # Artículos, libros y recursos utilizados



 **Explorar Simulaciones:**  
   - Abrir los cuadernos de Jupyter/Colab en `([https://github.com/descruceria777/Se-alesySistemas/blob/main/proyectofinal-SYS/PROYECTO_.ipynb]) para ver ejemplos de FFT, filtros, QAM, etc.

## Entregables
- **Resumen Teórico:** Cuaderno Colab con conceptos clave y simulaciones.  
- **Dashboard Interactivo:** Aplicación Streamlit para experimentar con parámetros del sistema.  
- **Video Explicativo:** Disponible en YouTube (enlace en la carpeta `entregables/`).  

## Fecha de Entrega
**24 de julio de 2025**

## Autores
- [Daniel Santiago Escruceria Resero]([https://github.com/amalvarezme/SenalesSistemas/tree/master/1_IntroduccionSyS])  
- [Nombre del Estudiante 2](enlace a GitHub)  
- [Nombre del Estudiante 3](enlace a GitHub)  

## Licencia
Este proyecto está bajo la licencia [MIT](LICENSE).  

---

### Notas Adicionales
- Para contribuciones o reporte de errores, abrir un *issue* en el repositorio.  
- El video debe explicar claramente la relación entre QAM, WiFi y 5G usando diagramas o animaciones.  
