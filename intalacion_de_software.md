# Docker
Docker en terminos generales es una maquina virtual recortada, que solo toma los elementos necesarios para funcionar. Estos contenedores o docker, se especializan en diferentes tareas, por ejemplo bases de datos, servidor de aplicaciones web, por mencionar algunos.

Descargue e instale docker de:

https://www.docker.com/

Seleccione su sistema operativo y arquitectura, para las practicas del curso se hara en Windows 11

Una vez que descargo e instalo Docker, le pedira que reinicie su equipo. Hagalo y cuando inicie su equipo aparacera una ventana de comandos, indicando que necesita installa el subsistema de Windows para Linux WSL, presione Enter para la instalación.
Espere un poco y despues saldra una ventana como la siguiente:
<img width="1087" alt="image" src="https://github.com/user-attachments/assets/3f7948b1-f0f3-4683-8d13-3e29c30e7b8e" />

Esto significa que su Docker esta listo, inicielo

## MariaDb
Dockerizaremos una instancia de MariaDB mediante docker

Inicie su Docker aparecera una ventana como la siguiente
<img width="1604" alt="image" src="https://github.com/user-attachments/assets/1819480d-e89c-4571-833d-e5fe4fe1d67b" />

Escriba en la textbox de Search: mariadb, como se muestra en la imagen
<img width="1607" alt="image" src="https://github.com/user-attachments/assets/eb5b457b-7016-4902-9b5f-8d24f3ad9f0a" />

De click en la primera opción, aparecera algo como esto
<img width="1614" alt="image" src="https://github.com/user-attachments/assets/49d90103-bdb1-41c1-9277-326af1f88be3" />

De click en el botón de Pull, esto descargara la imagen de mariadb
De una leida rápida a la documentación ahi encontrara más detalles, observara que la documentación menciona la configuración de variables de entorno, no se preocupe aqui haremos todo con la interfaz gráfica, pero ya se habrá dado cuenta que puedo hacerlo mediante scripts.
Ahora de click en Run, aparecera un formulario
<img width="1590" alt="image" src="https://github.com/user-attachments/assets/ca381662-fdcd-46fc-92b4-f44b4bc18e9b" />

De click en la flecha de combobox, para que vea las opciones
Llene el formulario conmo en la siguiente imagen
<img width="1614" alt="image" src="https://github.com/user-attachments/assets/e55cf681-9bf2-4e19-9407-2c305bdbe50e" />

Container name: mariadb

Host port: 3306 (Si ya tiene instado Mysql o MariaDb, elija otro puerto por ej el 3307 o proceda a bajar el servicio temporalmente)

MARIADB_ROOT_PASSWORD: 123456 (Por recomendacion la contraseña en ambiente de desarrollo debe ser facil de recordar)

De click en Run 

Es posible que aparezca un cuadro de dialogo, solictando permiso de acceso a red, de click en permitir.
Vaya a menu lateral y seleccione **Containers**, su base de datos ya debe de estar en linea.
<img width="1608" alt="image" src="https://github.com/user-attachments/assets/57b606e2-c4ff-4bab-bfe6-6836de54601c" />


# HeidiSql
Esta es una herramienta para la administración de la base de datos, la cual es libre, fácil y muy intuitiva.

Descarguela en https://www.heidisql.com/download.php

Descargue e instale, siga los pasos del wizard.

Inicie la app.

<img width="684" alt="image" src="https://github.com/user-attachments/assets/7ace9973-8bdf-471e-8228-8feb03cefe97" />

De click en el botón verde que dice Nueva, vera algo como lo siguiente
<img width="683" alt="image" src="https://github.com/user-attachments/assets/a2cf5051-989e-49de-a3ae-10a36f5071cd" />

Coloque el puerto que eligio en la sección de Docker/MariaDb, para este caso 3306 y la contraseña 123456, coloque un nombre a su conexión. de click en **Abrir**

Finalmente vera algo como esto, aqui vera que ya esta correctamente hecha sus instalaciones.

<img width="933" alt="image" src="https://github.com/user-attachments/assets/27b32a68-53cb-48e3-b9b9-62b1a566ed13" />

Felices Querys




