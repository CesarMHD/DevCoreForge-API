# DevCoreForge - API 🛠️

**DevCoreForge API** es el motor de persistencia y lógica de negocio de mi mesa de trabajo personalizada. Esta API está diseñada para gestionar el almacenamiento estructurado de proyectos, ideas y, fundamentalmente, la **bitácora técnica de procesos**, permitiendo que cada solución de ingeniería sea consultable y reutilizable.

> ⚠️ **Estado del Proyecto:** En fase de diseño de base de datos y definición de modelos.

---

## 🚀 Tecnologías Utilizadas

*   **Framework:** Laravel 11
*   **Base de Datos:** MySQL
*   **Autenticación:** Laravel Sanctum (Tokens API seguros)
*   **Documentación:** Swagger / OpenApi para el testing de endpoints.

---

## 📋 Características del Proyecto

- **Estructura de Bitácora Técnica:** Modelado de datos optimizado para guardar procesos paso a paso, permitiendo almacenar fragmentos de código, comandos y configuraciones específicas por proyecto.
- **Gestión de Entidades de Ingeniería:** CRUD completo para proyectos que incluye stack tecnológico, objetivos de negocio y materiales necesarios.
- **Motor de Priorización:** Lógica de backend para el filtrado y selección de proyectos basada en importancia, urgencia o selección aleatoria (Ruleta).
- **Sistema de Notas e Ideas:** Almacenamiento independiente para conceptos de proyectos en fase de ideación.

---

## 🔌 Conexión con el Frontend

Esta API sirve datos de forma desacoplada al cliente desarrollado en Angular.
> [Repositorio Frontend](https://github.com/CesarMHD/devcoreforge-client.git)

---

## ⚙️ Instalación y Configuración

1. **Clonar el proyecto:**
   ```bash
   git clone https://github.com/CesarMHD/devcoreforge-api.git
