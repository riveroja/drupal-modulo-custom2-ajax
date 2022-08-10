# drupal-modulo-custom2-ajax
## Módulo custom para formulario en Drupal 7.X , con AJAX

INSTALACIÓN
-----------

Los archivos deben copiarse en una instalación de Drupal 7.X en el directorio:

> {SERVER-DRUPAL}/sites/all/modules/custom/nombremodulo

Luego deberá habilitarse el módulo desde los settings del admin.

Para que sea visible, de deberá crear una página básica desde:

> Content - Add content - Basic page

- Agregar un titulo y cualquier contenido. Guardar los cambios.
- Se genera una URL para referenciar a la página creada, por ejemplo:
> {SERVER-DRUPAL}/node/2
- Habilitar el bloque definido en mimodulo.module, para ellos:
> Ir a Structure - Blocks
- Buscar el bloque por su nombre, y seleccionar desde el desplegable Content, en Configure:
> En la sección Show block on specific page, sleccionar Only the listed pages e indicar que deberá verse úncamente en node/2
-Guardar el bloque


El formulario se visualiza ingresando a {SERVER-DRUPAL}/node/2.


