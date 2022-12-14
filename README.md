# Proyecto Lenguaje de programaci贸n

## Centro de Veterinaria y Estadias "Care - Stays EGGTP" 馃惗馃樅馃彔
_Aplicaci贸n para veterinarias y estad铆a de mascotas donde existe el registro de mascotas, reservaci贸n de dos tipos tanto m茅dicas como de alojamiento, consultas de la informaci贸n registrada dentro de la aplicaci贸n, eliminaci贸n de citas y mascotas en caso de requerirlo, entre otros._

### Pre-requisitos 馃搵

_Adem谩s tener un dispositivo m贸vil configurado previamente en el cual se pueda compilar la aplicaci贸n, caso contrario se puede instalar un emulador para la ejecuci贸n de la aplicaci贸n._-

### Frontend 馃懆鈥嶐煉?
_Para empezar, instale Visual Studio y seleccione la opci贸n "Desarrollo para dispositivos m贸viles con .NET" en el programa de instalaci贸n._

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/requerimiento_frontend.png)

_Proceda a clonar el proyecto, luego de eso podr谩 observar los siguientes archivos accediendo a la carpeta "Proyecto\_LP/PRY\_LENG\_PROG"_

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/solucionVisualStudio.JPG)

_Una vez abierta la soluci贸n podr谩 visualizar el entorno de desarrollo de la siguiente manera_

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/VisualStudio.JPG)

_Para la visualizaci贸n del aplicativo ser谩 necesario ciertas configuraciones.\nDeber谩 tener activado el modo desarrollador, depuraci贸n usb, permitir la instalaci贸n de aplicaciones de terceros._
_Otra forma de probar el aplicativo es mediante un emulador que puede ser instalado en las mismas herramientas que provee Visual Studio_

_Dado que el proyecto se encuentra trabajando con Apis locales donde se conecta para realizar las debidas peticiones. Es necesario ejecutar el comando desde el simbolo del sistema de Adb de Android_
_Opcion que encontrar谩 c贸mo lo ve en la imagen_

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/adConsole.png)

_En la consola deber谩 ejecutar el comando para que pueda realizar la conexi贸n local con las peticiones para la visualizaci贸n de los datos en la aplicaci贸n._
```
adb reverse tcp:800 tcp:8000
```

_Una vez aplicado todo lo mencionado anteriormente, en la secci贸n superior podr谩 visualizar la siguiente opci贸n que le permitir谩 ejecutar el aplicativo ya sea desde su dispositivo m贸vil o emulador_

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/compilarProyecto.png)

### Base de datos: MySQL Workbench 馃梽
_Se est谩 utilizando la herramienta visual de dise帽o de bases de datos MySQL Workbench para el almaecenamiento y consulta de informaci贸n_

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/database.JPG)

### Backend 馃梽锔忊殭锔?
_Para empezar debe asegurarse que su m谩quina local tenga PHP y Composer instalados._
_Una vez instalado los requerimientos anteriores podr谩 visualizar los archivos de la siguiente manera_

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/backend.JPG)

_Existen migraciones que se han realizado, para ejecutarlas y carga la informaci贸n es necesario la ejecuci贸n del siguiente comando_
```
php artisan migrate:fresh --seed
```

_Dicho comando proceder谩 a migrar la informaci贸n a nuestra base de datos mencionada anteriormente c贸mo se ve en la imagen_

![requerimiento frontend](https://raw.githubusercontent.com/raochoa019/prueba-readme/main/recursos/migraciones.JPG)

_Finalmente para el levantamiento de los servicios desde el backend es necesario la ejecuci贸n del siguiente comando_

```
php artisan serve
```

## Autores 鉁掞笍
* **Bryan Alava Calderon**
* **Tommy Beltr谩n Borbor**
* **Robert Ochoa Ramos**
* **Aaron Villao Mero**