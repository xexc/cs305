# cs305


Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting company that develop financial plans for individuals. These plans include retirement plans, savings, investments, and insurance. Artemis was seeking to add security to their existing application to ensure the most secure communications. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I enjoyed testing vulnerabilities via static testing. Its important to practice secure coding so that you reduce the risk or the chance of exposing the code to vulnerabilities. Software security adds protection to a company, as well as giving them peace of mind. 

What part of the vulnerability assessment was challenging or helpful to you?
The dependency check tool was probably the most helpful, it makes it much easier than checking each dependency by hand for vulnerabilities. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
When testing we can see that most of the vulnerabilities were caused by using old libraries, so updating the libraries currently in use in the code will result in more secure code. In the future, I'll probably make more use of online CVE databases, to find solutions to mitigate vulnerabilities easier.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Throughout coding the software, I was constantly running debugs to ensure that everything was functional. After refactoring the code, I ran through the same test cases to make sure everything was still operational.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I found the Maven Dependency checker tool very useful and will be using it in the future.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show my use of Dependency checkers to a future employer, this show them that I am competent with finding vulnerabilities within a codebase.
