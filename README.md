# DotNetCloudWorkshop

Pre-Requisites:

1. Windows
2. Install the PCF CLI (download from the link below)
+
===https://apps.pcf7.cloud.fe.pivotal.io/tools 
+
4. Firefox or Chrome (Not IE)

Smoketest:

1. Git clone (or download and unzip from Git) https://github.com/mgunter-pivotal/DotNetCloudWorkshop.git 
[fix below]
2. cd DotNetCloudWorkshop/session_01/lab_01/uk-towns-dotnet
3. cf push uktowns -s windows2012R2 -b binary_buildpack 
4. cf enable-diego uktowns
5. cf start uktowns
6. cf login -a https://api.pcf7.cloud.fe.pivotal.io --skip-ssl-validation (e.g. student1/w0rk5h0p)

Optional:

 1.  ASP.NET 5 - at least one of the labs will be done using ASP.NET 5.  A completed version of this lab will be available/usable for those that don't want to install ASP.NET 5, and just want to review/push the code to Cloud Foundry.
 2.  Visual Studio 2015 (All labs are "pre-published", but most students will want to follow along as we walk through some of the code)
