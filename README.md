# 💻 ComputadoresApp
Aplicación Móvil para Gestión y Consulta de Productos

# 📚 Descripción General
ComputadoresApp es una aplicación móvil desarrollada como parte de un proyecto académico, enfocada en la gestión de usuarios y la consulta dinámica de productos. Está construida utilizando Kodular, una plataforma de desarrollo visual basada en App Inventor, y ha sido diseñada para cumplir con los requisitos de evaluación de diferentes cortes del curso.


# 🚀 Versión 2.0 — Integración de API Externa (Segundo Corte)
Actualización significativa con enfoque en la integración de una API RESTful para mostrar productos electrónicos en tiempo real.

✨ Funcionalidades Nuevas
Conexión a API Externa:
Consumo de una API pública para mostrar productos con título, precio e imagen.

Decodificación JSON:
Interpretación de respuestas en formato JSON y conversión a estructuras de datos utilizables por la app.

Visualización Dinámica de Productos:
Renderizado en la interfaz con datos obtenidos en tiempo real (título, imagen y precio).

Navegación entre Productos:
Botón de "Siguiente" (y opcionalmente "Anterior") para navegar entre elementos del catálogo.

Manejo Robusto de Datos:
Validación de listas vacías, control de errores de conexión y manejo de índices fuera de rango.


# 🛠️ Tecnologías Utilizadas
Kodular (basado en App Inventor)

API RESTful para el consumo de datos

Formato JSON para intercambio de información

TinyDB para almacenamiento local persistente

Sensores de Kodular: Sensor de orientación y lector de código de barras

# 📦 Versión 1.0 — Gestión Local y Sensores (Primer Corte)
Versión inicial enfocada en funcionalidades locales de autenticación y hardware del dispositivo.

# 📝 Funcionalidades Implementadas
Sistema de Login Local:
Módulo de autenticación con verificación de credenciales.

Persistencia con TinyDB:
Almacenamiento y recuperación de datos de usuario localmente, incluso tras cerrar la app.

Integración de Sensores:

Sensor de Orientación: Detecta la posición del dispositivo para ajustar el comportamiento de la app.

Lector de Código de Barras: Escanea códigos para obtener información del producto.

# ✅ Requisitos del Primer Corte Cumplidos
Operaciones Locales: Todas las funcionalidades se ejecutan en el dispositivo sin conexión a la nube.

Gestión de Usuarios y Sensores: Implementación completa de funcionalidades requeridas.
