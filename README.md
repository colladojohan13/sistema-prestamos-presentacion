# Sistema de gestión de préstamos

Aplicación web para prestamistas que centraliza clientes, préstamos, cuotas, cobros, caja y documentos en un solo lugar.

> Este repositorio es únicamente una presentación del producto. El código fuente, la base de datos y los componentes internos no se distribuyen públicamente.

## Funciones principales

- Registro y administración de clientes.
- Creación, aprobación y desembolso de préstamos.
- Interés fijo sobre el monto prestado.
- Calendarios de pago semanales, quincenales o mensuales.
- Registro de pagos parciales y completos.
- Control de mora, días de gracia y cuotas atrasadas.
- Alertas de cobro y seguimientos pendientes.
- Gestión de caja, gastos y cierres.
- Reportes de cobros y cartera.
- Contratos, pagarés, recibos y tablas de cuotas en PDF.
- Firmas digitales y registro de auditoría.
- Roles de administrador y cobrador.
- Configuración de empresa, logo y datos de contacto.
- Diseño adaptable a computadoras y teléfonos.

## Flujo de trabajo

```mermaid
flowchart LR
    A[Registrar cliente] --> B[Crear préstamo]
    B --> C[Aprobar]
    C --> D[Desembolsar]
    D --> E[Registrar cobros]
    E --> F[Reportes y cierre de caja]
```

## Tecnologías

- Python 3.12 y Django 5.2.
- HTML, CSS y JavaScript.
- SQLite para desarrollo local.
- Preparado para PostgreSQL en producción.
- ReportLab y Pillow para documentos e imágenes.
- Gunicorn y WhiteNoise para despliegue.

## Modalidad de entrega

El sistema se ofrece mediante demostración y contratación privada. La implementación, el código fuente y el acceso a datos se administran por separado según el acuerdo con cada cliente.

## Contacto

Para solicitar una demostración o información comercial, comunícate directamente con el propietario del proyecto.

## Propiedad intelectual

Copyright © 2026. Todos los derechos reservados. Consulta [LICENSE.md](LICENSE.md).

