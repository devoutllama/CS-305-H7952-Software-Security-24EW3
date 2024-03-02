# CS-305-H7952-Software-Security-24EW3

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance. The company intends to modernize/digitize its operations. One thing they want from GlobalRain is how to protect their organization from external threats.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
One thing I did very well was my research and recommendation of a hash algorithm for the protection of their web application. We had to find a way to connect to and then make localhosts secure in the final part of the project using the chosen hash cipher. Coding securely is important because it reduces risk and shortens the room available for error which could lead to vulnerabilities. Software security ensures that a company is protected from external threats, attacks, and vendettas, which in turn builds the trust of the customers who patronize them.

# What part of the vulnerability assessment was challenging or helpful to you?
It was incredibly challenging trying to suppress the many vulnerabilities the application had. We were tasked with creating a suppression.xml file which contained code that would suppress the vulnerabilities, however, to do this, the program would have to be able to read the suppression file which it couldn't. The time spent attempting to fix was a learning experience and something I will continue to look out for.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
There are two ways I increased the layers of security. First was the hash algorithm I chose, the SHA-256. Cryptographic hash algorithms produce irreversible and unique hashes. The larger the number of possible hashes, the smaller the chance that two values will create the same hash. In other words, the SHA-256 algorithm ensures that collisions do not occur. The second form was through the suppression file. Every vulnerability had a code that could be used and applied for it to be suppressed, which produced the second layer of security.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made sure to run the program several times with different goals. The first goal was of course the program to run without any errors in installing the spring framework, which would serve to help display any vulnerabilities within the code. The second was to ensure that the code produced the things it was meant to - the vulnerability report. The first time running the program produced a vulnerability report of course. To ensure that no new vulnerabilities were created with my meddling, I had to compare the various vulnerability reports and examine any differences they might have had. If there were any new ones the best step would be to add its suppression code to  the supprssion.xml file. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
There was a lot of Stackoverflow involved, about errors I encountered when trying to do things like parse/read the suppression file. I also did things like directly copying the pom.xml file and modifying it, changing the name and contents to fit the suppression file. Ultimately, the most important tools were of course the advice and fixes of classmates. 

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
One thing that this assignment embodied for me was my resilience in fixing any problems that arose and my attention to detail. There were a lot of vulnerabilities to be suppressed, which meant a lot of code and time spent on the project. I suppose it shows that I am willing to get down and dirty to solve and come up with solutions to the problems that might arise.
