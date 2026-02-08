# LanzAudit - Juan García Lanza
LanzAudit es una aplicación web para realizar y gestionar auditorías de seguridad, con la capacidad de ejecutar escaneos con herramientas de uso profesional como Nmap y WPScan a través de una interfaz web Flask muy intuitiva.

Está diseñada para su uso en el ámbito empresarial, permitiendo realizar auditorías y analizarlas sin la necesidad de contar con amplios conocimientos técnicos en Ciberseguridad.

## Gestión de usuarios y roles
La aplicación incluye un sistema de gestión de usuarios y roles para los Administradores. Los roles disponibles son:
- Admin: Control total sobre la aplicación, gestión de usuarios y escaneos.
- Worker: Ejecución y gestión de sus propios escaneos.
- Analyst: Análisis de escaneos realizados por Workers o Admins.

## Generación automática de informes
LanzAudit incorpora un sistema basado en IA capaz de generar informes profesionales en PDF de forma rápida, en un formato claro y presentable.

## Estructura del repositorio
El repositorio incluye:
- **LanzAudit-Produccion/** ➡️​ Instalación y despliegue manual en servidor o VPS.
- **LanzAudit-Docker/** ➡️​ Despliegue rápido mediante Docker.

## Sobre el proyecto
Esta aplicación ha sido desarrollada por Juan García Lanza en el año 2025 para ser presentada como Proyecto de Administración de Sistemas Informáticos en Red.
