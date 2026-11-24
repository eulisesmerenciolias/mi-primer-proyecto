# Cuba Ruta — primera versión administrativa

Prototipo web de una plataforma de contratación y administración de transporte de cargas.

## Ejecutar
Abrir `index.html` en un navegador moderno. No requiere instalación ni servidor.

## Módulos incluidos
- Resumen de operación.
- Registro y edición de viajes: contenedores, mudanzas, carga agrícola, mercancías empresariales y carga general.
- Registro de transportistas y modalidad de explotación del vehículo.
- Clientes y vehículos.
- Control administrativo de importes, pagos y referencias.
- Parámetros manuales de tipo de cambio y comisión de referencia.
- Exportación de respaldo JSON.

## Limitaciones importantes
- Los datos se guardan en el almacenamiento local del navegador.
- No hay autenticación real, roles, sincronización entre dispositivos ni base de datos central.
- No se ejecutan cobros ni transferencias bancarias.
- No se consulta automáticamente la tasa de elTOQUE; la tasa es manual hasta integrar una API autorizada.
- Los datos iniciales son ficticios y sirven únicamente para demostrar el flujo.

## Siguiente etapa técnica
Implementar backend y base de datos, autenticación de administrador/operador, permisos, registro de auditoría, almacenamiento de comprobantes y despliegue web. Posteriormente evaluar integraciones de pagos con proveedores autorizados.
