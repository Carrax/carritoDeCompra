# Carrito de Compra

 Proyecto para un carrito de compra. El proyecto se diseña pensando en que sea escalable y modular, se basa en un sistema de roles y permisos, dipone de las siguientes funcionalidades:

 + Registro y adminsitración de usuarios.
 + Creación y modificacion de productos.
 + Envío de correos masivos por usuarios y grupos de usuarios.
 + Carrito de compra y compra de productos.
 + Historial de compra.
 + Filtrado de productos por categoría.

###  [Contextos](doc/contextos.md)

 1. [Superadministrador](doc/contextos/superadministrador.md)
 -> Podrá realizar tareas de administración avanzada, cómo crear categorias, dar de alta administradores.
 2. [Administrador](doc/contextos/administrador.md)
-> Podrá realizar tareas de administración tanto de productos cómo de clientes.
 3. [Cliente](doc/contextos/cliente.md)
 -> Podrá agregar y eliminar productos en el carrito, administrar su cuenta. Porcesar la compra.
 4. [Anónimo](doc/contextos/anonimo.md)
 -> Podrá agregar y eliminar productos en el carrito y al procesar la comprá se le pedirá que se registre cómo cliente.

---
### [Entidades](doc/entidades.md)

Dispondrá, en un principio, de ocho entidades:

1. [usuario](doc/entidades/usuario.md)
2. [producto](doc/entidades/producto.md)
3. [producto-usuario](doc/entidades/producto-usuario.md)
4. [rol](doc/entidades/rol.md)
5. [menu](doc/entidades/menu.md)
6. [categoria](doc/entidades/categoria.md)
7. [grupo](doc/entidades/grupo.md)
8. [grupo-usuario](doc/entidades/grupo-usuario.md)
---
