# 🏛️ Proyecto Final Computación Gráfica: Escena Prehispánica

![Unity](https://img.shields.io/badge/Engine-Unity_2022.3+-black?logo=unity)
![Blender](https://img.shields.io/badge/Modeling-Blender_4.0-orange?logo=blender)
![Language](https://img.shields.io/badge/Code-C%23-blue?logo=csharp)

## 📋 Información del Proyecto
Este repositorio aloja el proyecto final para la asignatura de **Computación Gráfica** de la carrera de **Ingeniería en Computación**.

El proyecto consiste en la implementación técnica y visual de una escena 3D con temática prehispánica. El objetivo principal es demostrar la integración de assets creados desde cero en un motor gráfico en tiempo real, aplicando los fundamentos teóricos de la graficación por computadora.

## ⚙️ Stack Tecnológico
Se utilizaron herramientas estándar de la industria bajo un flujo de trabajo optimizado:

| Componente | Herramienta | Descripción |
| :--- | :--- | :--- |
| **Motor Gráfico** | Unity | Gestión de escena, iluminación y renderizado en tiempo real. |
| **Modelado 3D** | Blender | Creación de geometría, UV mapping y exportación (FBX). |
| **Scripting** | C# | Lógica de movimiento de cámara e interacción básica. |
| **Control de Versiones** | Git | Gestión del código fuente y assets. |

## 📸 Capturas de la Escena

> *Nota: Inserta aquí las capturas de tu escena en Unity.*

![Vista Principal](link-a-tu-imagen-principal.png)
*Vista general de la estructura principal renderizada en Unity.*

![Wireframe vs Render](link-a-tu-imagen-comparativa.png)
*Comparativa: Modelo en Blender (Wireframe) vs. Integración final en Unity.*

## 🔧 Detalles de Implementación
El desarrollo se centró en los requisitos fundamentales de la computación gráfica sin sobrecarga de procesamiento:

* **Pipeline de Importación:** Los modelos fueron creados en Blender asegurando una topología limpia y exportados a Unity manteniendo las coordenadas de texturizado (UVs) correctas.
* **Iluminación:** Se implementó un esquema de iluminación [Ej: Mixta / Baked / Realtime] para resaltar la geometría sin comprometer el rendimiento.
* **Cámara:** Script en C# para el recorrido de la escena (First Person Controller / Cámara Orbital).
* **Materiales:** Configuración de materiales estándar en Unity aplicando texturas difusas y normales.

## 🚀 Instrucciones de Ejecución

Para clonar y ejecutar este proyecto se requiere **Unity Hub** y una versión compatible de Unity (recomendado 2022.3 LTS o superior).

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
    ```
2.  **Abrir en Unity Hub:**
    * Abre Unity Hub.
    * Da clic en `Add` -> `Add project from disk`.
    * Selecciona la carpeta raíz del repositorio clonado.
3.  **Cargar la Escena:**
    * Navega a la carpeta `Assets/Scenes`.
    * Abre el archivo `MainScene.unity` (o el nombre que tenga tu escena).

## 📂 Estructura del Proyecto
La organización de carpetas sigue el estándar de ingeniería para mantener el orden:

* `Assets/Models`: Archivos .fbx exportados de Blender.
* `Assets/Materials`: Definiciones de materiales y shaders.
* `Assets/Textures`: Mapas de bits (Albedo, Normal Maps).
* `Assets/Scripts`: Código fuente C# para el control de la escena.
* `Assets/Scenes`: Archivos de escena de Unity.

## 👥 Autores - Ingeniería en Computación
* **[Tu Nombre]** - *Modelado e Integración Unity*
* **[Nombre Compañero]** - *Scripting y Texturizado*

---
*Facultad de Ingeniería - [Nombre de tu Universidad]*
