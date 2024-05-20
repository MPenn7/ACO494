*Group members:
Alexander Molina
Marshall Pennington
Matt Yonsetto
Matt Rebeles

*Description
This applicatioin implements 2 vulnerabilities which are then detected by AppScan on the cloud. It is built on finding
vulnerabilities on the Altoroj application.

Altoroj is a banking application it is shown as an example as to what could happen to an application
when only funcionalities are taken into consideration and not security.

AltoroJ uses Apache Derby as it's SQL database that is automatically initialized the first time you login
via its web interface. All transactions done will be stored on the database rom that point on until you delete
your repository called "altoro that loacated in your os home folder.


*Prerequisites 
Visual Code 1.88.1
Apache Tomcat 8.5.100
Gradle 7.4.2
JRE jre1.8.0_351 
	*Extensions
		Debugger for Java
		Extension Pack for Java
		Gradle for Java
		HCL Appscan Codesweep
	
*Vulnerabilites
-Insecure direct object references (IDOR)
-Unvalidated Redirects and Forwards

*Minor Vulnerabilites
-Password stored in Java String Object
-printStackTrace is used in the program


