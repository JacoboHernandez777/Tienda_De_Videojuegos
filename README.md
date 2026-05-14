# Documentacion de nuestra tienda de videojuegos
### Objetivo
- El objetivo de este proyecto es desarrollar una base de datos relacional para una tienda de videojuegos que permita administrar de manera eficiente la información relacionada con juegos, clientes, consolas y ventas.
El sistema busca facilitar el control y organización de los registros, mejorar el flujo de información y garantizar la integridad de los datos mediante el uso de claves primarias y foráneas.
Ademas, el proyecto pretende aplicar los conocimientos adquiridos sobre modelado de bases de datos y creación de relaciones entre entidades utilizando phpMyAdmin.

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


# Tienda de Videojuegos



### Problema
actualmente, diversas tiendas de videojuegos operan bajo esquemas de registro manual. Esta falta de digitalización conlleva riesgos críticos como:
* Desfase entre existencias físicas y registros. 
* Vulnerabilidad ante extravío de datos de ventas. 
* Complejidad para rastrear las compras de los clientes de forma eficiente. 


Objetivo del Sistema
El propósito fundamental de este proyecto es implementar una base de datos relacional robusta que centralice y automatice la administración de juegos, clientes, consolas y transacciones. Se busca garantizar la integridad de los datos y optimizar el flujo de información mediante un diseño técnico estandarizado.

### Arquitectura Técnica
El sistema ha sido desarrollado bajo los siguientes pilares de ingeniería de datos:
**Gestor de Base de Datos:** MariaDB / MySQL administrado a través de phpMyAdmin
**Lenguaje de Estructuracion:** SQL.
**Normalización:** Aplicación estricta de la **Primera, Segunda y Tercera Forma Normal (1FN, 2FN, 3FN)** para eliminar redundancias y dependencias innecesarias.
### Modelo de Informacion
La arquitectura se sostiene en cuatro entidades principales interconectadas:

1. **Consolas:** Catálogo maestro de plataformas.
2. **Juegos:** Control de stock, titulos y precios vinculados a hardware específico.
3. **Clientes:** Registro detallado de usuarios para trazabilidad comercial. 
4. **Ventas:** Modulo transaccional que unifica al cliente con el producto mediante llaves foráneas.

**desarrollamos esto para la digitalización de inventarios y control de ventas.** 