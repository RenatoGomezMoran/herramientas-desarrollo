# herramientas-desarrollo

# NEXORA

### Plataforma de Gestión Comercial y Operativa

NEXORA es una aplicación web para gestionar las principales operaciones comerciales de una empresa, como clientes, productos, ventas e inventario.

El proyecto tiene como objetivo aplicar el uso de **Git y GitHub** para el desarrollo colaborativo, utilizando ramas, commits, Pull Requests, merge y resolución de conflictos.

## Funcionalidades

* Gestión de usuarios y roles.
* Gestión de clientes.
* Gestión de productos.
* Gestión de ventas.
* Control de inventario.
* Dashboard con indicadores básicos.

## Requerimientos funcionales

* **RF01:** El sistema debe permitir iniciar sesión.
* **RF02:** El administrador debe poder gestionar usuarios y roles.
* **RF03:** El sistema debe permitir registrar, editar, eliminar y consultar clientes.
* **RF04:** El sistema debe permitir registrar, editar, eliminar y consultar productos.
* **RF05:** Cada producto debe manejar precio y stock.
* **RF06:** El sistema debe permitir registrar ventas asociadas a un cliente.
* **RF07:** Una venta debe permitir agregar uno o más productos y cantidades.
* **RF08:** El sistema debe calcular automáticamente el total de una venta.
* **RF09:** Al registrar una venta, el stock del producto debe actualizarse.
* **RF10:** El sistema debe permitir consultar el historial de ventas.
* **RF11:** El sistema debe permitir consultar los movimientos de inventario.
* **RF12:** El dashboard debe mostrar información resumida de ventas, productos y clientes.

## Requerimientos no funcionales

* **RNF01:** La aplicación debe contar con autenticación de usuarios.
* **RNF02:** El sistema debe controlar el acceso según el rol del usuario.
* **RNF03:** La información debe almacenarse en una base de datos.
* **RNF04:** La aplicación debe tener una interfaz web responsive.
* **RNF05:** El código fuente debe gestionarse mediante Git y GitHub.
* **RNF06:** Cada funcionalidad debe desarrollarse mediante ramas independientes.
* **RNF07:** La integración de cambios debe realizarse mediante Pull Requests.
* **RNF08:** El proyecto debe mantener una estructura organizada y documentada.

## Tecnologías

* React
* Node.js / Express
* PostgreSQL
* Git
* GitHub

## Flujo Git

```text
Issue → Branch → Commit → Push → Pull Request → Review → Merge
```

### Ramas

```text
main
└── develop
    ├── feature/auth
    ├── feature/clientes
    ├── feature/productos
    ├── feature/ventas
    └── feature/inventario
```

## Objetivo del proyecto

Desarrollar una solución funcional de gestión comercial y demostrar buenas prácticas de control de versiones y trabajo colaborativo utilizando Git y GitHub.

**Estado:** En desarrollo.
