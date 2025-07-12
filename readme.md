# Bases de datos
Un sistema gestor de base de datos (SGBD), es un software que gestiona una o más bases de datos y nos permite explotar la información almacenada en ellas de una forma relativamente simple.

Ejemplos de SGBD: Oracle, MySql, Sqlite, MS Sql server, Postgress, Sqlite

## Estructura 
- Tabla
- Registro
- Campo

Ejemplos de tablas

## DDL, DML, DCL

El lenguaje de definición de datos (DDL) describe la parte de SQL que crea, altera y suprime objetos de base de datos. Estos objetos de base de datos incluyen esquemas, tablas, vistas, secuencias, catálogos, índices, variables, máscaras, permisos y alias.

El lenguaje de manipulación de datos (DML) describe la parte de SQL que manipula o controla los datos.

Como administrador de seguridad de la base de datos, utiliza los comandos SQL del lenguaje de control de datos (DCL) para controlar el acceso de usuario a los objetos de base de datos y a su contenido.
La seguridad comienza con el usuario administrativo. Como usuario administrativo, debe crear y autorizar a otros usuarios. Cuando crea usuarios por primera vez, no pueden ver o hacer nada. Cuando otorga a los usuarios más privilegios, ellos pueden acceder a más objetos de base de datos.

Cuando crea usuarios, de forma predeterminada, ellos solo tienen acceso a las vistas del sistema. Con estas vistas, ellos pueden recuperar listas de objetos de base de datos de usuario y seleccionar datos dentro de esos objetos. Como la seguridad también se compila en estas vistas de sistema, la lista de objetos de base de datos que puede ver un usuario depende de los privilegios de seguridad del usuario

https://www.ibm.com/docs/es/i/7.5.0?topic=programming-data-definition-language
https://www.ibm.com/docs/es/i/7.5.0?topic=programming-data-manipulation-language
https://www.ibm.com/docs/es/psfa/7.1.0?topic=categories-data-control-language

# Definicion de tipo de datos
Ejemplo de tablas de bases de datos
Como se puede apreciar en las imagenes anteriores, cada tabla en las columnas coinciden con un tipo de dato: texto, numeros, fechas

## Tipos de datos numéricos exactos

## Tipos de datos numéricos aproximados
## Tipos de datos carácter
## Booleanos
## Fecha y hora

(Ver MongoDb para ampliar el panorama)