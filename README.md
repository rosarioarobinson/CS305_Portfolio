# Software Security Portfolio for CS 305

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

Artemis Financial is a financial consulting company that manages individual plans based on savings, retirement, investments, and insurance. They wish to improve their software for their customer base and ask that their software security be updated to the best and most current applications. In my role as a software developer for Global Rain, I had to verify, document, and update Artemis Financial’s software security.

**What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**

While identifying Artemis Financial’s software security vulnerabilities, I identified the areas of security that needed to be handled, such as APIs and cryptography. In addition to this, I did a manual review of the vulnerability assessment performed, which identifies vulnerabilities within the code and the vulnerability assessment process flow diagram provided. Coding securely is important to ensure that not only the customer’s private data stays secure, but the company’s as well. Software security adds to the company’s wellbeing in that it ensures consistent protection of the company and customer data.

**What about the process of working through the vulnerability assessment did you find challenging or helpful?**

The most challenging part of the vulnerability assessment was understanding the areas of security (based on the vulnerability assessment process flow diagram) and how it relates to Artemis Financial. Ensuring that I understood what each area of security represented and how to best resolve the security issues for Artemis Financial was important, but also challenging to interpret. Overall, I was able to complete that section after doing additional research and understanding how to interpret Artemis Financial’s needs.

**How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?**

To approach the need for increased layers of security, I completed a vulnerability assessment report and practices for a secure software report. Both of these reports identify specific security vulnerabilities and issues within Artemis Financial’s system. The vulnerability assessment report focused on each area of security as it relates to Artemis Financial and implementing static testing, which meant completing a dependency check on their code. The practices for secure software report focused on explaining the appropriate algorithm cipher to help secure Artemis Financial’s software, generating a self-signed certificate to ensure networking while being online, deploying the algorithm cipher to the application, and additional testing to ensure all vulnerabilities are accounted for. Most of the techniques that I have learned in this course are valuable, but I believe that testing and dependency checks are some of the most important techniques to utilize in the future.

**How did you ensure the code and software application was functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

Specifically during project two, the practices for secure software report, multiple testing occurred with the code. There was secondary testing that occurred that utilized the dependency check tool that ensures the code compiles properly; once that test is completed, functional testing of the code is done to ensure the code functions properly. Completing multiple tests and manually including the dependencies within the pom.xml file allows for the system to cover all vulnerabilities present in the system.

**What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?**

A few of the resources that I find helpful and would use in future assignments or tasks were the use of dependency checks and self-signed certificates. Dependency checks seem to be very useful and once implemented a pom.xml file within your code, will allow you to see vulnerabilities within your systems for security purposes. Self-signed certificates are highly useful for authenticating for HTTPS purposes and would allow for me to ensure for small projects and future assignments that I have some protection for website-server verification.

**Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?**

To future employers, I would like to showcase my attention to detail within my assignment. Specifically with interpreting what the client wishes to see, detailing the areas of security required, and detailing the testing process. Creating both projects and reports allowed me to understand the fundamentals of software security and how to implement various techniques for a company that an employer would like to see.
