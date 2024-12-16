# Software-Security

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
-
Artemis Financial is a consulting company that works to create financial plans for its customers. They are looking to streamline their efforts and improve software security in order to protect the customer's data.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
-
Post finding Artemis Financial's software vulnerabilities, I understood the concerns and addressed the vulnerabilities as they should be. It is important to code securely in order to avoid collisions and attacks that could compromise the customer's personal data. Software security reflects directly on the company's reputability. A company that shows less concern for software security is at higher risks for malicious attacks.

Which part of the vulnerability assessment was challenging or helpful to you?
-
The part of the vulnerability assessment that was hard for me was assessing the different vulnerabilities that came up on the dependency check report and ciphering out the false positives.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
-
To increase layers of security, I implemented hashing with SHA-256 to ensure that sensitive data could not be exposed. In the future, I would continue to use vulnerability scanners like OWASP to identify vulnernerabilities, conduct penetration testing and continuously evaluate risks. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
-
Implementing tools like OWASP Dependency Check ensures that communications with third party libraries were secure and up to date. Running these dependency checks each time a vulnerability was addressed ensures that if any new vulnerabilities were introduced, they could be addressed accordingly.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
-
Before this course I had not run dependency checks before so understanding how to check for vulnerabilities as well as address them as needed will help for future assignments that deal with security issues.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
-
For this project, I would most likely showcase my implementation of SHA-256 as well as address the vulnerability checks.
