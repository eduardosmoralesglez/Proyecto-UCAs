# Especificación de Actores y Operaciones

## Actores.

- Usuario General:
  - Usuario normal de la red, puede crear y modificar su perfil, realizar pedidos y entregar carga para enviar.
- Usuario de las UCAs:
  - Usuarios principales de la red, puden hacer todo lo de los usuarios generales y ademas, puden realizar pedidos prioritarios, entregar carga prioritaria para envio y tienen acceso a las impresoras quirales.
- Portadores:
  - Usuarios encargadas de realizar las entregas de los usuarios generales, pueden acceder a todos las solicitudes generales.
- Usuarios Qpido:
  - Usuarios que administra la red, pueden añadir, promocionar o eliminar usuarios, ademas son los encargados de las entregas prioritarias de los usuarios UCA.

## Operaciones por Actor

### Usuario General
- Crear perfil: Para acceder a la red tiene que crear un perfil de usuario.
- Modificar perfil: El usuario puede modificar su perfil.
- Realizar pedido: Solicitar a un portador la entrega de un pedido.
- Entregar carga: Solicitar a un portador para que recoja una carga.

### Usuario de las UCAs
- Crear perfil: Para acceder a la red tiene que crear un perfil de usuario.
- Modificar perfil: El usuario puede modificar su perfil.
- Realizar pedido: Solicitar a un portador la entrega de un pedido.
- Entregar carga: Solicitar a un portador para que recoja una carga.
- Realizar pedido prioritaria: Solicita a un portador Qpido para la entrega de un pedido prioritario.
- Entregar carga prioritaria: Solicita a un portador Qpido para la recogida de una carga prioritaria.
- Utilizar impresoras Q: El usuario puede acceder a las impresoras quirales.

### Portadores
- Crear perfil: Para acceder a la red tiene que crear un perfil de usuario.
- Modificar perfil: El usuario puede modificar su perfil.
- Ver pedidos: El usuario puede ver todos los pedidos activos.
- Ver recogidas: El usuario puede ver todas las recogidad activas.

### Usuarios Qpido
- Crear perfil: Para acceder a la red tiene que crear un perfil de usuario.
- Modificar perfil: El usuario puede modificar su perfil.
- Utilizar impresoras quirales: El usuario puede acceder a las impresoras quirales.
- Ver pedidos prioritarios: El usuario puede ver todos los pedidos prioritarios activos.
- Ver recogidas prioritarias: El usuario puede ver todas las recogidad prioritarias activas.
- Añadir usuario: Crear usuarios nuevos para la red.
- Promocionar usuario: Promocionar un usuario general a usuario UCAs
- Eliminar usuario: Eliminar o degradar a un usuario de la red.
