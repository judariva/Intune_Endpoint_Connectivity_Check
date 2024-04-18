# Verificación de Conectividad con Endpoints de Intune

¡Hola! Soy Juan David Rivera, especialista en ciberseguridad. Hoy te ofrezco un script de PowerShell diseñado para verificar la conectividad con los endpoints de Microsoft Intune utilizando direcciones IP y URLs. Esta herramienta es esencial para garantizar que la infraestructura de tu empresa mantenga una comunicación efectiva y segura con los servicios de Intune.

## Contexto

Con la creciente adopción de servicios en la nube, la continuidad de las operaciones empresariales depende en gran medida de conexiones de red robustas y confiables. Interrupciones en la conectividad pueden llevar a pérdidas significativas en productividad y potencial económico. Este script proactivamente identifica problemas de conectividad, permitiendo a los administradores de TI resolver rápidamente incidencias antes de que afecten las operaciones.

## Características del Script

El script automatiza varias tareas críticas:

- **Inicialización de Registro**: Prepara un entorno de log, creando directorios necesarios para almacenar los registros de las pruebas de conectividad.
- **Recuperación de Endpoints de Intune**: Utiliza la API de Office 365 para obtener las direcciones IP y URLs relevantes a los servicios de Intune.
- **Resolución de Nombres DNS**: Para URLs especificadas, resuelve los nombres DNS y maneja distintos tipos de entrada, como URLs y direcciones IP.
- **Pruebas de Conectividad**: Ejecuta pruebas de conectividad usando `Test-NetConnection` para evaluar la accesibilidad de cada endpoint y registra los resultados.

Este enfoque estructurado y automatizado asegura una evaluación completa y documentada de la conectividad, facilitando el mantenimiento y la solución de problemas de red.

## Prerrequisitos

Antes de utilizar este script, asegúrate de tener:

- **PowerShell 5.1 o superior**: Necesario para la ejecución de scripts avanzados y manejo de errores.
- **Acceso a Internet**: Imprescindible para realizar las pruebas de conectividad y resolución de DNS.
- **Permisos de Administrador**: Requeridos para ejecutar comandos que pueden afectar la configuración del sistema y realizar cambios en los directorios.

## Instrucciones de Uso

Sigue estos pasos para ejecutar el script efectivamente:

1. **Descargar el Script**: Clona este repositorio en tu máquina local o descarga el script directamente desde GitHub.
2. **Abrir PowerShell como Administrador**: Esto es necesario para permitir la ejecución de scripts y la modificación de configuraciones de red.
3. **Navegar al Directorio del Script**: Utiliza `cd ruta_del_script` para colocarte en el directorio donde resides el script.
4. **Ejecutar el Script**: Inicia el script con `.\Intune_Endpoint_Connectivity_Check.ps1`. Los logs y resultados se guardarán automáticamente en los directorios configurados dentro del script.

## Contacto y Soporte

Si encuentras problemas o tienes preguntas sobre la personalización y ejecución del script, no dudes en contactarme. Estoy aquí para ayudarte a optimizar la seguridad y funcionalidad de tu infraestructura IT.

Visita mi página web para más recursos y contacto: [https://juandavidrivera.com/](https://juandavidrivera.com/)
