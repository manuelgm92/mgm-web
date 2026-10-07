---
title: "Spring Hotel App"
excerpt: "Aplicación web desarrollada con Java, Spring Boot y MySQL para la gestión integral de un hotel."
classes: wide           # Amplía el ancho máximo del contenedor de la página
layout: single
author_profile: true
header:
  image: "https://images.unsplash.com/photo-1652057295518-d2a109170821?q=80&w=1200&h=400&auto=format&fit=crop"
  teaser: "https://images.unsplash.com/photo-1652057295518-d2a109170821?q=80&w=400&h=225&auto=format&fit=crop"
  actions:
    - label: "<i class='fab fa-fw fa-github'></i> Ver Código en GitHub"
      url: "https://github.com/PrimeraEdicionFlexible/ProyectoFinalEquipoJ.git"

---

## 🏨 Sobre el Proyecto

**Spring Hotel App** es un sistema de gestión hotelera diseñado para optimizar el control diario de un establecimiento. Permite centralizar las operaciones clave —como la administración de huéspedes, control de habitaciones y el seguimiento de reservas e incidencias— en una interfaz web limpia y funcional.

El sistema fue desarrollado de forma colaborativa como proyecto final, aplicando arquitectura backend robusta con Java y persistencia avanzada de datos.

---

## 🔑 Características Principales

* **Control de Acceso por Roles (RBAC):**
  * **Recepcionistas:** Tienen permisos operativos completos para consultar, crear, editar y dar de baja registros de clientes, habitaciones y reservas.
  * **Supervisores:** Perfil de gestión enfocado en la supervisión global del sistema, acceso de solo lectura a operaciones críticas y administración de usuarios.
* **Gestión de Incidencias:** Módulo dedicado a reportar y resolver problemas o mantenimientos en las instalaciones del hotel.
* **Autenticación Segura:** Sistema de login propio integrado en la arquitectura de la aplicación.

---

## 🛠️ Stack Tecnológico

* **Backend:** Java 11, Spring MVC, Spring ORM / Hibernate
* **Base de Datos:** MySQL 8+ (con scripts de inicialización estructurados)
* **Vista:** JSP (JavaServer Pages) & HTML/CSS
* **Despliegue:** Apache Tomcat 9.x
* **Dependencias:** Maven

---

## 💡 Lo que aprendí y retos superados

* Estructurar una aplicación web completa bajo el patrón **Modelo-Vista-Controlador (MVC)** utilizando el ecosistema de Spring.
* Gestionar relaciones complejas de bases de datos relacionales (como la asociación entre reservas, huéspedes e incidencias) mediante **Hibernate**.
* Implementar seguridad a nivel de rutas y lógica de negocio diferenciando perfiles de usuario.

---

[🔗 Accede al repositorio completo en GitHub](https://github.com/PrimeraEdicionFlexible/ProyectoFinalEquipoJ.git){: .btn .btn--primary .btn--lg}