# Supermercado

## Ángel Pérez Gutiérrez

### Descripción del Proyecto

Este proyecto tiene como objetivo la creación de una página web para un supermercado utilizando PHP. La plataforma permitirá a los usuarios navegar por una variedad de productos, gestionar sus pedidos y acceder a su perfil personal.

### Estructura del Proyecto

La página se desarrollará siguiendo el siguiente procedimiento:

1. **Sesión de Inicio y Registro**: Los usuarios podrán crear una cuenta y acceder a su perfil.
2. **Página Principal (Index)**: Servirá como menú principal y mostrará las siguientes secciones:
   - Listado de productos
   - Listado de categorías
   - Listado de proveedores
   - Listado de pedidos
   - Listado de mejores ventas
3. **Perfil del Usuario**: Los usuarios podrán ver y editar su información personal.
4. **Gestión de Pedidos**: Sección donde los usuarios podrán consultar:
   - Pedidos realizados
   - Pedidos entregados
   - Pedidos pendientes

### Ejemplo de Código

A continuación se presentan ejemplos de código que se utilizarán en el desarrollo de la aplicación:

```php
// Se iniciará la sesion
session_start();
if (isset($_SESSION['usuario'])) {
    // Código para mostrar el perfil del usuario
} else {
    // Redirigir al usuario a la página de inicio de sesión sino ha iniciado sesion 
}
```

### Instalación

Para poder visualizar en linux la pagina del proyecto, se utilizará el siguiente comando:

```bash
sudo /opt/lampp/lampp start
```

### Menú de Productos

El menú de productos en venta se presentará de la siguiente manera:

| Productos en venta   |      Descripción      |  Precio  |
|----------------------|:---------------------:|---------:|
| Patatas              |  Producto fresco      | $1600    |
| Pizza                |    Pizza clásica      | $12      |
| Hamburguesa          | Hamburguesa gourmet   | $1       |

### Documentación del proyecto

Para más información sobre los componentes del programa, puedes consultar el siguiente enlace: [Supermercado en php](https://github.com/Zer0shiroo/Proyecto-Supermercado-DAW)


**Ejemplo de como quedaria la pagina:**

![Diagrama de flujo del sistema](https://res.cloudinary.com/admitad-gmbh/image/upload/v1721554389/15b914ec4b9ea359566076dc196e99ec.png)
