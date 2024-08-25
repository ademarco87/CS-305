# CS-305
CS 305 Software Security


Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a services company and was requesting to modernize their software, particuarly to address security vulnerabilities.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I achieved implementing AES and SHA-256 hashing to make a secure connection between the server and client using a self-signed Certificate. 

Which part of the vulnerability assessment was challenging or helpful to you?
One part I had difficulty at first was that my web browser (with Win11 pro) does not like self-signed certificates. It was difficult to get it to connect initially, but after changing some settings, was able to connect. Despite being a HTTPS, the web browsers on win11 do not like self-signed certificates.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I used AES and SHA-256 due to the nature of Artemis and their client. These are known to be the top security algorithms and are constantly re-assessed and tested against various bad-actor methods.  

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Initially, the code was tested to make sure a connection was created. Then implementing the HASH checksum afterwards. Doing a dependency check did not appear to intruduce any new volunerabilies aside form known forms. It would be beneficial to implement a automation to suppress the known volunerabilies, to easily identify any new ones being reported.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used the KeyTool for the certificate mangement. I did have some trouble with generating the certificate. After some investigation, I had multiple versions of the JDK - doing a clean install fixed the issues with the generation. Static analysis was used with the 10th dependency verions. The POM file whas changed from a very outdated version. Checking on the versions can only assist with checking on volunerabilies.  

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would highlight the successful outcomes in a presentation. Employers are rarely interested in the implementation, more so that results are as expected. Demonstrating that it was successful gives them a easy way to understand that it works as intended.
