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

## Vistas de Arquitectura

**Modelo de Dominio**

![Modelo de Dominio](Diagramas_UML/Modelo%20de%20Dominio.png)

**Interfaces entre Capas**

![Interfaces entre capas](Diagramas_UML/Interfaces%20entre%20capas.png)

## Documentación Técnica
El diseño detallado de la arquitectura bajo el modelo 4+1 vistas, diagramas UML y el modelo relacional de la base de datos se encuentran documentados en los siguientes archivos:
*   [Ver Documento de Arquitectura y Diseño de Sistemas](Sistema%20de%20Gestión%20de%20Atención%20-%20DISEÑO%20DE%20SISTEMAS.pdf)
*   [Ver Diagrama de Casos de Uso detallado](Diagramas_UML/Diagrama%20de%20Casos%20de%20Uso.pdf)

---
*Nota: El código fuente de la solución de Visual Studio se subirá próximamente.*
