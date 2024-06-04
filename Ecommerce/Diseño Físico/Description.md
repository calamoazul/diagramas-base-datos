# Descripción 

Queremos crear un Marketplace similar a Amazon donde los usuarios puedan crear tiendas y vender sus productos online. Los usuarios se registrarán con correo y contraseña y almacenaremos además su nombre completo.

De cada tienda queremos almacenar su nombre y el usuario al que pertenece, así como los productos que vende. Para cada producto almacenaremos su nombre, una descripción, el stock actual, el precio actual y el descuento actual. Además, es posible que algunos productos cuenten con distintos tamaños y colores (por ejemplo, un monitor puede estar disponible en distintas resoluciones y pulgadas), por lo tanto queremos permitir a los usuarios almacenar esta información. Finalmente, cada producto contará con al menos una imagen o varias. Los productos son únicos para cada tienda, es decir, aunque haya varias tiendas vendiendo el mismo producto, cada una de ellas tiene que crearlo por separado en la aplicación y añadir su nombre, imágenes, etc.

Los usuarios, además de vender, podrán comprar productos de otras tiendas. Para ello, tendrán que crear un pedido del cual almacenaremos los productos que incluye, la cantidad de cada producto, el color y tamaño de cada producto (si es el caso), el precio de cada producto (ya que puede cambiar en el futuro) y el descuento aplicado (también podrá cambiar en el futuro). Calcularemos también el precio total de la compra y añadiremos un número de factura para poder enviarlo al comprador más tarde.

Además, necesitamos saber a dónde enviar el paquete, de forma que los usuarios podrán asociar a su cuenta varias direcciones de envío y elegir una de ellas al crear un pedido. La dirección estará compuesta por los siguientes campos: país, provincia, ciudad, calle, número y, opcionalmente, unidad (número de apartamentos, puerta, etc). Esta dirección la almacenaremos junto con los otros campos del pedido. Por último, como el pedido puede tardar varios días en prepararse, enviarse y llegar a su destino, queremos almacenar su estado ("procesando", "enviado", "entregado", "cancelado").
___

Realiza el diseño físico teniendo en cuenta:

>[!NOTE]
>
>La correcta ejecución de las sentencias SQL
>Definición de tablas y campos con sus atributos
>Definición de las claves y relaciones entre tablas
>El entregable ÚNICAMENTE podrá ser mediante un fichero TXT o SQL.