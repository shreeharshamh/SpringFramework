JAVA FRAMWORKS
--------------
Its a programming language that helps us to solve particular problem and frameworks are nothing but
predefined API's which we can embed in our program.

JAVA FRAMEWORK PRINCIPLE
------------------------
Dont call us, we'll call you AKA IoC 
Do not worry about creating objects, framework is going to create the objects for you while you just
have to configure the objects.

CLASS A ------> CLASS B
CLASS A ------> CLASS B         Dependency

CLASS A <------ CLASS B
CLASS A <------ CLASS B         Injection

SPRING FRAMEWORK
----------------

DATA ACCESS/INTEGRATION         WEB (MVC/Remoting)
-----------------------         ------------------
JDBC    ORM                     Struts      Servlets
OXM     JMS                     Web         Websocket
Transactions                    Portlet

AOP     Aspects     Instrumentation     Messaging

            CORE CONTAINER
            --------------
Beans   Core        ExpressionLanguage  Context

                TEST
                ----

IOC CONTAINER
-------------
Configured by loading XML files or by specific Java Annotations or Configuration Classes
                      ---------                ----------------    ---------------------

Two Types of IOC Container
1. BeanFactor
2. ApplicationContext

Two ways to inject Dependency in Spring Framework
1. By Constructor       <constructor-arg>   subelement of <bean> used for Constructor Injection
2. By Setter Method     <property>          subelement of <bean> used for setter Injection


Spring is Lighweight and AWT is Heavyweight
Cos, while running AWT applications, AWT will use OS libraries
but, in case of Swings, it uses only jdk library & has no dependency with OS libraries.
however, EJB's are having dependency of ApplicationServers and thus it's Heavyweight.