#Use Case 1 
###Title
Determine License and Vulnerability Information 

###Primary Actor 
Manager

###Goal In Context
The manager of the company is able to determine license and vulnerabilty information from provided software packages.

###Stakeholders
 a) Manager = To be able to retrieve any known information about the license and vulnerability in the software package.
 
 b) Developer = To be able to provide the proper information regarding the package information.
 
###Preconditions 
 a) Relevant file/package license and vulnerability information in the database.
 
 b) Manager provides proper query to receive license and vulnerability information from the database.
 
###Main Success Scenario 
Manager receives accurate license and vulnerability information for the requested software packages.

###Failed End Conditions
Manager receives inaccurate or invalid license and vulnerability information for the requested software packages.

###Trigger
Manager uploads software package to which license and vulnerability information is provided.


#Use Case 2 
###Title 
Developer Uploads Software Package to be Scanned for Licenses and Vulnerabilities 

###Primary Actor 
Developer 

###Goal In Context 
The developer is able to successfully upload software package for scanning. The uploaded package is scanned for licenses and vulnerabilities and the information is returned to the developer and written to the database. 

###Stakeholders 
 a) Developer = To be able to produce a software package that has to be recognized by the database when it is scanned against it as well                 as fits the requirements of manager.

 b) Manager = Has to ensure that the software pacakage fits company requirements. 
 
###Preconditions 
 a) There has to be a completed software package present to be able to scan it and check for vulnerabilities 
 
 b) There has to be a database that the package can be written to.
 
 c) Ability to connect to the NIST Vulnerability Database.
 
 d) Working version of FOSSology.
 
###Main Success Scenarios 
The package is scanned and returned to the developer after the information has been stored in the database.  

###Failed End Conditions
 a) The package is scanned but the database does not add the software's licenses and vulnerabilities to the database. 
 
 b) The pacakage is scanned but is not returned to the developer 

###Trigger
Developer uploads software package to a database that is able to scan for license and vulnerabilities. 

#Use Case 3 
###Title 
Retrieving Project Policy For License and Vulnerabilities   

###Primary Actor 
a) Developer

b) Manager

###Goal In Context 
To be able to receive project policy for license and vulnerabilities upon request. 

###Stakeholders 
a) Manager = The manager should be able to retrieve project policy upon request. 

b) Developer = The developer should also be able to retrieve project policy upon request. 

###Preconditions 
There has to be a project policy for license and vulnerabilities in the database to be able to retrieve. 

###Main Success Scenarios 
The developer or manager are able to receive the project policy when requested.  

###Failed End Conditions 
The system is unable to return any results from the Project Policy For License and Vulnerabilities Database to the developer or the manager. 

###Trigger 
The developer or manager sends a request for the project policy.

