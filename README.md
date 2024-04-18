# Verificación de Conectividad con Endpoints de Intune

¡Hola! Soy Juan David Rivera, especialista en ciberseguridad. Te presento un script de PowerShell para verificar la conectividad con los endpoints de Microsoft Intune utilizando direcciones IP y URLs, esencial para mantener comunicaciones seguras y efectivas con los servicios de Intune.

## Contexto

Con el incremento de la adopción de servicios en la nube, la continuidad operativa empresarial depende de conexiones de red robustas. Este script identifica proactivamente problemas de conectividad, permitiendo a los administradores de TI actuar rápidamente para mitigar impactos.

## Características del Script

Este script automatiza tareas críticas incluyendo:

- **Inicialización de Registro**: Configura un entorno de log para almacenar registros de conectividad.
- **Recuperación de Endpoints de Intune**: Obtiene las direcciones IP y URLs de los servicios de Intune mediante la API de Office 365.
- **Resolución de Nombres DNS**: Resuelve los nombres DNS y maneja diferentes tipos de entrada, como URLs y direcciones IP.
- **Pruebas de Conectividad**: Realiza pruebas de conectividad y documenta los resultados, facilitando la solución de problemas.

## Prerrequisitos

Antes de ejecutar este script, asegúrate de cumplir con los siguientes requisitos:

- **PowerShell 5.1 o superior**: Necesario para la ejecución de scripts avanzados.
- **Acceso a Internet**: Imprescindible para realizar pruebas de conectividad.
- **Permisos de Administrador**: Requeridos para ejecutar comandos que afectan la configuración del sistema.

## Instrucciones de Uso

Para usar este script, sigue estos pasos:

1. **Descargar el Script**: Descarga el script desde el [repositorio de GitHub](https://github.com/judariva/Intune_Endpoint_Connectivity_Check/releases/latest).
2. **Abrir PowerShell como Administrador**: Esto es necesario para ejecutar scripts y modificar configuraciones de red.
3. **Navegar al Directorio del Script**: Usa `cd ruta_del_script` para moverte al directorio donde resides el script.
4. **Ejecutar el Script**: Inicia el script con `.\Intune_Endpoint_Connectivity_Check.ps1`. Los resultados se guardarán en los directorios configurados.

## Contacto y Soporte

Para preguntas o asistencia personalizada con el script, contáctame. Estoy aquí para ayudar a mejorar la seguridad y eficiencia de tu infraestructura IT.

Visita mi página web para más recursos y contacto: [https://juandavidrivera.com/](https://juandavidrivera.com/)
