#Use Case 1 
###Title
Determine License and Vulnerability Information 

###Primary Actor 
Manager

###Goal In Context
The manager of the company is able to determine license and vulnerabilty information from the software packages & license info

###Stakeholders
 a) Manager = To be able to retrieve the precise information about the licenses and vulnerabilities about the project
 
 b) Developer = To be able to provide the proper information regarding the relevant file/package information
 
 c) Compnay = To be able to understand the manager's decisions based on whether to move the project forward or not 
 
###Preconditions 
 a) Relevant file/package information in the database
 
 b) Proper project information has been provided 
 
###Main Success Scenario 
Manager receives accurate license and vulnerability information for the requested software packages.

###Failed End Conditions
Manager receives inaccurate or invalid license and vulnerability information for the requested software packages.

###Trigger
Manager uploads or identifies project information to which license and vulnerability information is provided.


#Use Case 2 
###Title 
Developer Scans for License and Vulnerabilities 

###Primary Actor 
Dveloper 

###Goal In Context 
The developer has to ensure that his software does not contain any licensed materials or issues before reporting to the manager

###Stakeholders 
 a) Developer = To be able to produce a software that is license and issue free

 b) Manager = Has to ensure that the software package is free from license or vulnerabilities that might bring issues in the future

###Preconditions 
 a) There has to be a completed software package present to be able to scan it
 
 b) There has to be a database that the package can be compared to
 
###Main Success Scenarios 
The package is scanned and returned without any known issues or vulnerabilities from the database 

###Failed End Conditions
The package is scanned and the results are returned with various license issues and vulnerabilities 

###Trigger
Developer uploads software package to a database that is able to scan for license and vulnerabilities. 
