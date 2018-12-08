### Usuario


Atributo | Tipo | Descripción | Requerido | Único
-- | -- | -- | -- | --
id| INT |Identificador del usuario | Sí | Sí
nombre | VARCHAR(50) |Nombre del usuario | Sí | No
apellidos | VARCHAR(100) |Apellidos del usuario | Sí | No
dni-nif | VARCHAR(50) |DNI/NIF del usuario | Sí | Sí
email | VARCHAR(100) |Correo del usuario | Sí | Sí
pais | VARCHAR(50) |País del usuario| Sí | No
ciudad | VARCHAR(50) |Ciuadad del usuario| Sí | No
direccion_fisica | VARCHAR(150) |Dirección del usuario| Sí | No
numero_cuenta | VARCHAR(150) |Número de cuenta bancaria| Sí | No
codigo_postal | INT |Código postal del usuario| Sí | No
usuario | VARCHAR(50) |Usuario para el login | Sí | Sí
password | VARCHAR(150) |password encriptado | Sí | No
fecha_alta | TIMESTAMP |fecha de alta en el sistema | Sí | No
rol | VARCHAR(50) |Rol del usuario | Sí | Sí
