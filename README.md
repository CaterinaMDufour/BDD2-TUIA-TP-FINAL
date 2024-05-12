# BDD2-TUIA-TP-FINAL

## Desarrollo del Trabajo Práctico:
Este documento consta de:
  • Situación de Negocio
  • Descripción de las fuentes de datos a utilizar
  • Consultas requeridas por el departamento de Ventas

### Situación de Negocio:
Ud. es un administrador de base de datos para una compañía llamada The Drinking Company (TDC). La compañía produce bebidas de distintas categorías que comercializa tanto en el mercado minorista (retail) como en el mercado mayorista (wholesale) y trabaja los 365 días del año. TDC tiene una trayectoria de 4 años en el mercado con un gran éxito en el rubro. Posee un área de ventas que abarca varios estados de los Estados Unidos, repartidos en 4 regiones (east), oeste (west), central (central) y sur (south). Los productos que comercializa TDC están divididos en 5 rubros: colas (cola), cervezas (beer), sodas (soda), jugos (juice) y bebidas energizantes (energy drink). Dichos productos pueden tener varias presentaciones: botellas de 1 litro, botellas de 2 litros, botellas de 670 cm3 , latas de 330 cm3 y latas de 500 cm3 .

El departamento de finanzas quiere rastrear, analizar y pronosticar el ingresode las ventas, a través de las zonas geográficas, los productos, los clientes y diferentes períodos de tiempo. Ud. ya ha definido algunas consultas básicas. Sin embargo, estas consultas agregan trabajo a la base de datos operacional. Además, los usuarios solicitan consultas adicionales a medida que las necesitan. Su compañía ha decidido crear un Data Mart para la información de ventas. Un Data Warehouse contiene información que ha sido limpiada y transformada a un formato “informativo” y no operacional.

### Estructura del Repositorio:
Los puntos a desarrollar en el Trabajo Practico son los siguientes:
- **Diagrama estrella del Data Warehouse:** Utilizando los conceptos aprendidos, crea un diagrama estrella que represente la estructura lógica de tu Data Warehouse ( detallar tabla de hechos , dimensiones , sus relaciones y los atributos de las mimas, marcar PK y FK, cardinalidad y jerarquías si las hubiera )
- **Definir el flujo de datos y las tareas para creación del Data mart**
- **Implementación del Data Warehouse:** Basado en el punto anterior, crear una base de datos para el Data Warehouse utilizando SQL Server.
- **Carga del Data Warehouse:** Describe detalladamente los pasos necesarios para cargar correctamente el Data Warehouse. Incluye la extracción de datos desde diferentes fuentes, su transformación y limpieza, y finalmente, la carga en las tablas del Data Warehouse. Se deberá contemplar: 
  ○ Carga de datos desde las bases de datos operativa de la empresa
  ○ Carga de datos desde fuentes externas de ser necesario
- **Implementación de ETL en SSIS:** Utilizando SQL Server Integration Services (SSIS), implementa los pasos descritos anteriormente para cargar el Data Warehouse. Asegúrate de mostrar un flujo de trabajo lógico y eficiente utilizando las herramientas proporcionadas por SSIS.
- **Creación de Dashboards para la gerencia:** Utilizando PowerBI u otra herramienta de visualización de datos de tu elección desarrollar los tableros y reportes necesarios
