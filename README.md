# Sistema de Planificación Financiero

## Introducción

El **Sistema de Planificación Financiero** es una solución informática diseñada para ayudar a individuos a gestionar sus finanzas personales de manera eficiente. Aborda la dificultad común de planificar ingresos, gastos e inversiones en contextos económicos variables. El sistema permite registrar ingresos, categorizar gastos, seguir el rendimiento de inversiones y recibir recomendaciones personalizadas para optimizar las finanzas personales.

Este proyecto se desarrollará bajo el Proceso Unificado de Desarrollo (PUD), garantizando calidad, escalabilidad y eficiencia. Se utilizará el lenguaje **Java** para la lógica del sistema y **MySQL** para la persistencia de datos, con un prototipo inicial en consola.

## Justificación

La gestión de finanzas personales es una necesidad crítica, especialmente en economías con inflación, como la de Argentina. Más del 60% de los hogares argentinos no cuentan con herramientas digitales para planificar sus finanzas. Las soluciones existentes suelen ser costosas y no están adaptadas a contextos locales. 

Este sistema ofrece:
1. **Adaptación local**: soporte para impuestos argentinos, inversiones locales y monedas variables.
2. **Accesibilidad**: funcionamiento offline con persistencia local en MySQL.
3. **Simplicidad**: interfaz en consola accesible.
4. **Personalización**: recomendaciones basadas en los datos del usuario.

## Definición del Proyecto y del Sistema

### Definición del Proyecto
El proyecto consiste en el diseño, desarrollo e implementación de un sistema informático para gestionar las finanzas personales de los usuarios, incluyendo ingresos, gastos, inversiones y recomendaciones.

### Definición del Sistema
El Sistema de Planificación Financiero (SIFIP) es un sistema basado en Java con persistencia en MySQL. Sus principales características incluyen:
- Registro y categorización de ingresos y gastos.
- Seguimiento de inversiones (acciones, criptomonedas, FCIs, plazos fijos).
- Generación de reportes financieros.
- Recomendaciones personalizadas.

### Objetivos

**Funcionales:**
- Registro y consulta de transacciones financieras.
- Seguimiento de inversiones.
- Generación de reportes y recomendaciones.

**No Funcionales:**
- Escalabilidad.
- Usabilidad.
- Seguridad.
- Eficiencia.

## Requerimientos

### Funcionales
- RF1: Registro de ingresos.
- RF2: Registro de gastos.
- RF3: Registro de activos financieros.
- RF4: Cálculo de balance financiero.
- RF5: Generación de reportes de gastos.
- RF6: Actualización de precios de activos y cálculo de rendimientos.
- RF7: Recomendación de inversiones.
- RF8: Sugerencias de hábitos financieros.

### No Funcionales
- Escalabilidad para 10,000 transacciones.
- Respuesta en menos de 2 segundos.
- Protección de datos.

## Modelo de Negocio

El sistema se desarrolla para la startup **Finanzas Fáciles**, con un modelo de negocio que incluye:
- **Propuesta de valor**: Herramientas accesibles y personalizadas para la gestión financiera.
- **Segmento de clientes**: Individuos interesados en ahorrar e invertir.
- **Fuentes de ingresos**: Suscripciones y servicios de consultoría financiera.

## Procesos del Negocio

- **Captura de datos**: Registro de ingresos, gastos e inversiones.
- **Análisis financiero**: Cálculo de balance y rendimientos.
- **Recomendaciones**: Sugerencias basadas en los datos ingresados.

## Propuesta de Solución

El sistema será modular, desarrollado en Java con persistencia en MySQL, incluyendo:
- Módulo de transacciones.
- Módulo de inversiones.
- Módulo de reportes.
- Módulo de recomendaciones.

### Arquitectura del Prototipo
- **Capa de presentación**: Interfaz en consola.
- **Capa de lógica**: Clases Java para gestionar transacciones e inversiones.
- **Capa de datos**: Conexión a MySQL mediante JDBC.

## Casos de Uso

### Registrar Ingreso
- **Actor**: Usuario.
- **Descripción**: El usuario ingresa un ingreso con monto, descripción, periodicidad y fecha.

### Consultar Balance
- **Actor**: Usuario.
- **Descripción**: El usuario consulta el balance financiero calculado desde los ingresos y gastos registrados.

## Fases del Proyecto

### Incepción
- Definición del alcance y objetivos.
- Creación del prototipo inicial.

### Elaboración
- Diseño detallado de la arquitectura y módulos.
- Modelado UML.

### Construcción
- Desarrollo completo de los módulos.
- Pruebas de integración.

### Transición
- Entrega del prototipo operativo.
- Capacitación y recolección de feedback.
