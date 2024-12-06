# Tienda_Lupita

# Resumen Ejecutivo

# Descripción
Tienda_Lupita es un sistema de gestión web diseñado para optimizar las operaciones de una tienda y papelería. Permite administrar productos y clientes de manera eficiente, proporcionando herramientas para el control del inventario, registro de clientes y seguimiento de datos temporales mediante cookies.

# Problema Identificado
La tienda enfrenta desafíos como:

Falta de un sistema centralizado para administrar productos y clientes.
Dificultad para rastrear inventarios y datos temporales de clientes.
Procesos manuales que generan errores y pérdida de tiempo.

# Solución
Un sistema basado en Jakarta EE 10 que:

Ofrece funcionalidades de gestión de productos y clientes.
Usa cookies para manejar información temporal.
Mejora la experiencia del usuario final con un diseño basado en MVC.

# Arquitectura
El sistema sigue una arquitectura MVC (Modelo-Vista-Controlador):

Modelo: Define la lógica de negocio y los datos.
Vista: Proporciona la interfaz gráfica para usuarios.
Controlador: Conecta la vista y el modelo, manejando las solicitudes del usuario.

# Tabla de Contenidos

1.-Requerimientos
2.- Instalación
3.- Configuración
4.- Uso
  a.- Guía para el Usuario Final
  b.- Guía para el Usuario Administrador
4.- Contribución
5.- Roadmap
6.-Producto

# Requerimientos

  # Servidores
Servidor de Aplicaciones: GlassFish Server 6.x o superior.

# Paquetes Adicionales
Jakarta EE 10: Framework para aplicaciones web.
Maven: Gestión de dependencias y construcción del proyecto.

# Versión de Java
JDK 11 o superior.
# Instalación
  # ¿Cómo instalar el ambiente de desarrollo?
    Clona el repositorio:
        git clone https://github.com/alejandrohdzlop/Tienda_Lupita.git

# Importa el proyecto en NetBeans.

  # Instala dependencias con Maven:

        mvn install
# ¿Cómo ejecutar pruebas manualmente?
    Ejecuta el proyecto desde NetBeans.
      Accede a la aplicación desde el navegador en http://localhost:8080/Tienda_Lupita.

# ¿Cómo implementar en producción?
    Ambiente Local
      Genera un archivo .war desde NetBeans.
        Despliega el archivo en el servidor GlassFish.
      Nube (Heroku)
        Crea un contenedor Docker con GlassFish.
          Sube la imagen a Heroku usando su CLI.


# Configuración

    # Archivos de Configuración
        web.xml: Configuración de servlets y mapeos.
        cookies.properties: Configura tiempos de expiración y rutas.


# Configuración de Requerimientos

# Ajusta las variables de entorno:
  APP_PORT para definir el puerto de despliegue.
    COOKIE_EXPIRATION para el tiempo de vida de las cookies.


# Uso
  # Guía para el Usuario Final

      1.- Inicia sesión en el sistema.
      2.- Gestiona productos y clientes desde el menú principal.
      3.- Visualiza los datos temporales almacenados con cookies.
  # Guía para el Usuario Administrador
      1.- Accede a la configuración desde el panel de administración.
      2- Ajusta parámetros como expiración de cookies y configuración del servidor.

# Contribución
Guía de Contribución

Clona el repositorio:
git clone https://github.com/alejandrohdzlop/Tienda_Lupita.git

Crea un branch:
git checkout -b feature/nueva-funcionalidad

Realiza cambios y haz un commit:
git add .
git commit -m "Descripción del cambio"

Haz push al branch:
git push origin feature/nueva-funcionalidad

Crea un pull request desde GitHub.


# Roadmap
  # Funcionalidades Futuras
    1.- Reportes: Generar reportes en PDF para ventas y productos.
    2.- Gestión Avanzada de Clientes: Integrar datos más completos.
    3.- Persistencia con Base de Datos: Migrar datos temporales a una base de datos relacional.



# Producto
Este sistema está diseñado para ser una herramienta flexible y escalable que mejore las operaciones de pequeñas empresas. La primera versión incluye funcionalidades esenciales como la gestión de productos y clientes, mientras que futuras iteraciones introducirán características avanzadas.
