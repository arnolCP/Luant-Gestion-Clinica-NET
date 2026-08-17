# Sistema Web de Gestión Clínica (Luant)

Sistema integral de gestión odontológica desarrollado con arquitectura monolítica modular multicapa. Diseñado para optimizar los procesos operativos de admisión, historias clínicas y facturación.

**[Ver Sistema en Producción (Live Demo)](http://proyfinal.somee.com/)**
*(Desplegado en Somee.com con base de datos MS SQL)*

## Tecnologías y Arquitectura
*   **Backend:** C#, ASP.NET Core MVC
*   **Persistencia:** SQL Server Express, Entity Framework Core (ORM)
*   **Patrones de Diseño:** Repository Pattern, Inyección de Dependencias, Arquitectura Multicapa
*   **Frontend:** Razor Views, HTML5, CSS3, JavaScript
*   **Despliegue:** Somee.com (App Hosting & Database)

## Módulos Principales
*   **Gestión de Seguridad:** Autenticación, autorización por roles (Administrador, Recepcionista, Especialista) y registro de auditoría.
*   **Gestión de Citas:** Programación, reprogramación y validación de disponibilidad de especialistas.
*   **Gestión Clínica:** Control de historias clínicas, registro de diagnósticos y tratamientos realizados.
*   **Facturación:** Generación de comprobantes de pago y control de saldos.

## Documentación Técnica
El diseño detallado de la arquitectura bajo el modelo 4+1 vistas, diagramas UML (Secuencia, Clases, Despliegue) y el modelo relacional de la base de datos se encuentran documentados en el siguiente archivo:
*   [Ver Documento de Arquitectura y Diseño de Sistemas](./DISEÑO_DE_SISTEMAS.pdf)

---
*Nota: El código fuente de la solución de Visual Studio se subirá próximamente.*
