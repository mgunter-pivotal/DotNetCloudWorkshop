# SpringCloudWorkshop

Pre-Requisites:

1. Windows or Mac OSX 
2. Java JDK 1.7+ 
3. Install the PCF CLI (download from the link below)

https://apps.pcf14.cloud.fe.pivotal.io/tools 

4. Firefox or Chrome (Not IE)


Smoketest:

1. Git clone https://github.com/jrolfe-pivotal/SpringCloudWorkshop.git 
2. cd SpringCloudWorkshop/session_04/lab_07/complete/hello-actuator
3. gradlew.bat assemble ( or ./gradlew on MacOSX)
4. java -jar build/libs/hello-actuator-0.0.1-SNAPSHOT.jar
5. browse to http://localhost:8080
6. cf login -a https://api.pcf14.cloud.fe.pivotal.io --skip-ssl-validation (use student1/carn1valc0rp)

Recommended, but Optional Software : Spring Tool Suite, or IntelliJ IDE
