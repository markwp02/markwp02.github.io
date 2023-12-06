# Software Engineer
Java, Spring boot, Hibernate, React, AWS, Pega

## Education
### Monash University
Bachelor Of Science (Computer Science)  
WAM: 81.176 and GPA: 3.636

### Certifications
[Pega Certified Senior System Architect](https://academy.pega.com/verify-certification?fname=Mark&lname=Paterson)


## Work Experience
### Mar 2022 - July 2022 Application Developer
Red Energy
- Design, develop and unit test end to end software integration application using Groovy, Spring boot and Apache Camel
- Created routes to handle Google Drive file operations in the Camel application, using the Google Drive Component
- Automated a billing email process that would save Operations 2 to 3 days of manual labor a month

### Jan 2017 - Feb 2022 Software Engineer 
Verra Mobility
- Develop, debug and troubleshoot both Java Spring boot and Pega web applications 
- Contributed to over 350 knowledge based articles increasing productivity of the team overall
- Trusted to own the most critical issues and resolve within the business SLA
- SME for NSW and Canada clients that routinely provided advice and assistance to fellow engineers

## Projects
### eCommerce website
As a web developer, I wanted to create a project that can showcase the core skills. That is to create a web application. I chose to create an eCommerce website, where the customer can do the fo
- aawefew

### Downloads Cleanup
     
If your like me, you routinely download files from the web, without either deleting or filing away the files. Over time, this can leave your downloads folder with many files and difficult to find the ones you want.

The Downloads Cleanup project is aimed at solving this problem by routing files by there entension. This project is a great oportunity to showcase the power of Apache Camel with its' Java Domain Specific Language (DSL), that routes from one File endpoint.   
The following file suffixes are configured:

- Pdf files .pdf &rarr; /pdf
- text files .txt, .log  &rarr;  /text
- code files .java, .sql, .html, .js, .css &rarr; /code
- image files .jpg, .png, .jpeg &rarr; /image
- compressed files .zip, .7z &rarr; /compressed
- executable files .exe &rarr; /app  

These file extensions, as well as the name of the directory to route to can be configured within the application.properties file.

![Dir listing before](./assets/img/dirListing.png)

After running the application

![Dir listing after](./assets/img/dirListingAfter.png)

The files have all been routed to the destination directory

![Routed directories](./assets/img/routedDirectories.png)  

Where the files are archived based on the current date
![Archived code files](./assets/img/codeFilesListing.png)  

[View the code](https://github.com/markwp02/DownloadsCleanup)