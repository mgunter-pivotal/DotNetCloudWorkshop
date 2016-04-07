# DotNetCloudWorkshop

Pre-Requisites:

1. Windows
2. Java JDK 1.7+ (perhaps optional?)
3. Install the PCF CLI (download from the link below)
4. Visual Studio

https://apps.pcf7.cloud.fe.pivotal.io/tools 

4. Firefox or Chrome (Not IE)

Smoketest:

1. Git clone (or download and unzip from Git) https://github.com/mgunter-pivotal/DotNetCloudWorkshop.git 
[fix below]
2. cd DotNetCloudWorkshop/session_04/lab_07/complete/hello-actuator
3. gradlew.bat assemble ( or ./gradlew on MacOSX)
4. java -jar build/libs/hello-actuator-0.0.1-SNAPSHOT.jar
5. browse to http://localhost:8080
6. cf login -a https://api.pcf14.cloud.fe.pivotal.io --skip-ssl-validation (use student1/carn1valc0rp)

Optional:

 1.  ASP.NET 5 - at least one of the labs will be done using ASP.NET 5.  A completed version of this lab will be available/usable for those that don't want to install ASP.NET 5, and just want to review/push the code to Cloud Foundry.
