# Proyecto del Curso Integrador 1
Título: Desarrollo de un Prototipo de Sistema Web para la Gestión de Inventario de una Empresa de Muebles en el Distrito de Villa el Salvador, Lima – 2024

## Descripción del Proyecto
Este proyecto es el resultado del trabajo realizado en el **Curso Integrador 1**. Su propósito es aplicar los conocimientos adquiridos en las áreas de desarrollo de software, diseño de sistemas, y gestión de proyectos para crear una solución práctica a un problema real.

### Objetivo
El objetivo principal del proyecto es el desarrollo de un prototipo de sistema web que permita gestionar el inventario de una empresa de muebles ubicada en el distrito de Villa el Salvador, Lima. Este sistema web brindará funcionalidades como el registro y la actualización de inventario, mejorando la eficiencia operativa. Además contara con una tienda en línea intuitiva y actualizada, donde los clientes podrán realizar sus compras de forma rápida y segura 

## Características
  - Gestión de usuarios (registro, inicio de sesión, roles).
  - Módulo de formularios dinámicos.
  - Interfaz amigable y responsiva.
  - Conexión a una base de datos para almacenamiento persistente.

## Requisitos del Sistema
- **Lenguaje:** Java (versión 11 o superior)
- **Framework CSS:** BootStrap 5
- **Base de Datos:** MySQL
- **IDE recomendado:** NetBeans
- **Herramientas adicionales:** Maven o Ant

## Estructura del Proyecto
ProyectoMuebleriaLucia/

├── **Web Pages**/

│   ├── Carrito.jsp

│   ├── Cliente.jsp

│   ├── Compras.jsp

│   ├── Dashboard.jsp

│   ├── Empleado.jsp

│   ├── Entradas.jsp

│   ├── LoginCliente.jsp

│   ├── NecesitaIniciarSesion.jsp

│   ├── OrdenCompra.jsp

│   ├── Producto.jsp

│   ├── Proveedor.jsp

│   ├── RegistroError.jsp

│   ├── RegistroExitoso.jsp

│   ├── Salidas.jsp

│   ├── index.jsp

│   ├── loginadmin.jsp

│   ├── paneladmin.jsp

│   ├── ventaerror.jsp

│   └── ventaexitosa.jsp

├── *Source Packages*/

│   ├── **Conexion**/

│   │   ├── ConexionBD.java

│   │   ├── Fecha.java

│   │   └── GenerarSerie.java

│   ├── **Controladores**/

│   │   ├── Controlador.java

│   │   ├── ControladorCarrito01.java

│   │   ├── ListarOrdenes.java

│   │   ├── ListarPedidos.java

│   │   ├── PedidosPorCliente.java

│   │   ├── ValidarLoginCliente.java

│   │   └── Validarlogin.java

│   └── **Modelos**/

│       ├── Carrito.java

│       ├── Cliente.java

│       ├── ClienteDAO.java

│       ├── Empleado.java

│       ├── EmpleadoDAO.java

│       ├── OrdenCompra.java

│       ├── OrdenCompraDAO.java

│       ├── OrdenPedido.java

│       ├── Pago.java

│       ├── PedidoDAO.java

│       ├── PedidoVentaDAO.java

│       ├── Producto.java

│       ├── ProductoDAO.java

│       ├── Proveedor.java

│       └── ProveedorDAO.java
