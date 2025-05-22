# computadoresApp

ComputadoresApp: Gestión y Consulta de Productos (Proyecto Universitario)
Este repositorio contiene el proyecto de aplicación móvil ComputadoresApp, desarrollado en Kodular. La aplicación está diseñada para demostrar diversas funcionalidades clave en el desarrollo de aplicaciones móviles, cumpliendo con los requisitos de las entregas de los diferentes cortes del curso.

🚀 Versión 2.0: Integración de API Externa para Consulta de Productos (#Segundo Corte)
Esta es una actualización significativa sobre la versión inicial, enfocada en la integración y consumo de datos de una API externa para la gestión y consulta de un catálogo de productos.

✨ Nuevas Funcionalidades en esta Versión:
Conexión a API Externa: La aplicación ahora se conecta a una API RESTful para obtener dinámicamente un listado de productos (título, precio, imagen, etc.).
Decodificación JSON: Implementación de la lógica para decodificar las respuestas en formato JSON recibidas de la API, transformándolas en estructuras de datos manejables por la aplicación.
Visualización Dinámica de Productos: Los datos de los productos se muestran en la interfaz de usuario (títulos, precios, imágenes) de forma dinámica, reflejando la información obtenida de la API.
Navegación de Productos: Incorporación de botones de "Siguiente" (y opcionalmente "Anterior") para permitir al usuario explorar el catálogo de productos cargados desde la API.
Manejo Robusto de Datos: Se han implementado validaciones para asegurar que la aplicación maneje correctamente los estados de la lista de productos (vacía, fuera de límites) y los errores comunes de conexión a la API.

🛠️ Tecnologías Utilizadas:
Kodular (Basado en App Inventor): Plataforma de desarrollo de aplicaciones móviles sin código.
API RESTful: Para la obtención de datos de productos.
JSON: Formato de intercambio de datos.
TinyDB: Base de datos local para persistencia de datos.
Componentes de Sensores de Kodular: Orientación y Lector de Código de Barras.

📦 Versión 1.0: Gestión Local de Usuarios y Sensores (Primer Corte)
Esta fue la primera versión del proyecto, centrada en la implementación de funcionalidades locales y la integración de sensores.

📝 Funcionalidades Implementadas:
Sistema de Login Local: La aplicación cuenta con un módulo de autenticación de usuarios.
Validación de Credenciales: Verificación de usuarios y contraseñas.
Persistencia de Datos (TinyDB): Las credenciales de los usuarios se almacenan y se recuperan localmente utilizando la base de datos TinyDB de Kodular, lo que permite que los datos persistan incluso después de cerrar la aplicación.
Integración de Sensores: Se han incorporado dos sensores clave:
Sensor de Orientación: Utilizado para [Explicar brevemente el uso, ej: "detectar cambios en la orientación del dispositivo y reaccionar a ellos"].
Sensor de Código de Barras: Permite [Explicar brevemente el uso, ej: "escanear códigos de barras y procesar la información obtenida"].
✅ Requisitos del Primer Corte Cumplidos:
Operaciones Locales: Todas las funcionalidades de gestión de usuarios y sensores se ejecutan de forma local en el dispositivo, sin dependencia de servicios en la nube.
Integración de Sensores: Se han implementado satisfactoriamente los dos sensores requeridos.
Funcionalidad Completa: La aplicación demuestra una gestión básica de datos persistentes y la interacción con hardware del dispositivo a través de los sensores.
