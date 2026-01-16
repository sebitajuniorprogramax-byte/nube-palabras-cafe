# nube-palabras-cafe

Analizador de Preferencias (Nube de Palabras)
Este proyecto automatiza la creación de una nube de palabras a partir de las respuestas de un Google Form. Está diseñado para identificar rápidamente las tendencias y gustos de los usuarios (en este ejemplo, sobre el consumo de café) mediante el procesamiento de lenguaje natural (NLP).

Funcionalidades
-Conexión Automática: Se vincula directamente con Google Sheets para obtener datos en tiempo real.
-Limpieza de Datos: Filtra automáticamente palabras comunes y conectores (stop words) para resaltar solo los conceptos clave.
-Visualización Personalizada: Genera una imagen estética usando una paleta de colores temática.

Cómo replicar este proyecto
Si deseas usar este código con tus propios datos, sigue estos pasos:
-Haz clic en el botón "Open in Colab" arriba.
-Crea una copia en tu propio Drive (Archivo > Guardar una copia en Drive).
-Cambia la variable nombre_archivo por el nombre exacto de tu hoja de cálculo en Google Drive.
-Si quieres cambiar el diseño, ajusta los parámetros en la sección de Generación de la Nube:
colormap: Cambia los colores (ej. 'viridis', 'plasma', 'cool').
background_color: Cambia el fondo de la imagen.
max_words: Define cuántas palabras quieres mostrar.

Resultado Esperado
El script genera una imagen llamada resultado_cafeteria.png con los términos más frecuentes, permitiendo un análisis visual inmediato de las preferencias de los clientes.

<img width="1175" height="838" alt="descarga" src="https://github.com/user-attachments/assets/d309504a-e124-4225-89d6-d1f310001799" />

