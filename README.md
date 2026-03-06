# docs-traceability-delivery-v2 📄📦

**Proyecto: Sistema para el Registro y Trazabilidad de Recepción de Mercancía** **Módulo III - Diplomado de Diseño Web**

Este repositorio contiene la documentación técnica y los diagramas de base de datos del sistema de gestión de mercancía. El enfoque principal de esta entrega es demostrar la integridad referencial y la trazabilidad de operaciones mediante el uso de Supabase como backend.

<img width="1366" height="767" alt="home" src="https://github.com/user-attachments/assets/229c8eaf-816f-4627-8cac-f48a974315fc" />

## 🛠️ Stack Tecnológico
* **Frontend:** React + TypeScript + Tailwind CSS.
* **Backend/DB:** Supabase (PostgreSQL).
* **Despliegue:** Netlify.

## 📋 Especificaciones de la Entrega
- [x] **Estructura Relacional:** 8 tablas normalizadas con llaves primarias (UUID) y foráneas.
- [x] **Trazabilidad Automática:** Implementación de campos de tiempo con zonas horarias (TIMESTAMPTZ) en todas las entidades.
- [x] **Sistema de Auditoría:** Bitácora inmutable para el registro detallado de acciones CRUD.
- [x] **Scripts SQL:** Archivos independientes para la creación de esquemas y carga de data maestra.

## 📂 Estructura de Documentación (Scripts .sql)
Los scripts se han segmentado por entidad, incluyendo la estructura de tabla y registros iniciales:

* `productos_rows.sql`: Catálogo maestro de productos.
* `facturas_rows.sql`: Transacciones de recepción de mercancía.
* `perfiles_rows.sql`: Perfiles de usuario y niveles de acceso.
* `proveedores_rows.sql`: Directorio de suministradores.
* `categorias_rows.sql`: Clasificación por rubros de inventario.
* `unidades_medida_rows.sql`: Estandarización de medidas base.
* `ajustes_recepcion_rows.sql`: Control de mermas y correcciones.
* `bitacora_rows.sql`: Registro histórico de auditoría.
* `DATOS_PROYECTO.txt`: Credenciales de acceso para el entorno de pruebas.

## 🗄️ Estructura de Base de Datos (Supabase)

<img width="1366" height="768" alt="supabase tables" src="https://github.com/user-attachments/assets/d2f03764-339a-4b61-a5bf-a776f94302f3" />

---
*Documentación creada para la evaluación oficial del Módulo III.*
