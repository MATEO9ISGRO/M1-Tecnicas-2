# 📚 Clase 8: Análisis Geográfico y Capas Vectoriales en QGIS

> **Procesamiento ráster GeoTIFF, delimitación de áreas nivales y digitalización vectorial**

Repositorio correspondiente al **Módulo 8**, enfocado en el uso de **QGIS** para el análisis de imágenes satelitales multiespectrales y la creación de capas vectoriales georreferenciadas. Como caso de estudio, se realizó la medición comparativa de la cobertura nival en el **Glaciar de las Lágrimas** (Malargüe, Mendoza), sitio histórico del accidente aéreo de 1972.

---

## 🛰️ Tratamiento de Imágenes Satelitales y GeoTIFF

* **Entorno SIG:** Configuración e integración de herramientas de código abierto en QGIS.
* **Estándar GeoTIFF (`.tif` / `.tiff`):** Análisis de capas ráster con metadatos de georreferenciación integrados en cabecera.
* **Captura de Datos (Copernicus / Sentinel-2):** Descarga de bandas multiespectrales de alta resolución espacial desde *Copernicus Browser*, aplicando un filtro de nubosidad menor al 10%.

---

## 📐 Vectorización, Proyección y Cálculo de Áreas

Para garantizar precisión métrica en el cálculo de superficies ($m^2$), el proyecto se estructuró bajo el siguiente Sistema de Referencia de Coordenadas:

* **SRC Proyectado:** `UTM Zona 19S / WGS 84` (**EPSG:32719**).
* **Digitalización Vectorial:** Creación de capas de polígonos y puntos de interés mediante delimitación manual vértice por vértice en formato **GeoPackage**.

---

## 🗂️ Recursos y Archivos de la Clase

| Recurso / Contenido | Formato | Descripción |
| :--- | :---: | :--- |
| **Informe Técnico y Análisis SIG** | [Ver PDF](#) | Documento descriptivo con la metodología, procesamiento de imágenes y resultados del análisis nival. |
| **Proyecto QGIS y Capas** | [Descargar ZIP](#) | Archivo comprimido con el proyecto completo, capas vectoriales (GeoPackage) y configuraciones de estilo. |
| **Medición de Cobertura Nival** | [Descargar RAR](#) | Set de datos ráster y polígonos delimitados para la evaluación comparativa de la superficie cubierta de nieve. |

---

## 🛠️ Tecnologías Utilizadas

| Herramienta | Función en el Módulo |
| :--- | :--- |
| **
