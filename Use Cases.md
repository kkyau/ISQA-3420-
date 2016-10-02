#Use Case 1 
###Title
Determine License and Vulnerability Information 

###Primary Actor 
Manager

###Goal In Context
The manager of the company is able to determine license and vulnerabilty information from provided software packages

###Stakeholders
 a) Manager = To be able to retrieve the precise information about the licenses and vulnerabilities about software packages
 
 b) Developer = To be able to provide the proper information regarding the relevant file/package information
 
###Preconditions 
 a) Relevant file/package licesne and vulnerability information in the database
 
 b) Manager provides proper query to receive license and vulnerability information from the database
 
###Main Success Scenario 
Manager receives accurate license and vulnerability information for the requested software packages.

###Failed End Conditions
Manager receives inaccurate or invalid license and vulnerability information for the requested software packages.

###Trigger
Manager uploads software package query to which license and vulnerability information is provided.


#Use Case 2 
###Title 
Developer Uploads Software Package to be Scanned for Licenses and Vulnerabilities 

###Primary Actor 
Developer 

###Goal In Context 
The developer is able to successfully upload software package for scanning. The uploaded package is scanned for licenses and vulnerabilities and the information is returned to the developer and written to the database. 

###Stakeholders 
 a) Developer = To be able to produce a software that has to be recognized by the database when it is scanned against it as well as fits                 the requirements of manager

 b) Manager = Has to ensure that the software pacakage is free of issues and fits all the requirements needed by the company

###Preconditions 
 a) There has to be a completed software package present to be able to scan it and check for vulnerabilities 
 
 b) There has to be a database that the package can be written to
 
 c) Ability to connect to the NST Vulnerability Database 
 
 d) Working version of FOSSology
 
###Main Success Scenarios 
The package is scanned and returned to the developer after the information has been stored in the database.  

###Failed End Conditions
 a) The package is scanned but the database does not add the software's licenses and vulnerabilities to the database. 
 
 b) The pacakage is scanned but is not returned to the developer 

###Trigger
Developer uploads software package to a database that is able to scan for license and vulnerabilities. 

#Use Case 3 
###Title 
Submitting a Project Request 

###Primary Actor 
a) Developer

b) Manager

###Goal In Context 
To be able to submit a project request as well as for the manager to be able to submit or modify policy documents. 

###Stakeholders 
a) Manager

b) Developer

###Preconditions 
a) There has to be a data store available to scan the software package against.

b) The manager has to have the proper information to modify or update the data store. 

###Main Success Scenarios 
a) The software package is scanned and the data store is able to scan the package and return the results accordingly. 

b) When the manager attempts to modify or update the policy documents, the data store recognizes the changes and saves the changes. 

###Failed End Conditions 
a) The package is scanned but the data store is unable to identify the proper license and vulnerabilities. 

b) The package is scanned but not returned to the developer or the manager. 

c) The data store does not recognize that the manager is trying to modify or update policy documents. 

###Trigger 
a) The developer or manager uplaods a package requesting to identify licenses or vulnerabilities. 

b) The manager attempts to modify or update policy documents. 

