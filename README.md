# Actividad-3
Taller de Productividad Basada en Herramientas Tecnológicas

Descripcion

Es una harramienta desarrollada en lenguaje java para realizar el inventario de los productos que se encuentran en stock y poder realizar las facturas de las comprar registradas por el cliente. Nos permite poder realizar las compras, registrar a los clientes, provedores y la actualizacion de nueva mercancia.

Problema Identificado

Se realizo el analisis del negocio de zapateria, el detalle que se detecto es que no cuentan con un control de inventario automatizado al momento de realizar una compra por el cliente. El dueño debe de realizar el inventario de manera manual.
Otros de los problemas identificados es que no cuentan con sistema de facturacion, han tenido problemas con este punto debido a que ha habido microempresas que le han hecho pedidos en volumen, pero una de las condiciones de la compra es que todo debe de ser facturado por el mismo negocio, por lo tanto no cuentan con este sistema.

Solucion

Se creo esta herramienta, para poder tener un control de inventario mediante el sistema, de esta manera podra tener un mejor control en el stick.Tambien se implemento dentro del sistema, un modulo para poder realizar la actualizacion del la nueva mercancia o en su caso poder eliminar la mercancia que ya no esta en venta.
Otras de las soluciones implementadas, es que podemos registrar al cliente en el sistema, para poder contar con sus datos y de esta forma podremos registrar las compras realizadas a su nombre para poder realizar una facutra de la mercancia comprada.
Cuenta con un registro de busqueda de mercancia para realizar la busqueda del producto mas rapida. Se creo un sistema de busqueda del cliente, de esta manera podremos identificar si el cliente ya a sido registrado o no duplicar los registros en la base de datos.
Debido a que el negocio se trae la mercancia desde provedores, pudimos implementar un sistema donde podra tener sus provedores registrados y tener un mejor control al momento de la administracion del negocio.

Arquitectura

Registro de clientes / Búsqueda de clientes / Registro de artículos / lista de artículos
Actualizar Stock artículos / Devoluciones / Realizar venta (facturar)
Consultas / Registro de proveedores / Lista de proveedores

Tabla de Contenidos

Facturacion
Source packages
Facturacion.java
IVA.java
interfaz_Clientes.java
interfaz_Proveedor.java
interfaz_actualizarstock.java
interfaz_articulo.java
interfaz_buscarclientes.java
interfaz_buscarproveedor.java
interfaz_devoluciones.java
interfaz_factura.java
interfaz_principal.java
Persona.java
Sentencias_sql.java
conexion.java
control_articulos.java
control_cliente.java
control_existencias.java
control_proveedor.java
interfaz_buscararticulos.java
interfaz_consultas.java
faxturacion.imagenes
0162iconos-clubzonanokia.com
ALUMNOS2.JPG
dibujosdezapatosparaimprimir.jpg
dinero_46x46.jpg
Libraries
mysql-connector-java5.1.5-bin.jar
jcalendar-1.3.3.jar
JDK 13 (Default)

Requerimientos

-Conexion de base de datos MYSQL facturas.sql
-mysql-connector-java-5.1.6-bin.jar
-jcalendar-1.3.3.jar
-JDK 8

Instalacion
-Descargar el software del repositorio
-La base de datos esta construida en el gestor de base de datos Mysql, el cual es muy estable y robusto, por tal motivo para su uso deben tener instalado el paquete XAMPP, el cual contiene un servidor apache y el gestor de base de datos ya mencionado.
-Instalacion del jdk 8.
-Instalacion de mysql.

-Se debe de configurar al echivo de facturas.sql en el conector de base de datos mysql para poder realizar la ejecucion y pruebas del programa.

-El ambiente local, se tiene que ejcutar el .jar para que ejecute la interfaz del programa, ya con el .sql instalado, nos va a permitir ejecutrar las funciones del software.

Configuracion

Instalamos la version mas actual de java ya que sin ella no pdoremos correr el software
Configuracion del ambiente JAVA
Obtenemos la plantilla de excele para que podamos pasar la informacion que necesitamos
configuramos nuestta base de datos en la plantlla de excel del software y la cargamos

Uso

El software realizar todo el proceso de facturación e inventario en un almacén, el sistema permite realizar los siguientes procesos de registro:
Registro de clientes
Registro de artículos
Registro de proveedores
Ademas se deben listar listar los respectivos procesos construidos anteriormente.
El sistema actualiza el stock o las existencias de los artículos, a lo que llamaremos inventario, esto con el fin de mantener el proceso de facturación acorde a los articulos existentes en bodega.

El usuario administrado, tendra una cuenta diferete con al cual tendra acceso a poder hacer modificaciones y todos los cambios necesarios.

Contribucion

Abrimos el repositorio
Link del repositorio (https://github.com/dioneilucio/Actividad-3)
En el branch "master" podemos encontrar la version mas actual del software y la mas completa y estable
Del lado derecho tenemos la opcion de clone or download
Tenemos dos opciones a elegir (abrir en el equipo o descargar como zip)
Cualquiera de las 2 opciones nos puede servir

Roadmap

Los requerimientos planeados en una futura version del software es poder crear un proceso donde corran los intereses en las ventas que se esta realizando en el negocio.
Poder contar un qr que nos arroje el producto y asi mismo agilizar la compra.
Conforme vaya creciendo el negocio, se iran implementando modificaciones a medida del cliente.
