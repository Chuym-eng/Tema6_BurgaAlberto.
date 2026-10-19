# Documento de Visión v1 - Sistema de reservas de citas
## 1. Propósito
Permitir agilizar el servicio brindado a los clientes 
## 2. Problema
La falta de un sistema para la gestión de ventas e inventario
## 3. Alcance
- Incluye: registro de clientes, registro de ventas, registro de producto, gestión de inventario,
inicio de sesión.
- No incluye: pagos en línea, historia clínica, telemedicina.
## 4. Interesados
| Rol | Necesidad |
|---|---|
| Cajero | registra ventas, clientes y genera el comprobante de venta |
| Almacenero | registra productos e ingresos de mercadería, y controla el inventario y las alertas de stock |
| Vendedor |  | inicia sesión y busca prendas para atender al cliente |
| Cliente | | compra las prendas y recibe el comprobante |
| Proveedor | | suministra la mercadería que luego se registra en el inventario |
| Administrador | Recibe reportes acerca de las ventas realizadas |
## 5. Objetivos medibles
- Reducir el tiempo de espera de 8 a 9 minutos hacia 2 a 4 minutos
- Implementar una alarma si el stock es < 10.
## 6. Requisitos de alto nivel
- REQ-001: Registrar Cliente
- REQ-002: Registrar venta
- REQ-003: Registrar producto
- REQ-003: Revisar inventario
- REQ-004: Iniciar sesión
## 7. Restricciones
Debe funcionar en navegador. Primera versión en 7 semanas.
