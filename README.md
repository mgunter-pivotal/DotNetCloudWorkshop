# DotNetCloudWorkshop

Pre-Requisites:

1. Windows
2. Install the PCF CLI (from: https://apps.pcf7.cloud.fe.pivotal.io/tools )
4. Firefox or Chrome (Not IE)

Smoketest:

1. Git clone (or download and unzip from Git) https://github.com/mgunter-pivotal/DotNetCloudWorkshop.git 
2. cd DotNetCloudWorkshop/session_01/lab_01/uk-towns-dotnet
3. cf login -a https://api.pcf7.cloud.fe.pivotal.io --skip-ssl-validation (e.g. student1/w0rk5h0p)
4. cf push uktowns -s windows2012R2 -b binary_buildpack 
5. cf enable-diego uktowns
6. cf start uktowns (you should see the output below)

====

     state     since                    cpu    memory    disk      details
0   running   2016-04-07 05:52:52 PM   0.0%   0 of 1G   0 of 1G

====
Optional:

 1.  ASP.NET 5 - at least one of the labs will be done using ASP.NET 5.  A completed version of this lab will be available/usable for those that don't want to install ASP.NET 5, and just want to review/push the code to Cloud Foundry.
 2.  Visual Studio 2015 (All labs are "pre-published", but most students will want to follow along as we walk through some of the code)
