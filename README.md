## Spring Context, Beans
Spring Context, Beans, Dependency Injection, SpringMVC  <br />
Configuration with xml and annoations   <br />

### Technologies
Spring Core, Context, Beans, Dependeny Injection, SpringMVC <br /> 



### Standalone Application
AnnotationConfigApplicationContext <br /> 
Annotation based configuration: class MyConfiguration  <br /> 



### SpringMVC Application
XmlWebApplicationContext <br />
Configuration files: web.xml, servlet-context.xml <br />

Xml-configured bean: MyBean <br />
Annotation-defined bean: MyAnnotatedBean <br />

Dependency injection:  <br />
Bean injection: @Autowired annotation <br />




### Steps
#### Standalone Application
##### Compile 
*mvn clean compile*  <br />

##### Run Application
*mvn exec:java@main* <br />


#### SpringMVC Application
##### Run with embedded Jetty:
*mvn clean compile install jetty:run*


##### Acces Application:
*localhost: 8080*
