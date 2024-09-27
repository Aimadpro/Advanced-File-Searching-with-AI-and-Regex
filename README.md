📄 Descripción del Proyecto
SmartSearch es una herramienta basada en Python diseñada para buscar y analizar archivos de texto utilizando expresiones regulares o modelos de inteligencia artificial como OpenAI GPT. Esta herramienta es ideal para trabajar con grandes volúmenes de datos o documentos, permitiendo analizar y extraer información relevante de manera eficiente. SmartSearch puede ejecutar búsquedas con patrones simples o aprovechar la potencia de los modelos de IA para proporcionar resultados contextuales y detallados a partir de segmentos de texto.

✨ Características Clave
Búsqueda con Expresiones Regulares: Realiza búsquedas tradicionales de patrones utilizando expresiones regulares en múltiples archivos.
Búsqueda Basada en IA: Utiliza modelos avanzados como GPT-3 o GPT-4 para procesar, analizar y extraer información contextual de archivos grandes.
Estimación de Coste y Tokens: Proporciona una estimación detallada del coste y la cantidad de tokens necesarios antes de ejecutar una búsqueda basada en IA.
Procesamiento Segmentado de Archivos: Divide automáticamente los archivos grandes en segmentos para ajustarse a los límites de tokens de los modelos de IA.
Confirmación Interactiva: Antes de proceder, el programa muestra el tamaño del archivo y el coste estimado, permitiendo un control total por parte del usuario.

📦 Requisitos
Asegúrate de tener las siguientes dependencias instaladas:
- python-dotenv
- openai
- transformers
- requests
- rich
- gpt4all
- 
⚙️ Uso
El script se puede ejecutar desde la línea de comandos utilizando los siguientes argumentos:
Argumentos Básicos:
file: Ruta del archivo o directorio donde se encuentran los archivos.
-r, --regex: Expresión regular para buscar patrones en los archivos.
-p, --prompt: Prompt utilizado para la búsqueda contextual con IA.
-m, --model: Nombre del modelo de IA a utilizar. Por defecto: "gpt-3.5-turbo-0125".
--max-tokens: Número máximo de tokens que el modelo puede generar.

💡 Mejoras Futuras
Soporte para otros modelos de IA (por ejemplo, GPT-J, LLaMA, etc.)
Implementar procesamiento paralelo para grandes conjuntos de archivos.
Ampliar la herramienta para soportar otros tipos de archivos (PDF, documentos de Word, etc.).
🛠️ Contribuciones
Si deseas contribuir a este proyecto, no dudes en enviar sugerencias, problemas o pull requests. Asegúrate de seguir las pautas de contribución.

📜 Licencia
Este proyecto está licenciado bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

✉️ Contacto
Para cualquier consulta o sugerencia, no dudes en ponerte en contacto:

Nombre: Aimad Aisa Driouchi
Correo: aaisad2324@politecnics.barcelona
[Mi Perfil de LinkedIn](https://www.linkedin.com/in/aimad-aisa-driouchi-09ab6a2b4/)
