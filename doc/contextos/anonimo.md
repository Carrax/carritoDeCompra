## Anónimo

Cómo anónimo podré:

+ Navegar por los productos aplicando diferentes filtros
+ Agregar una cantidad *X* de un determinado producto al carrito
+ Eliminar productos del carrito
+ Registrarse cómo cliente
+ Registrarse a la vez que procesa la compra

---
### Registro cómo cliente
Como **Anónimo**  quiero **poder registrarme**  para poder **acceder al sistema con todas las ventajas de los clientes**.

---
### Navegar por la tienda
Como **Anónimo**  quiero **navegar por los producto aplicando filtros**  para poder **Poder acceder al producto que quiero más facilmente**.

---
### Añadir al carrito
Como **Anónimo**  quiero **agregar al carrito más de un producto a la vez**  para poder **facilitarme la compra del mismo tipo de producto**.

---
### Eliminar productos del carrito
Como **Anónimo**  quiero **eliminar productos añadidos al carrito**  para poder **no tener que comprar algo que agregué al carrito**.

---
### Registrarse simultaneamente a la compra
Como **Anónimo**  quiero **comprar los productos añadidos al carrito, a la vez que me registro**  para poder **registrarme y comprar a la vez**.

---
---

## Criterios de aceptación

+ **Dado** que el usuario anónimo no está registrado en el sistema **cuando** intenta acceder a alguna funcionalidad que requiere previlegios **entonces** informarle de que no puede acceder por falta de privilegios y redirigirle a la página de registro.
+ **Dado** que el usuario anónimo no puede procesar la compra **cuando** vaya a finalizar el proceso de compra **entonces** requerirle el registro cómo cliente.
+ **Dado** que el usuario ha introduzido algún dato incorrecto **cuando** intenta logearse en el sistema **entonce** informarle de que algún dato es incorrecto y ofrecerle la oportunidad de volvera intentarlo o de recuperar la contraseña.
