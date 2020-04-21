# Implementation of MDC logging

    Nowadays, most real-world applications consist of a web application and REST service, i.e. 
    deployed on a remote server. Web applications are built using a client application framework, 
    while the REST service consists of a group of microservices. Unlike a traditional application 
    where a page is loaded with a single request per page, a modern application consists of a single page (SPA)
    and needs multiple service requests to load. Each service request hops over multiple microservices to 
    process the request. This poses a challenge in analyzing logs when multiple clients concurrently access 
    the application.
### https://dzone.com/articles/mdc-better-way-of-logging-1
