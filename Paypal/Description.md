# Hemos llegado al final de este tremendo curso   

Pero aún nos queda la parte más interesante, un proyecto completo donde poner en práctica todo lo visto a lo largo de estas 5 horas de contenido. 

Queremos que pongas en práctica los tres tipo de diseño vistos: teórico, lógica y conceptual. 

Realiza los tres diseños basándonos en el siguiente caso:

>[!NOTE]
>Queremos hacer una ampliación similar a PayPal donde los usuarios dispongan de cuentas con saldo y puedan hacer transferencias a otros usuarios. Los usuarios se registrarán mediante correo y contraseña, aunque almacenaremos también su nombre completo.
>
>Cada usuario podrá crear varias cuentas, que pueden ser normales o de empresa. Para cada cuenta, almacenamos su saldo actual en €, su nombre y una descripción proporcionada por el usuario.
>
>Si la cuenta es normal, no almacenamos más información asociada a ella. Sin embargo, si la cuenta es de empresa, almacenaremos el nombre de la empresa y su número de identificación fiscal o tax ID.
>
>De cada transferencia que ocurre entre las cuentas de los usuarios nos interesa almacenar la cantidad transferida, la fecha incluyendo hora y minuto y el estado de la transferencia, que puede ser "pagado" o "reembolsado".
>
>Del mismo modo, los usuarios podrán transferir dinero desde sus cuentas de la aplicación a sus cuenta bancarias, o recibir dinero desde su banco para aumentar el saldo en la app. Por lo tanto, el usuario podrá asociar varias cuentas bancarias a cada cuenta creada en la aplicación. De las cuentas bancarias queremos almacenar su número de cuenta.
>
>Para cada transferencia que ocurre entre un banco y nuestra app queremos saber la dirección en la que se ha transferido el dinero (si se ha hecho desde la app al banco o viceversa). Además, como las transferencia bancarias pueden tardar varios días queremos saber su estado ("procesando", "completada", "cancelada"), así como la fecha de emisión de la transferencia y la fecha de finalización (cuando se ha completado o cancelado).

___

Una vez los tengas:

>[!NOTE]
>Realiza el diseño lógico y conceptual. Exporta cada diseño  a una imagen o PDF.
>Realiza el diseño físico mediante un fichero SQL.
>
>Crea un nuevo fichero SQL con al menos 3 consultas, una básica y dos con agrupaciones.
>
>Almacena los cuatro archivos en un .zip y entrégalo en el apartado habilitado. 