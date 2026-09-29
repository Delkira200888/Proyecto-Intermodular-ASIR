# 3. Seguridad y Plan de Copias de Seguridad

## 3.1. Requisitos de seguridad
Para garantizar la confidencialidad, integridad y disponibilidad de la tienda online de la ferretería y de los datos de sus clientes, se establecen las siguientes medidas de seguridad perimetral y de acceso:
- **Cifrado de comunicaciones:** Uso obligatorio de certificados SSL/TLS para asegurar que el tráfico entre los clientes y el servidor web viaje cifrado (HTTPS).
- **Control de accesos:** Restricción de privilegios en la administración de la plataforma, asegurando que solo el propietario o el administrador autorizado puedan gestionar el catálogo y los pedidos.
- **Cortafuegos (Firewall):** Filtrado de tráfico de red para bloquear peticiones maliciosas o accesos no autorizados a los puertos de los servicios internos.

## 3.2. Política de copias de seguridad (Backup)
Dado que la pérdida de datos de stock o de pedidos interrumpiría la actividad comercial del negocio, se implementará un plan automatizado de respaldos:
- **Frecuencia:** Copias de seguridad diarias de la base de datos y semanales de los ficheros de configuración y del sistema de archivos web.
- **Ubicación:** Almacenamiento redundante de los respaldos en ubicaciones externas o independientes al servidor de producción principal.
- **Pruebas de restauración:** Verificación periódica de la integridad de los ficheros de copia para asegurar que se pueden recuperar con éxito en caso de fallo crítico.
