# Project: ocr-license-cl

# Chores and Development

## Definición y Validación del Producto

- Finalizar el conjunto de características principales para el MVP.
- Definir métricas de éxito para la demo funcional (por ejemplo, precisión del OCR, tiempo de respuesta).

## Base Técnica

- Seleccionar la pila tecnológica para el backend, frontend y base de datos.
- Investigar proveedores de hosting y servicios de GPU (por ejemplo, AWS, Azure, Google Cloud).

## Desarrollo del MVP

- **Backend**: Implementar el servicio en FastAPI para el procesamiento OCR y la comunicación con la base de datos.
- **Frontend**: Desarrollar una interfaz de usuario simple para consultar el backend y mostrar resultados.
- **Modelo OCR**: Entrenar y probar el modelo OCR de lectura de placas usando PyTorch (o alternativa si se encuentra algo mejor).
- **Integración**: Integrar el modelo OCR con el servicio backend.

## Pruebas e Iteración

- Probar el MVP para la funcionalidad principal (por ejemplo, lectura precisa de placas, tiempos de respuesta rápidos).
- Recopilar retroalimentación de una audiencia de prueba pequeña (administradores de edificios, empresas de seguridad).

## Configuración de Infraestructura

- Configurar contenedores Docker para despliegue.
- Configurar el hosting para backend, modelo y base de datos (comenzar con opciones de bajo costo como el nivel gratuito de AWS, si es posible).

## Demo y Retroalimentación

- Preparar una demo funcional para posibles clientes.
- Incorporar retroalimentación en la siguiente iteración.

## Planificación de Funcionalidades Futuras

- Explorar el procesamiento de video en tiempo real.
- Mejorar la interfaz de usuario para una adopción más amplia.

## Cronograma e Hitos

| Hito                         | Plazo          | Entregables Clave                                     |
|------------------------------|----------------|-----------------------------------------------------|
| Finalizar Pila Tecnológica   | Semana 1       | Decisiones confirmadas sobre tecnología y hosting.  |
| Configuración del Modelo OCR | Semana 2-3     | Modelo OCR básico entrenado y probado localmente.   |
| Esqueleto del API Backend    | Semana 4       | Esqueleto de FastAPI con endpoints para OCR e integración de base de datos. |
| Prototipo del Frontend       | Semana 5       | Prototipo básico de interfaz integrado con el backend para pruebas manuales. |
| Integración y Pruebas del MVP| Semana 6-7     | MVP completamente integrado con backend, frontend y modelo OCR. |
| Despliegue de Infraestructura| Semana 8       | MVP desplegado en un entorno en la nube (por ejemplo, AWS). |
| Presentación de la Demo      | Semana 9       | Demo funcional lista para posibles clientes.        |
| Retroalimentación e Iteración| Semana 10-11   | Recopilar retroalimentación y planificar características secundarias (por ejemplo, video en tiempo real). |

| **Hito**                    | **Tarea**|
|------------------------------|------------------------------------------------------------------|
| Finalizar Pila Tecnológica   | - Evaluar pros y contras entre SQL y MongoDB para la base de datos.|
|                              | - Revisar opciones para hosting y GPUs (AWS, Azure, GCP).|
|                              | - Tomar decisiones finales sobre herramientas para frontend y backend.|
| Configuración del Modelo OCR | - Recolectar un dataset inicial para entrenamiento (placas).|
|                              | - Preprocesar datos y etiquetarlos adecuadamente.|
|                              | - Entrenar un modelo OCR base en PyTorch con resultados iniciales.|
|                              | - Evaluar precisión inicial del modelo y ajustar hiperparámetros básicos.|
| Esqueleto del API Backend    | - Crear estructura inicial de FastAPI con endpoints básicos.|
|                              | - Integrar FastAPI con una base de datos dummy (mock).|
|                              | - Crear un endpoint para enviar imágenes y recibir texto como respuesta.|
| Prototipo del Frontend       | - Crear un mockup básico de la interfaz de usuario.|
|                              | - Configurar un entorno básico de React Native o alternativa.|
|                              | - Implementar un formulario para subir imágenes y mostrar resultados.|
| Integración y Pruebas del MVP| - Conectar el backend con el frontend (pruebas manuales).|
|                              | - Probar integración con el modelo OCR (peticiones REST).|
|                              | - Realizar pruebas de rendimiento iniciales para tiempos de respuesta.|
|                              | - Identificar y corregir errores básicos del MVP.|
| Despliegue de Infraestructura| - Configurar Docker para backend y modelo.|
|                              | - Configurar entorno en la nube para hospedar el MVP (AWS u otra).|
|                              | - Realizar pruebas del MVP en el entorno en la nube.|
| Presentación de la Demo      | - Preparar casos de uso para la demo (escenarios prácticos).|
|                              | - Crear una presentación simple para mostrar resultados y características.|
|                              | - Realizar pruebas previas de la demo con colegas o conocidos.|
| Retroalimentación e Iteración| - Recolectar y analizar retroalimentación de clientes potenciales.|
|                              | - Priorizar tareas para la siguiente iteración (video en tiempo real, etc.).|


