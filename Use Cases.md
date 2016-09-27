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
 a) Developer = To be able to produce a software that is license and issue free (Not really - it is about being able to scan software for this information. Software is not expected to be license free). 

 b) Manager = Has to ensure that the software package is free from license or vulnerabilities that might bring issues in the future (same comment) 

###Preconditions 
 a) There has to be a completed software package present to be able to scan it and check for vulnerabilities 
 
 b) There has to be a database that the package can be written to
 
 c) Ability to connect to NIST...
 
 d) Working version of FOSSology... 
 
###Main Success Scenarios 
The package is scanned and returned without any known issues or vulnerabilities from the database (The success scenario is really about writing the vulnerability and license information to the DB and also being able to return this information to the developer). 

###Failed End Conditions
The package is scanned and the results are returned with various license issues and vulnerabilities (see prior comments)

###Trigger
Developer uploads software package to a database that is able to scan for license and vulnerabilities. 
