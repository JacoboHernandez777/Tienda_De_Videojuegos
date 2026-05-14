# Documentacion de nuestra tienda de videojuegos

### Objetivo

El objetivo de este proyecto es desarrollar una base de datos relacional para una tienda de videojuegos que permita administrar de manera eficiente la información relacionada con juegos, clientes, consolas y ventas.
El sistema busca facilitar el control y organización de los registros, mejorar el flujo de información y garantizar la integridad de los datos mediante el uso de claves primarias y foráneas.
Ademas, el proyecto pretende aplicar los conocimientos adquiridos sobre modelado de bases de datos y creación de relaciones entre entidades utilizando phpM.

### Integrantes del equipo
#### Datos personales
- Nombre Completo: Leonardo Vargas Lopez
- Edad:17
- Correo Electronico: 23308060610434@cetis61.edu.mx
- Especialidad: Programacion
- Institucion: Cetis61
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
* Desajuste de inventario lo que aparece en la libreta no siempre coincide con lo que realmente hay en la bodega.. 
* Perdida de informacion, si se extravía un cuaderno o una hoja, se pierden datos valiosos de ventas.. 
* Dificultad para rastrear que compro cada cliente y cuándo, lo que complica ofrecer un buen servicio o promociones personalizadas.


Objetivo del Sistema
El propósito fundamental de este proyecto es implementar una base de datos relacional robusta que centralice y automatice la administración de juegos, clientes, consolas y transacciones. Se busca garantizar la integridad de los datos y optimizar el flujo de información mediante un diseño técnico estandarizado.

### Arquitectura Técnica
El sistema ha sido desarrollado bajo los siguientes pilares de ingeniería de datos:
**Gestor de Base de Datos:** MariaDB / MySQL administrado a través de phpMyAdmin
**Lenguaje de Estructuracion:** SQL.
**Normalización:** Aplicación estricta de la **Primera, Segunda y Tercera Forma Normal (1FN, 2FN, 3FN)** para eliminar redundancias y dependencias innecesarias.
### Modelo de Informacion
La arquitectura se sostiene en cuatro entidades principales interconectadas:

1. **Consolas:** Catalogo de plataformas.
2. **Juegos:** Control de stock, titulos y precios vinculados a hardware especifico.
3. **Clientes:** Registro detallado de usuarios para tener un historial claro y ordenado de las compras y clientes. 
4. **Ventas:** modulo que registra las ventas y relaciona al cliente con el producto comprado.

**desarrollamos esto para la digitalización de inventarios y control de ventas.** 