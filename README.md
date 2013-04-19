
=======
voom306
=======

ecommerce project

  first of all :
  
  cd DemoSite
  
  mvn clean install 
  
  if you have some hibernate jar invalid try download manualy or change repository
  (hibernate from bbroadleaf repository seems invalid)
  
to launch:

       1) enter in site folder and do "ant jetty-demo" or "tomcat-demo" , it will target the task 
          jetty-demo in build.xml that execute mvn goal and start db
          look at "localhost:8080" for jetty and "localhost:8080/site" for tomcat
      
       2) after launch site project, enter in admin folder and do "ant jetty-demo"
          look at: "http://localhost:8081/admin" or "https://localhost:8444"

