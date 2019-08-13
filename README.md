## <p align = "center"> Practica Nº1 </p>
## <p align = "center"> SISTEMAS EMPRESARIALES </p>
||||
|----------|-------------|-----------|
|Carrera:| Ingenieria De Sistemas|
|Materia:| Tecnologias Emergentes II|
|Apellidos y Nombres:|Valeriano Huanca Yhenny|
|C.I.:| 9231200 L.P.|
|Lugar y Fecha:| El Alto - 13/08/2019|
### 1)	Explique que son los sistemas empresariales 
Un Sistema Empresarial es un sistema que se encarga del funcionamiento de una organización u otro negocio. Gestiona datos, ofrece servicios, es capaz de soportar cualquier tipo de trabajo en grande.



### 2)	Describa cuales son las características más importantes de una aplicación empresarial
•	Acceso a bases de datos.
•	Operaciones transaccionales.
•	Escalables: Horizontal y vertical.
•	Disponibles: prestan servicios.
•	Seguras 
•	Permiten integración 
•	Arquitectura multicapa
###  3)	Investigue y proponga cinco instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta
### 4)	Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical
Escalabilidad horizontal puede aumentar componentes. 

 Escalabilidad vertical moderniza o actualiza los componentes que existen.
 ### 5)	Que es un servidor Web y que es un servidor de aplicaciones
  •	Un Servidor Web es una computadora que provee servicios a otras computadoras.

   •	Un Servidor de Aplicaciones es un dispositivo de software que proporciona servicios de aplicación a otras computadoras.
### 6)	Con un gráfico explique cómo funciona un protocolo HTTP
![IMAGEN](http://2.bp.blogspot.com/_jUCZth_DkjU/TID-jK9rWcI/AAAAAAAAAAQ/3JNIssF_KeQ/s1600/protocolo.png)
### 7)	Explique los elementos importantes de REQUEST en HTTP
El comando HTTP Request permite enviar todo tipo de petición  HTTP a un URL específico que contiene la información básica sobre la petición está formada de tres partes:

 El método indica el tipo de petición que se realiza .

 La ruta, parte de la dirección web que viene detrás del dominio.

 El protocolo, consta de HTTP y el número de versión de protocolo que se emplea
### 8)	Explique los elementos importantes de RESPONSE en HTTP
 Cada petición tiene su respuesta. Una respuesta del servidor consta de una línea de status que contiene alguna información básica sobre la respuesta del servidor. La línea de estado consta de dos partes: el protocolo y un código numérico. 
###  9)Describa con un gráfico la arquitectura Java EE
![imagen](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)
### 10)	Explique cuáles son los contenedores componentes y servicios de Java EE
CONTENEDORES.- Son espacios de ejecución que provee al componente todo tipo de servicio existen dos tipos de contenedores:

 •	Contenedor Web
 
 •	Contenedor de negocio(o de EJBs)

 COMPONENTES.-Es una unidad de software que forma parte de una aplicación tiene los siguientes tipos:
  
  •	Componente cliente
  
   •	Componente web
   
   •	Componente de negocio
   
### 11)	Investiga los métodos mas utilizados de las clases HttpServlet, HttpServletRequest  y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.
http Servlet Es la clase de la cual se debe extender para crear un servlet HTTP. De la clase se extiende los métodos los cuales son :

 •	doGet, procesa información que haya sido enviado con el método GET.
 
 •	poPost, implementa solo un método y el otro lo referencia.

httpServletRequest permite obtener información del cliente que depende del protocolo sus métodos son:

 •	getHeader(String name), permite obtener el valor de los headers de Http.
 
•	getCookies(), retorna un arreglo que contiene todas las cookies  

•	getSession(), retorna la sesión en la cual se encuentra el cliente

httpServletResponse permite enviar el cliente respuestas especificas del protocolo HTTP.

•	addCookie(Cookie cookie ), para definir nuevas cookies en el cliente

•	setHeader(String name, String value), para definir un headerHttp

•	sendRedirect(String location), envía mensaje al cliente para redireccionar la respuesta a la dirección señalada
