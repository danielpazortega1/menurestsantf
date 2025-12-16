# Menú Restaurante SantF

Este es un sistema integral de Punto de Venta (POS) y administración de inventarios diseñado específicamente para entornos de alta demanda sin dependencia de conexión a internet.

El objetivo principal del software es optimizar el flujo de trabajo operativo de un restaurante, permitiendo la creación de cuentas, gestión de facturación y control de stock en tiempo real con latencia cero.

## Características Principales

### Arquitectura 100% Offline
El sistema opera de manera totalmente local, garantizando que la operación del negocio nunca se detenga por fallos de red o internet. Ideal para zonas con conectividad limitada.

### Persistencia de Datos Optimizada
Implementación de una estructura de datos basada en archivos planos (**CSV/Excel**) para el manejo del backend. Esto permite:
* **Lectura/Escritura de alta velocidad:** Acceso inmediato a la información del inventario.
* **Portabilidad:** Los datos son fácilmente accesibles y migrables sin necesidad de gestores de bases de datos complejos.

### Gestión de Cuentas y Facturación
* Apertura y cierre de mesas/cuentas.
* Generación automática de facturas y tickets de venta.
* Cálculo automático de totales e impuestos.

### Reportes Automatizados (Business Intelligence)
El sistema incluye un módulo de cierre de caja ("Corte del día") que exporta automáticamente un reporte detallado en formato **CSV/Excel** con:
* Ventas totales del día.
* Desglose por producto.
* Balance de inventario post-venta.

## Tecnologías Utilizadas
* **Frontend/Interfaz:** HTML5 / CSS3 / JavaScript (Web-based local interface).
* **Backend/Datos:** Sistema de archivos local (CSV & XLSX integration).
* **Herramientas:** Manipulación de datos para exportación automatizada.

## Instalación y Uso
1.  Clonar el repositorio o descargar el archivo `.zip`.
2.  Asegurarse de tener el archivo `InventarioTotal.xlsx` en la carpeta raíz.
3.  Ejecutar el archivo `index.html` en cualquier navegador moderno.
## Tecnologías
* HTML5
* Excel (para el control de inventario)

## Cómo ver el proyecto
[(Aquí puedes pegar el link si ya está publicado en GitHub Pages)](https://danielpazortega1.github.io/menurestsantf/)
