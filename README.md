# DotNetCloudWorkshop

Pre-Requisites:

1. Install the PCF CLI (from: https://apps.pcf7.cloud.fe.pivotal.io/tools )
2. Firefox or Chrome is preferred

Optional (but recommended):

 1.  ASP.NET 5 - at least one of the labs will be done using ASP.NET 5.  A completed version of this lab will be available/usable for those that don't want to install ASP.NET 5, and just want to review/push the code to Cloud Foundry.
 2.  Visual Studio 2015 (All labs are "pre-published", but most students will want to follow along as we walk through some of the code)

Smoketest:

1. Git clone (or download and unzip from Git) https://github.com/mgunter-pivotal/DotNetCloudWorkshop.git 
2. cd session_01/lab_01/uk-towns-dotnet
3. cf login -a https://api.pcf7.cloud.fe.pivotal.io --skip-ssl-validation (e.g. student1/w0rk5h0p)
4. select student1-org and development space
5. cf push uktowns -s windows2012R2 -b binary_buildpack  (verify final lines of console output matches the example below)

Console output:
====
----
          state     since                    cpu    memory    disk      details
     #0   running   2016-04-07 05:52:52 PM   0.0%   0 of 1G   0 of 1G
----
====

