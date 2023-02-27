# CS-305
<b>Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?</b><br></br>
The client needed to address security concerns regarding secure communication and encryption of user and business data. <br></br>

<b>What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?</b><br></br>
I implemented cryptographic techniques to encrypt plain text user data, HTTPS was implemented to secure data channels, and certificates were implemented to make sure that both parties were transmitting data that had not been tampered with. It is important to code securely to make sure that business data and customer data is not leaked to bad actors and to also make sure the reputation of the company does not become tarnished. <br></br>

<b>What part of the vulnerability assessment was challenging or helpful to you?</b><br></br>
The most difficult part was generating the security certificate, this is because of how different an actual Unix based terminal differs from the command prompt on window, it was also difficult to find the certificate file on my mac due to how differently the file system behaves. Another problem I ran into was connecting to the local host on the specified port and this was probably due to the port not being open on my router. <br></br>

<b>How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?</b><br></br>
The layers of security would be to encrypt plain text data, secure the communication channel, and then to secure the application itself. My first step to checking the security of an application is to always make sure that the dependencies are up to date and I am on the lates stable version of a release because an out-of-date dependency likely has security flaws. I also always make sure the communication channel I am using is secure to make sure data being transmitted is not being leaked into the open internet/ web. <br></br>

<b>How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?</b><br></br>
This was done by running a dependency check by building/ compiling the pom.xml files/ application and checking the report that was generated. <br></br>
 
<b>What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?</b><br></br>
Reading documentation from oracle, stack overflow, and various other sources is always helpful to make sure that code is secure, correct, and follows industry best practices. I find it very helpful to always second guess myself and ask questions when needed if I do not fully understand a topic. <br></br>
<b>Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?</b><br></br>
I would show them they refactored code that I have completed, and the dependency check reports and also the explanations behind why I made the choices I did. It is important to be able to take flawed code, correct it, and then show the results from the corrected code. 
