# AngularZeroToHero
Repository for practice and master angular

# Roadmap para Aprender Angular

## Módulo 1: Fundamentos de Angular

**Temas a Aprender:**
- Introducción a Angular y Arquitectura
  - ¿Qué es Angular?
  - Arquitectura de Componentes
  - CLI de Angular
- TypeScript
  - Sintaxis básica
  - Clases, Interfaces y Tipos
- Componentes
  - Creación de componentes
  - Directivas estructurales (`*ngIf`, `*ngFor`)
  - Interpolación y enlaces de datos
- Módulos y Rutas
  - Creación de Módulos
  - Configuración de rutas básicas

**Proyecto Práctico:**  
Crear una aplicación simple de lista de tareas, donde se puedan agregar, editar y eliminar tareas. Cada tarea puede tener un estado de completada o no.

---

## Módulo 2: Manejo de Formularios y Validaciones

**Temas a Aprender:**
- Formularios en Angular
  - Formularios Reactivos vs. Formularios Basados en Plantillas
  - Enlace de Datos en Formularios
- Validaciones
  - Validaciones básicas y personalizadas
  - Manejo de errores en formularios

**Proyecto Práctico:**  
Construir un formulario de registro de usuarios con validación (nombre, email, contraseña, etc.), mostrando mensajes de error si hay validaciones no cumplidas.

---

## Módulo 3: Servicios y Dependencias

**Temas a Aprender:**
- Servicios y Dependencias
  - Inyección de dependencias
  - Ciclo de vida de los servicios
- Comunicaciones HTTP
  - HttpClient para realizar peticiones REST
  - Manejo de errores con HttpInterceptor

**Proyecto Práctico:**  
Desarrollar una aplicación de gestión de productos que consuma una API REST externa. Debe permitir listar, agregar, actualizar y eliminar productos.

---

## Módulo 4: Gestión de Estados y Comunicación entre Componentes

**Temas a Aprender:**
- Comunicación entre Componentes
  - @Input y @Output
  - EventEmitter
- Gestión de Estados
  - Angular Services para gestionar el estado compartido
  - Uso básico de NgRx (Redux para Angular)

**Proyecto Práctico:**  
Crear una aplicación de carrito de compras donde los productos seleccionados se agreguen a un carrito común gestionado en un servicio compartido. Implementar la capacidad de agregar, quitar y modificar la cantidad de productos en el carrito.

---

## Módulo 5: Directivas y Pipes Personalizados

**Temas a Aprender:**
- Directivas
  - Directivas personalizadas estructurales y de atributos
- Pipes
  - Uso de pipes existentes
  - Creación de pipes personalizados

**Proyecto Práctico:**  
Crear una aplicación de galería de imágenes con filtros personalizados usando pipes para ordenar y buscar imágenes según ciertos criterios. Implementar directivas que modifiquen el comportamiento de las imágenes, como por ejemplo, cambiar el tamaño al hacer clic.

---

## Módulo 6: Optimización y Pruebas

**Temas a Aprender:**
- Lazy Loading
  - Carga diferida de módulos
- Mejores prácticas de rendimiento
  - Change Detection Strategy
  - Optimización de bucles y eventos
- Testing en Angular
  - Pruebas unitarias con Jasmine y Karma
  - Pruebas de integración y componentes

**Proyecto Práctico:**  
Optimizar la aplicación de carrito de compras utilizando lazy loading para diferentes secciones y escribir pruebas unitarias para los componentes principales de la aplicación.

---

## Módulo 7: Despliegue y Seguridad

**Temas a Aprender:**
- Preparar una aplicación para producción
  - Construcción y optimización de la aplicación para despliegue
- Seguridad en Angular
  - Autenticación y Autorización (JWT, OAuth)
  - Protecciones contra XSS, CSRF
- Despliegue en la nube
  - Implementación en plataformas como Firebase, AWS o Heroku

**Proyecto Práctico:**  
Configurar un sistema de autenticación en una aplicación de gestión de usuarios y desplegarla en un entorno de producción, como Firebase o Heroku.

---

## Módulo 8: Arquitecturas Avanzadas

**Temas a Aprender:**
- Micro Frontends
- Mono repos con Nx
- Implementación de patrones avanzados de diseño

**Proyecto Práctico:**  
Dividir una aplicación monolítica en micro frontends y gestionar su integración utilizando técnicas de Nx para mantener un monorepo y optimizar el ciclo de desarrollo.

---

