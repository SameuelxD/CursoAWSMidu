# CursoAWSMidu

### ¿Que es el entorno CLOUD?
Es un servidor (computador) , que no es tuyo , su alojamiento fisico no te pertenece , es decir es un computador ajeno a ti , donde si se te autoriza y se te permite acceder a este servidor
podras controlar parte de su alojamiento virtual en la nube accediendo a sus servicios como servidor o computador , estos servicios facilitan para un dedarrollador o empresa a largo plazo su adquisicion prestada , pues al usuario de AWS no tendria que adquirir fisicamente todo el esquema de equipos necesarios para que su servicio en un servidor sea ejecutado.

### ¿Que es Amazon Web Services (AWS) ?
AWS Es precisamente aquel servidor que nos va a dar esas facilidades de controlar y manejar nuestros servicios en la web ,es decir si tengo una pagina nos permitira que esta pueda almacenar 
una base de datos , manejar procesamiento , latnecia , caracteristicas para registros,logueos,compras,ventas,almacenar imagenes estaticas,videos,contenido multimedia,gurdar infromacion de todo sentido , AWS ofrece servidores con estas capacidades pero con diferencias en sus caracteristicas para cada ususario pueda optimizar sus servicios alojados en AWS.

### Escalamiento Vertical y Escalamiento Horizontal.
Escalamiento en termiinos generales es la expansion de un servidor en sus caracteristicas para que este sea mas ascertivo en proveer sus servicios de alojamiento a un sitio estatico ,

# Escalamiento Vertical.
Es aquella adquisicion de mejores caracteristicas para el servidor como comprar un servidor con mayor procesamiento en hz , con msyor almacenamiento , con mayor ram , etc en general es contratar un servidor con mayores capacidades.

# Escalamiento Horizontal.
Es la adquisicion de mas servidores para que abrquen en mayor disponibilidad los servicios hospedados , es la compra de mas computadores para que entre estos se ayuden a aligerar el trabajo entre ellos.

Cda tipo de escalamiento tiene sus diferencias que los hacen mejor o peor en situaciones , por ejemplo el Escalamiento Vertical tiene un problema llamado downtime , que se refiere al tiempo que el servidor le toma adptarse y volver a la normalidad a proveer sus servicios , pues se actualiza sus capacidades el pierde la conexion total del alojamiento de sus servicios y funciones siendo ese tiempo bastante clave y primordial a diferencia que el Escalamiento Horizontal no tiene este problema , es importante recalcar tasmbien que el Escalamiento Vertical es mas sencillo de configurar en nuestro server y mas economico que el Escalamiento Horizontal pues este necesita que la carga de trabajo sea asignada manuelmente en cada servidor para que puedan ser optimo segun las caracteristicas del servidor siendo esto mas costoso.

### Servicios AWS
# EC2 (Elastic Cloud Computing).
Es un servicio para lanzar instancias o crear maquinas virtuales, con direcciones ip de alojamiento que sirven como dominio privados y publicos , servidores para alojar cualquier tipo de servicio como API's , Paginas Estaticas ,etc , es casi igual que AWS S3 , con la diferencia de que con AWS EC2 hay mas cobertura y poder no solo subir paginas web estaticas si  no hacer muchas mas cosas. Los EC2 son instancias.

# RDS (Relational DataBase Services).
Es una base de datos compatible con SQL , o lenguaje relacional de bases de datos , es decir su desarrolladora es AWS con un motor propio de AWS pero implementan la API de SQL para que este servicio pueda ser compatible con SQL , esta misma configuracion del servicio permite tambien alojar bases de datos como Aurora compatible con SQL y PostgreSQL , MYSQL , MariaDB , PostgreSQL , Oracle , etc. PlanetScale es un servicio que utiliza AWS , es un servicio que configura automaticamente los servicios que provee AWS , es un envoltorio que facilita el uso y la configuracion de todo lo que necesitamos en AWS


# Amazon Document DB.
Es una base de datos compatible con MongoDb , es un servicio creado y diseñado por AWS con MongoDb pero no es utilizable este servicio en MongoDb , es decir AWS Amazon Document DB si puede interactuar en su app con servicios provenientes de MongoDb pero viceversa MongoDb en su app no comparte sus servicios con AWS Amazon Document DB , es decir este servicio por medio de la API de MongoDb emula sus Bases de Datos sin ser reciproco MongoDb.

# Dynamo DB.
Base de datos propia de AWS , DB clave y valor , No es SQL , no es relacional , es una base de datos con recursos mas costosos que sus otros servicios Databases.

# Amazon MemoryDB for Redis.
Servicio de Bases de Datos compatible con Redis

# S3 (Simple Storage Service).
S3 es el mas simple pero a la vez es el mas usado , simple en cuestion de calidad precio que ofrece AWS , es decir pues su potencia,calidad de almacenar paginas web estaticas con su valor en costos es simple , de facil acceso y ergonomia en servicios y costos , hay que tener claro que estos servicios se almacenan un servidor donde la ubicacion de su alojamiento fisico es importante para la localizacion del cliente para el uso de sus servicios , pues la LATENCIA llega a ser mas alta si esta lejos o mas baja si esta cerca. Los S3 son buckets.

# AWS LAMBDA.
Es un servicio de computacion pero sin un servidor de alojamiento , permite ejecutar codigo sin necesidad de levantar una maquina , las Lambda ejecutan codigo y trabajan si lo necesitan automaticamente escalables permitiendo asi cualquier peticion en el servicio , tardan muy poco, su latencia permanece baja y el cobro del servicio es por el tiempo de computacion , las lambda son funciones
