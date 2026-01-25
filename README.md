# Política de Privacidad de PDV Sync Mobile

**Última actualización:** [25 de enero 26]

## 1. Introducción

**PDV Sync Mobile** es una aplicación corporativa diseñada para el uso exclusivo de empleados y colaboradores autorizados. La aplicación tiene como objetivo la gestión de actividades en puntos de venta, recolección de información de campo y auditoría de ejecución.

Al ser una herramienta de trabajo proporcionada por su empleador, la aplicación recopila datos específicos necesarios para validar la ejecución de sus labores.

## 2. Información que recopilamos

Para cumplir con sus funciones operativas, la aplicación solicita y utiliza los siguientes permisos y datos:

### A. Ubicación (GPS y Red)
La aplicación recopila datos de ubicación precisa y aproximada.
*   **¿Cómo se usa?** La ubicación se utiliza en **primer plano** (mientras usa la app) y en **segundo plano** (mientras la app está cerrada o minimizada) a través de un servicio de rastreo.
*   **¿Para qué?**
    *   Validar su presencia física en los Puntos de Venta (Geocerca).
    *   Registrar el cumplimiento de la ruta de visitas asignada.
    *   Auditoría de tiempos y movimientos durante la jornada laboral.
*   **Datos adicionales:** Junto con la ubicación, registramos el **nivel de batería** del dispositivo y detectamos el uso de aplicaciones de **"Mock Location"** (Ubicación Falsa) o cambios manuales en la hora del sistema para garantizar la integridad de los datos reportados.

### B. Cámara y Galería
*   **¿Cómo se usa?** La aplicación utiliza la cámara del dispositivo.
*   **¿Para qué?**
    *   Tomar fotografías de exhibiciones, productos y material publicitario como evidencia de trabajo.
    *   Escanear códigos de barras (usando ML Kit para identificar productos.

### C. Sensores del Dispositivo
*   **¿Cómo se usa?** Accedemos al **acelerómetro** y **magnetómetro**.
*   **¿Para qué?** Para la funcionalidad de "Nivelador" en la cámara, ayudando al usuario a tomar fotografías rectas y alineadas.

### D. Identificación y Biometría
*   **Autenticación:** Utilizamos credenciales corporativas (correo y contraseña) gestionadas a través de Firebase Auth.
*   **Biometría:** Si su dispositivo lo permite, puede usar su huella digital o reconocimiento facial para iniciar sesión rápidamente. **Nota:** Los datos biométricos se procesan exclusivamente en el hardware de su dispositivo y **nunca** son enviados a nuestros servidores.

### E. Almacenamiento (Archivos)
*   La aplicación almacena localmente las evidencias (fotos) y registros de actividad temporalmente antes de sincronizarlos con la nube. Esto permite trabajar en zonas con baja conectividad.

## 3. Uso de la Información

La información recopilada se utiliza exclusivamente para fines laborales y operativos de la empresa que contrata el servicio:
*   Supervisión de la ejecución en punto de venta.
*   Generación de reportes de disponibilidad de productos y precios.
*   Evaluación de desempeño basada en visitas y cumplimiento de rutas.
*   Auditoría de seguridad para prevenir fraudes en el reporte de visitas (detección de ubicación falsa).

## 4. Compartir Información

Sus datos son compartidos con:
*   **Su Empleador:** Quien tiene acceso total a los reportes, fotos, ubicaciones y horarios registrados por la app.
*   **Proveedores de Servicios (Terceros):**
    *   **Google Firebase:** Para autenticación, base de datos, almacenamiento de fotos y análisis de errores.
    *   **Google Maps Platform:** Para visualización de mapas y servicios de geolocalización.

No vendemos ni compartimos su información personal con terceros para fines publicitarios o de marketing.

## 5. Seguridad de los Datos

Implementamos medidas de seguridad estándar de la industria para proteger sus datos:
*   Todas las comunicaciones con el servidor están encriptadas (HTTPS/TLS).
*   El acceso a los datos está restringido según los roles y permisos definidos por la organización.

## 6. Retención y Eliminación de Datos

*   **Retención:** Los datos operativos (visitas, fotos) se conservan.
*   **Eliminación:** Al ser una herramienta corporativa, la solicitud de eliminación de datos de cuenta debe tramitarse a través del departamento de RRHH o TI de su empresa. Si deja de laborar para la empresa, su acceso será revocado por el administrador.

## 7. Contacto

Si tiene dudas sobre esta política de privacidad o el manejo de sus datos, puede contactar al soporte técnico de la aplicación.

---
*Este documento es informativo y complementa los contratos laborales y políticas internas de su empresa.*
