# Triggers

## BASE DE DATOS:
  ![Error al cargar la imagen](https://github.com/lauracahe/Triggers/blob/main/imagenes/Show_Databases.png)

### Trigger 1:
  **Procedimiento:** crear_email que devuelva una dirección de **correo electrónico** con el siguiente formato:
    - Un conjunto de caracteres del **nombre** y/o apellidos
    - El carácter **@**.
    - El **dominio** pasado como parámetro.
  Una vez creada la tabla escriba un **trigger** con las siguientes características:
    - Trigger: trigger_crear_email_before_insert
    - Se ejecuta sobre la tabla clientes.
    - Se ejecuta antes de una operación de inserción.
    - Si el nuevo valor del email que se quiere insertar es NULL, entonces se le creará automáticamente una dirección de email y se insertará en la tabla.
    - Si el nuevo valor del email no es NULL se guardará en la tabla el valor del email.

  ![Error al cargar la imagen](https://github.com/lauracahe/Triggers/blob/main/imagenes/trigger1.png)

### Trigger 2:
  Crear un trigger que permita verificar que las personas en el Municipio del catastro **no pueden vivir en dos viviendas diferentes**.

  ![Error al cargar la imagen](https://github.com/lauracahe/Triggers/blob/main/imagenes/trigger2.png)

### Trigger 3:
  Crear trigger que permita mantener actualizado el **stock** de la base de dato de viveros.

 ![Error al cargar la imagen](https://github.com/lauracahe/Triggers/blob/main/imagenes/trigger3.png)




