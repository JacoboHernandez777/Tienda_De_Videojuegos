# Documentacion de nuestra tienda de videojuegos
### Objetivo
- El objetivo de este proyecto es desarrollar una base de datos relacional para una tienda de videojuegos que permita administrar de manera eficiente la información relacionada con juegos, clientes, consolas y ventas.
El sistema busca facilitar el control y organización de los registros, mejorar el flujo de información y garantizar la integridad de los datos mediante el uso de claves primarias y foráneas.
Además, el proyecto pretende aplicar los conocimientos adquiridos sobre modelado de bases de datos y creación de relaciones entre entidades utilizando phpMyAdmin.

### Integrantes del equipo
#### Datos personales
- Nombre Completo: Leonardo Vargas Lopez
- Edad:[17]
- Correo Electronico: 23308060610434@cetis61.edu.mx
- Especialidad: Programacion
- Institucion: [Cetis61]
  #### fotografia
  <img width="236" height="248" alt="image" src="https://github.com/user-attachments/assets/e526fa82-66ea-4b21-9d92-b7ee81f6ef2d" />

 #### Datos personales
- Nombre Completo: Víctor Manuel Jacobo Hernández
- Edad:[17]
- Correo Electronico: 23308060610160@cetis61.edu.mx
- Especialidad: Programacion
- Institucion: [Cetis61]
  #### fotografia
<img width="236" height="248" alt="image" src="https://github.com/user-attachments/assets/494a8f96-0f8c-422e-a2de-f6f6f6474367" />

---



# Tienda de Videojuegos



### Problema
[cite_start]actualmente, diversas tiendas de videojuegos operan bajo esquemas de registro manual. [cite: 32] Esta falta de digitalización conlleva riesgos críticos como:
* [cite_start]**Errores de Inventario:** Desfase entre existencias físicas y registros. [cite: 32]
* [cite_start]**Pérdida de Información:** Vulnerabilidad ante extravío de datos de ventas. [cite: 32]
* [cite_start]**Dificultad Administrativa:** Complejidad para rastrear las compras de los clientes de forma eficiente. [cite: 32]

### 🎯 Objetivo del Sistema
[cite_start]El propósito fundamental de este proyecto es implementar una base de datos relacional robusta que centralice y automatice la administración de juegos, clientes, consolas y transacciones. [cite: 37] [cite_start]Se busca garantizar la integridad de los datos y optimizar el flujo de información mediante un diseño técnico estandarizado. [cite: 38]

### 🛠️ Arquitectura Técnica (Stack de Desarrollo)
El sistema ha sido desarrollado bajo los siguientes pilares de ingeniería de datos:
* [cite_start]**Gestor de Base de Datos:** MariaDB / MySQL administrado a través de **phpMyAdmin**. [cite: 39, 103]
* [cite_start]**Lenguaje de Estructuración:** SQL (Structured Query Language). [cite: 28, 111]
* [cite_start]**Normalización:** Aplicación estricta de la **Primera, Segunda y Tercera Forma Normal (1FN, 2FN, 3FN)** para eliminar redundancias y dependencias innecesarias. [cite: 24, 25, 26, 95]

### 📊 Modelo de Información
[cite_start]La arquitectura se sostiene en cuatro entidades principales interconectadas: [cite: 33, 34, 35]

1.  [cite_start]**Consolas:** Catálogo maestro de plataformas. [cite: 56, 57]
2.  [cite_start]**Juegos:** Control de stock, títulos y precios vinculados a hardware específico. [cite: 61, 62]
3.  [cite_start]**Clientes:** Registro detallado de usuarios para trazabilidad comercial. [cite: 69, 70]
4.  [cite_start]**Ventas:** Módulo transaccional que unifica al cliente con el producto mediante llaves foráneas. [cite: 75, 76, 116]

---
[cite_start]**Desarrollado como solución integral para la digitalización de inventarios y control de ventas.** [cite: 119, 120]