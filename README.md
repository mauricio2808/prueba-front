# prueba-front
Prueba front-end para la empresa Accenture

Para la prueba front-End hay que clonar el proyecto y instalar los modulos.

se necesita importar las librerias: sweeralert, ngx-pagination, ng2-search-filter, jquery, angular forms, rxjs. (Los módulos los enviare comprimidos a los correos)

El poryecto es modular, ya que trabajé con diferentes con modulos para las paginas, para los servicios y para la carpeta shared.
Se trabajó con rutas hijas y ruta padre.

Se creó un archivo de configuración, el cual hace la conexión con la Appi. Posteriormente se creó un archivo de modelo, el cual nos indica el modelo que tiene el cliente.

Se creó un archivo de paginas, el cual tiene su propio archivo de rutas y archivo de módulos. 
Cabe resaltar que se creó la pagina de inicio, usuarios, registrar cliente y CAMBIAR TEMA (el usuario podrá cambiar el color del tema y será guardado en el localStorage)

Se creó la carpeta de servicios en los cuales se creó, cambiar tema serive, shared srvice (menú) y usuario service. Esta carpeta contiene su propio módulo.

Se creó la carpeta shared, en la cual está el sidebar y el header de la plantilla.El sidebar es dinamico, llama al servicio sidebar para mostrar los dos menús, Menú General y el Menú Mantenimientos.

El menú general direcciona a paginas de la empresa y tambien a que el usuario pueda cambiar el tema de la apicación, escogiendo diferentes opciones de la paleta de colores.
El menú de mantenimientos es en el cual podrá ir al inicio, ver los usuarios inscritos y registrr nuevo usuario.

Se trabajó con formularios reactivos con sus respectivas validaciones.

