# Software-Security


Artemis Financial is a consulting company that develops financial plans for customers like saving and retirement plans. Artemis Financial has a RESTful web application API and they were seeking our expertise to build a modernized secure application and protect their users from external threats.
 After I finished Vulnerability Assessment Repor, I Updated all the following dependencies: 
  * Update Spring Data Rest version to the latest version 3.6.2 
  * Update for tomcat to version 9.0.31 
  * Upgrade snakeyaml to a version without CVE-2017-18640
  * Update logback-core to Red Hat Single Sign-On 7.4.2
  * Update to hibernate-validator-6.0.20.
  * Update log4j-api to 2.12.3

With Artemis Financial's business model, it's important to keep communication safe to protect the client's information. Since Artemis Financial is a global financial consulting company that makes international transactions, it is an obligation to keep all client information confidential. While there are no government restrictions to consider building the safety requirements base on modern standards is a priority. It’s also important to be alert for any external threats such as spyware, adware, SQL injection, and other attacks. I used many tools to secure the application including implementing appropriate encryption algorithm cipher Generating self-signed certificates using the Java Keytool in Eclipse, running static testing using the OWASP Dependency-Check Maven to find any additional security vulnerabilities, and lastly manually reviewing the code to make sure no additional software security where introduced. 
The most useful tool I learned in this class that I probably will recommend to future employers is how to run OWASP Dependency-Check Maven (static test) to capture all dependency security vulnerabilities.
