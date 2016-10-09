##External Entities 
a) Developer = Person who creates the software pacakage. 

b) Manager = Person in charge of the overseeing the developement of of the software package. 

##Processes
a) Scan package for vulnerabilities and licenses = Process where software pacakage is scanned for known vulnerabilities and licenses. 

b) Retrieve full list of project license and vulnerability information = Process where the request for the full list of project license and                                                                          vulnerability information is processed. 

c) Retrieve project policy = Process where the project policy is requested from the Project Policy for Licenses and Vulnerabilities. 

d) Update or modify project policy = Process where the manager sends a request to update project policy.

e) FOSSology = Process where the software package is scanned for any known licenses. 

##Data Stores
a) NIST Vulnerability Database = Database where the package is scanned against to check for any existing licenses. 

b) Project License and Vulnerability Information Database = Database containing existing project license and vulnerability. 

c) Project Policy For Licenses and Vulnerabilities Database = Database containing existing project policy for licenses and                                                                             vulnerabilities. 

##Data Flows 
a) Software pacakage = An assembly of files created by the developer to make a software.

b) Software package name = Software package sent to NIST Vulnerability Database to scan for existing license. 

c) NIST Vulnerability Database results = Results containing exisiting license in the software pacakage.

d) Software package result = Results from the scanned software pacakage. 

e) License results = Results after the software package has been scanned by FOSSology. 

f) License and vulnerability information = The results of the software package that has been scanned by the NIST Vulnerability Database and FOSSology that are being added to the Project License and Vulnerability Information Database.  

g) Project license and vulnerability request = Request sent by developer or manager to retrieve a full list of the existing project                                                    license and vulnerability information. 

h) Project license and vulnerability information = The results retrieved from the Project License and Vulnerability Information                                                            Database.

i) Project policy request = Request sent by developer or manager to retrieve existing policies from the Project Policy for Licenses and                               Vulnerabilities Database

j) Project policy results = Results retrieved from the Project Policy For Licenses and Vulnerabilities Database. 

k) Policy to be updated or modified = A request by the manager to update or modify the current policy in the Project Policy for Licenses                                       and Vulnerabilties Database
