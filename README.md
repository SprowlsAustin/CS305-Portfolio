# CS305-Portfolio

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis financial is a consulting company that developed financial plans for a variety of people and organizations such as entrpreneurs businesses and government agencies. They are seeking to moderinize their operations and implement the latest software security technologies.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
Using the process flow diagram and dependency checks i was able to identify 8 significant vulnerabilities through manual code review and 218 during dependency checskc this helped me provide mitigation recomendations for each of the vulnerabilities i found. In terms of secure coding its important because Artemis could be help resonsible if there is a breach which could hurt the users and put artemis in legal regulartory and compliance troubles as well as lose the trust of its users. 

Which part of the vulnerability assessment was challenging or helpful to you?
the most challenging part for me was getting the dependency checker to work I was constantly having issues with my API key and server issues getting the dependency libraries to download. understanding the difference between false positives and real vulnerabilities was also a challenge. On the other hand the process flow diagram was very helpful to identify where in the system vulnerabilities fell.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
in terms of secuirty layers added I implemeneted data integrity verification with SHA-256, ecrypted comunication betweenn client and server with HTTPS, self signed certificates for server authenticatio(although real certificates would be used in production), and depdendency checks for identifying vulnerabilities.in terms of assessing vulnerabilities and mitigation techniques i would use OWASP, Manual code reviews, and based on severity mitigation decisions.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I verified that the code and application were functional by actually running the application and confirmed that the checksum and HTTPS were generated and used without errors. Furthermore I verified after refactoring by running dependency checks, and confirmed that my additons did not introduce any new vlnerabilities. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
the tools i used were OWASP, java keytool, maven, and spring boot. the resources i used were the oracle java security standarfd algorithm names, the national vulnerabilitiy database, and NIST standards.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
on the technical side the skils that i have shown and developed are that im able to run vulnerability checks and implement security protocals for secure communication and cryptographic algorithms. Some professional skills Im able to demonstrate are that I am able to write security reports and understand industry standard digital security while making decisons about mitigation and business requirements.
