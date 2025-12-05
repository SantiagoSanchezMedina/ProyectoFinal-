README

------------------------------------------------------------
INSTALACIÓN Y USO DEL SOFTWARE – PROYECTO UNITY
------------------------------------------------------------

1. DESCRIPCIÓN GENERAL
------------------------------------------------------------
Este software corresponde al proyecto final de Computación Gráfica,
implementado en el motor Unity. Muestra una escena 3D interactiva
con temática prehispánica, modelada en Blender e integrada en Unity.

El usuario NO necesita tener Unity instalado para ejecutar el programa;
solo requiere el ejecutable (.exe) generado a partir del proyecto.

------------------------------------------------------------
2. REQUISITOS DEL SISTEMA
------------------------------------------------------------
- Sistema operativo: Windows 10 o superior (64 bits)
- Procesador: Intel o AMD de 64 bits
- Memoria RAM: mínimo 4 GB (recomendado 8 GB)
- Tarjeta gráfica con soporte DirectX 11 o superior
- Espacio en disco: suficiente para el instalador y la carpeta del juego
- Resolución de pantalla recomendada: 1280 x 720 o superior

------------------------------------------------------------
3. TECNOLOGÍAS Y PAQUETERÍAS UTILIZADAS (YA INCLUIDAS)
------------------------------------------------------------
El proyecto fue desarrollado con:

- Unity (motor gráfico en tiempo real)
- Lenguaje C# para los scripts
- Sistema de escenas, prefabs y componentes de Unity
- Sistema de materiales, iluminación y animaciones de Unity

Todas estas dependencias vienen empacadas dentro de la build.
El usuario final NO necesita instalar Unity ni paquetes adicionales.

------------------------------------------------------------
4. CONTENIDO DE LA CARPETA DEL PROGRAMA
------------------------------------------------------------
Después de instalar o descomprimir el software, debe existir
una carpeta similar a la siguiente:

- EscenaPrehispanica.exe           → Ejecutable principal
- EscenaPrehispanica_Data/         → Carpeta de datos del juego
- UnityPlayer.dll                   → Librería del motor
- UnityCrashHandler64.exe           → Manejador de errores (opcional)
- Otros archivos generados por Unity

IMPORTANTE:
No borre ni mueva archivos individuales. El .exe siempre debe estar
junto a la carpeta *_Data*.

------------------------------------------------------------
5. INSTALACIÓN DEL SOFTWARE
------------------------------------------------------------

A) Si se entrega como instalador (.exe creado con InstallForge):

1. Ejecutar el instalador.
2. Seguir las instrucciones del asistente:
   - Aceptar términos (si aplica).
   - Elegir la ruta de instalación.
   - Esperar a que finalice la copia de archivos.
3. Al terminar, se creará una carpeta con el programa instalado.
4. Verificar que en esa carpeta estén:
   - El archivo .exe del proyecto.
   - La carpeta *_Data* generada por Unity.

B) Si se entrega como carpeta comprimida (.zip):

1. Descomprimir el archivo .zip en una carpeta de su preferencia.
2. No cambiar la estructura de los archivos.
3. Asegurarse de que:
   - El .exe y la carpeta *_Data* estén juntos en la misma ruta.

------------------------------------------------------------
6. EJECUCIÓN DEL PROGRAMA
------------------------------------------------------------
1. Abrir la carpeta donde se instaló o descomprimió el software.
2. Hacer doble clic en:
   EscenaPrehispanica.exe
   (o el nombre que tenga el ejecutable del proyecto)
3. Esperar a que Unity cargue la escena.
4. Si aparece una ventana de configuración de resolución:
   - Elegir la resolución adecuada para su pantalla.
   - Elegir calidad gráfica "Medium" o "High" según el rendimiento
     de su equipo.
5. Presionar "Play" o "Iniciar" si la ventana de configuración lo solicita.

------------------------------------------------------------
7. CONTROLES BÁSICOS (EJEMPLO GENERAL)
------------------------------------------------------------

Teclado:
  W / A / S / D  → Movimiento del personaje o cámara
  Shift (izquierdo) → Correr / movimiento rápido (si está habilitado)
  Espacio        → Saltar / acción (si aplica)
  Esc            → Pausar o salir del programa

Mouse:
  Movimiento     → Rotar la cámara / cambiar dirección de vista
  Clic izquierdo → Interacción / acción principal (si aplica)
  Clic derecho   → Acción secundaria (si aplica)

Los controles exactos pueden variar según la configuración final
del proyecto, pero en general se sigue este esquema estándar de Unity.

------------------------------------------------------------
8. PROBLEMAS COMUNES Y SOLUCIONES
------------------------------------------------------------

El programa no abre:
- Verificar que el sistema sea de 64 bits.
- Intentar ejecutar como administrador.
- Revisar que el antivirus no haya bloqueado archivos.
- Si se descargó en .zip, volver a descomprimir en una carpeta nueva.

La ventana se ve en negro o se cierra al iniciar:
- Actualizar los drivers de la tarjeta gráfica.
- Probar con una calidad gráfica más baja.
- Cerrar otros programas pesados antes de ejecutar.

Errores de resolución o la ventana se sale de la pantalla:
- Cambiar la resolución desde la ventana de inicio de Unity,
  si aparece.
- Si el proyecto incluye menú de opciones, ajustar la resolución
  desde ahí.

------------------------------------------------------------
9. INFORMACIÓN FINAL
------------------------------------------------------------
Este software forma parte del proyecto final de la materia
de Computación Gráfica. La escena fue modelada principalmente
en Blender e integrada en Unity para su visualización en tiempo real.

El usuario solo necesita instalar o descomprimir el programa
y ejecutar el archivo .exe correspondiente.
