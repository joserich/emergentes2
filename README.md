# Sistemas empresariales
## ¿Que es un sistema empresarial?
- Es un sistema que tiene un impacto muy importante en el funcionamiento de  la organización o negocio y cuya falla traería graves consecuencias. 
- Normalmente que ofrece alta calidad de servicio, gestiona con grandes  volúmenes de datos, disponible de forma continua y es capaz de soportar  cualquier organización grande.
- En el desarrollo de aplicaciones de misión crítica se consideran**
 >* Plataforma tecnológica
 >* Alta disponibilidad
 >* Escalabilidad
 >* Seguridad
 >* Mantenimiento
 
## Caracteristicas mas importantes de una aplicación empresarial
* Acceso a bases de datos, usualmente a bases de datos relacionales.
* Operaciones transaccionales, cumple con las propiedades ACID
* Escalables, permiten escalabilidad vertical y horizontal
* Disponibles, idealmente prestan servicios de forma continua
* Seguras, no todos los usuarios acceden con la misma, funcionalidad
* Permiten integración con otras tecnologías
* Arquitectura multicapa

## Instituciones que requerirían aplicaciones de misión crítica. 
 **Las instituciones que requeririan las aplicaciones de misión critica son:**
 * **Unidades Educativas**, Para almacenar datos de tanto de estudiantes como usuarios externos y proveer informacion sobre avance academico para cada usuario. Tambien necesita almacenar material digital academico segun a cada grado.
 * **Bancos electronicos**, necesitan la mayor disponilidad, escalibilidad, y seguridad de la informacion e informatica.
  * **Universidades(Repositorio)**, Las universidades necesitan almacenar y procesar gran cantidad de informacion digital sobre investigacion     y produccion academica.
 * **Brockers(Plataformas de venta y compra de divisas)**, Estos sistemas necesitan estar en linea las 24 horas y ser escalables a nivel de operaciones transaccionales(compra/venta) de divisas y criptomonedas.
  * **Institutos**, Necesitan generar estadisticas y prover informacion necesaria para que personas con ganas de superarse se registren y usen el sistema.
   

## Diferencias entre la escalabilidad horizontal y escalabilidad vertical

La escalabilidad vertical o hacia arriba, este es el más simple, pues significa crecer el hardware de uno de los nodos, es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. pero también puede ser la migración completa del hardware por uno más potente. El esfuerzo de este crecimiento es mínimo, pues no tiene repercusiones en el software, ya que solo será respaldar y migrar los sistemas al nuevo hardware.

![Escalabilidad Horizontal](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-horizontal.png)

El escalamiento horizontal es sin duda el más potente, pero también el más complicado. Este modelo implica tener varios servidores (conocidos como Nodos) trabajando como un todo. Se crea una red de servidores conocida como Cluster, con la finalidad de repartirse el trabajo entre todos nodos del cluster, cuando el performance del cluster se ve afectada con el incremento de usuarios, se añaden nuevos nodos al cluster, de esta forma a medida que es requeridos, más y más nodos son agregados al cluster.
Debemos entender que cada uno ofrece ventajas y desventajas y no existe uno mejor que otro; pero si existen escenarios donde uno puede funcionar mejor que el otro. Lo ideal sería hacer un análisis para cada escenario y determinar el mejor.

![Escalabilidad Horizontal](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-vertical.png)

## Servidor
- Un servidor es una computadora que formando parte de una red provee servicios a otras computadoras denominadas clientes.
- Algunos servidores comunes son impresion correo fax telefonia **web**¨base de datos **aplicaciones** etc.

## Que es un servidor Web y que es un servidor de aplicaciones
Un servidor web programa informático que procesa una aplicación del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente.

- Un servidor de aplicaciones es un dispositivo de software que proporcionan servicios 
de aplicación a las computadoras cliente.
- Un servidor de aplicaciones generalmente gestiona la mayor
parte (o la totalidad) de las funciones de la lógica de negocio y acceso a los datos de 
la aplicación.
- Los beneficios de la aplicación de la tecnología de servidores
de aplicación son la centralización y al disminución de la
complejidad en el desarrollo de aplicaciones

## Protocolo HTTP
HTTP, de sus siglas en inglés: "Hypertext Transfer Protocol", es el nombre de un protocolo el cual nos permite realizar una petición de datos y recursos, como pueden ser documentos HTML. Es la base de cualquier intercambio de datos en la Web, y un protocolo de estructura cliente-servidor, esto quiere decir que una petición de datos es iniciada por el elemento que recibirá los datos (el cliente), normalmente un navegador Web. Así, una página web completa resulta de la unión de distintos sub-documentos recibidos, como, por ejemplo: un documento que especifique el estilo de maquetación de la página web (CSS), el texto, las imágenes, vídeos, scripts, etc... 
![Grafico protocolo HTTP](http://2.bp.blogspot.com/_jUCZth_DkjU/TID-jK9rWcI/AAAAAAAAAAQ/3JNIssF_KeQ/s1600/protocolo.png)

Clientes y servidores se comunican intercambiando mensajes individuales (en contraposición a las comunicaciones que utilizan flujos continuos de datos). Los mensajes que envía el cliente, normalmente un navegador Web, se llaman peticiones, y los mensajes enviados por el servidor se llaman respuestas.

## Explique los elementos importantes de REQUEST en HTTP

El comando HTTP Request permite enviar todo tipo de petición HTTP a un URL específico y procesar la respuesta del servidor HTTP.

Aunque hay varios métodos de HTTP para recuperar datos de un servidor, las dos más utilizados son GET y POST.

El método GET solicita un recurso del servidor indicado en el campo URI. Si la URI apunta a una base de datos de producción de recursos como un servlet, los datos serán devueltos dentro del mensaje de respuesta. 

## Explique los elementos importantes de RESPONSE en HTTP

Una vez que el servidor ha recibido y procesado la solicitud, éste debe devolver un mensaje de respuesta HTTP hacia el cliente. El mensaje de respuesta se compone de una línea de estado y cero o más campos de cabecera, seguido por una línea vacía. También puede tener opcionalmente un cuerpo del mensaje.

La primera línea del mensaje de respuesta HTTP que se conoce como la línea de estado. Se compone de HTTP versión del protocolo que se ajusta a la respuesta, seguida por un código numérico y su estatuto de texto explicación.

## Java EE(Enterprice Edititión)

Es una plataforma de programación para desarrollar y ejecutar software de aplicaciones en Lenguaje de programación Java con arquitectura de n-niveles distribuida, basándose ampliamente en componentes de software modulares ejecutándose sobre un servidor de aplicaciones. 

![Grafico Java EE](https://picodotdev.github.io/blog-bitix/2016/03/introduccion-y-nuevas-caracteristicas-de-java-ee-7/images/aplicaciones-multicapa-javaee.png)

Java EE incluye varias especificaciones de API, tales como JDBC, RMI, e-mail, JMS, Servicios Web, XML, etc., y define como coordinarlos. Java EE también establece algunas especificaciones únicas para Java EE de algunos componentes.
Estas incluyen Enterprise JavaBeans, Servlets, JavaServer Pages y varias tecnologías de servicios web. Esto permite al desarrollador crear una aplicación de Empresa que sea portable entre plataformas y escalable. Otros beneficios añadidos son, por ejemplo, que el servidor de aplicaciones puede manejar las transacciones, seguridad, escalabilidad, concurrencia y gestión de los componentes que son desplegados, significando que los desarrolladores pueden concentrarse más en la lógica de negocio de los componentes en lugar de las
tareas de mantenimiento de bajo nivel. 


## Contenedores, componentes y servicios de Java EE

Un contenedor es un entorno de ejecución que provee al componente una serie de servicios.

Java EE Server: La porción de tiempo de ejecución de un producto
Java EE. provee los contenedores web y de ejb.
Contenedor EJB: Maneja la ejecución de los enterprise beans.
Contenedor Web: Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE. Contenedor de aplicación cliente: Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.
Contenedor Applet: Maneja la ejecución de applets, no necesita servidor de aplicaciones,consiste en un browser y el plugin web de java.

Un componente es una unidad de software que forma parte de una aplicación

Java EE define los siguientes tipos de componentes:
* Componente cliente: Cliente AWT, Swing, Applet y navegador Web
* Componente web: Servlet, JSP y JSF
* Componente de negocio: EJB
* Cada tipo cubre necesidades concretas y se basan en APIs especificas 

**Java EE define los siguientes servicios:**

**De directorio:** para la indexación y búsqueda de
componentes y recursos
**De despliegue:** para poder personalizar los componentes y
recursos

**De transaccionalidad:** para poder ejecutar distintas acciones en una misma unidad transaccional

**De seguridad:** para poder autenticar y autorizar a los
usuarios de la aplicación

**De acceso a datos:** para facilitar el acceso a Bases de Datos
Servicios Java EE

**De conectividad:** para poder acceder fácilmente a distintos EIS

**De mensajería:** para poder comunicarse con otros componentes, aplicaciones o EIS

Para que un entorno de ejecución pueda decir que es Java EE debe implementar y soportar:
  * Todos los tipos de componentes
  * Todos los tipos de contenedores
  * Todos los servicios


## Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse
Un servlet es una clase Javaque hereda de la clase HttpServlet. Los cinco métodos más
    comunes de un servlet son:
    
    public void init()throws ServletException{
    }
    
    public void service(HttpServletRequest request,
          HttpServletResponse response)
          throws ServletException, IOException {
    public void doPost (HttpServletRequest request,
          HttpServletResponse response)
          throws ServletException, IOException {
    public void doGet (HttpServletRequest request,
          HttpServletResponse response)
          throws ServletException, IOException {
          }
    public void destroy(){
    };

