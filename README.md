# omegawebapp
Omega Infotech web application to manage Organization details, Services, Contact Us sections.

# Technologies Used
Front End : HTML, Bootstrap, Jquery and Font Awesome Library Back End : Core Java, Spring Boot with Spring MVC API for rendering web pages. Build : Maven packaging: WAR

# Setup
Download the project and add to IDE as existing maven project

Or

Use Github Desktop to pull the respository using the url link and import it as existing maven project into your workspace.

# Build
Go to the root folder application and type mvnw verify

On BUILD SUCCESS : war file will be created to the target folder inside application.

# Deployment
Take the war file from target and login to the web server machine.

Goto -> webapps javaee folder inside your tomcat directory (If folder not available create with same name webapps javaee) Place the war file inside the webapps javaee folder

Now goto the tomcat bin directory and type startup.bat to start the server and deploy the war file. On successful deployment your war file and folder with same war file name should be created insdie webapps folder.

STOP and START the server from Tomcat10 DAEMON Service Runner.

Access the link from any desired browser : https://www.omegainfotech.in

# Author 
Designed and Developed By @Omega Infotech
