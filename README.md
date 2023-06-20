# CS_305_Software_Security

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that provides financial recommendations to its customers. Because of the sensitive information that Artemis Financial has and maintains, it is necessary that it employs strong security in its software. The assignments for this class revolved around implementing many security features into its software.

### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
When vulnerabilities were found, they were reviewed to determine the threat they posed. If it was determined that these vulnerabilities were false positives, they were suppressed in the static testing reports. If the vulnerability was real, they were dealt with appropriately (e.g., updating dependencies, refactoring code to remove the vulnerability, adding extra security features like certificates and encryption, etc.). It is important to code securely to prevent potential attacks on software. This improves a company's wellbeing by protecting its sensitive data and reputation while also keeping the services that it provides active and running.

### What part of the vulnerability assessment was challenging or helpful to you?
The most helpful part of the vulnerability assessment was incorporating encryption and certificates. Having a chance to do this in a hands-on project taught me how to utilize these tools in a real-life scenario.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
As stated above, a number of layers of security were added. These include the use of certificates, encryption, and updating dependencies. For future projects, I will use the tools and skills gained from this class to assess vulnerabilities. These include manual code review and the OWASP Dependency Check tool. Both of these are useful to find vulnerabilities and assess their best mitigation strategy.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
The main tool for this was the OWASP Dependency Check tool. It helped to identify vulnerabilities within the dependencies for the code and identify those that needed to be updated. It also helped to ensure that no additional vulnerable dependencies were added to the code. Additionally, a manual code review helped to ensure that there were no vulnerabilities in the code itself.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The most impactful tools that I used during this course were Maven and the OWASP Dependency Check tool. The two worked together to identify deficiencies and manage dependencies to ensure that all code was up to date and functioned well together.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
The most important thing I can show from this assignment is my ability to understand the problem at hand and work with the information and tools available to solve the task. Real-life problems are so varied that it is impossible to be knowledgeable and skilled enough to solve everything that presents itself without analyzing the situation and determining what additional information and skills are needed. This assignment shows that I have that ability.
