# Tienda Lupita - Java Application
# Resumen Ejecutivo

## Descripción
La aplicación **Tienda Lupita** es un sistema de gestión para una tienda y papelería que permite administrar productos y clientes. Esta aplicación es un software de escritorio basado en Java que no requiere un servidor web, ya que se ejecuta localmente desde un archivo JAR.

## Problema identificado
Las pequeñas tiendas y papelerías a menudo carecen de un sistema eficiente para gestionar su inventario y clientes, lo que puede resultar en un manejo manual ineficiente. **Tienda Lupita** fue creada para ofrecer una solución automatizada que gestione productos, clientes y otros aspectos de la tienda de manera sencilla.

## Solución
La solución consiste en una aplicación en Java que permite realizar las siguientes funcionalidades:
- **Gestión de productos:** Agregar, modificar y eliminar productos en el inventario.
- **Gestión de clientes:** Agregar, modificar y eliminar clientes de la base de datos.
- **Gestión de ventas:** Registra las ventas y mantiene un historial.
  
## Arquitectura
La arquitectura de la aplicación está basada en Java y se organiza de la siguiente manera:
- **Java SE** para la lógica de la aplicación.
- **Base de datos local** (por ejemplo, SQLite o H2) para almacenar los datos de productos y clientes.
- **Interfaz de línea de comandos (CLI)** para la interacción del usuario.

---

# Tabla de Contenidos

- [Descripción](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Descripción)
- [Problema Identificado](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Problema-Identificado)
- [Solución](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Solución)
- [Arquitectura](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Arquitectura)
- [Requerimientos](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Requerimientos)
- [Instalación](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Instalación)
- [Configuración](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Configuración)
- [Uso](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Uso)
- [Contribución](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Contribución)
- [Roadmap](https://github.com/alejandrohdzlop/TiendaLupita/wiki/Roadmap)


---

## Requerimientos

### Software Requerido:
- **Java:** 8 o superior.
- **Base de datos:** SQLite o H2 (configurable).
- **Sistema operativo:** Windows, Linux o macOS.

### Dependencias:
- Las dependencias del proyecto se gestionan mediante **Maven**.

---

## Instalación

### 1. Clonar el Repositorio
      Para comenzar a trabajar con la aplicación, primero clona el repositorio en tu máquina local:

```git clone https://github.com/alejandrohdzlop/TiendaLupita.git```

### 2. Instalar Dependencias
Las dependencias se gestionan a través de Maven, por lo que necesitas tener Maven instalado en tu máquina. Para instalar Maven, sigue la guía oficial: Guía de instalación de Maven.


### 3. Generar el archivo JAR
Una vez que hayas clonado el repositorio, navega a la carpeta del proyecto y ejecuta el siguiente comando para compilar el código y generar el archivo JAR:

```
mvn clean package
```

Esto creará un archivo .jar en la carpeta target/.



