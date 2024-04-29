# CS305
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a client who was looking to provide secure communications and software to their clients.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
While reviewing DocData.java shows some vulnerabilities. The exception handling with ‘SQLException’ only prints the stack trace and may leak vulnerable information. DocData.java also does not have any input validation with means it could be vulnerable to SQL injections. GreetingController.java also lacks input validation. In CRUDController.java the value ‘business_name’ is received, but there is not input validation. Having secure software allows for a company to be confident in their client's privacy.

What part of the vulnerability assessment was challenging or helpful to you?
I found that the static testing was challenging to understand. You have to go through line by line to review the vulnerabilities to determine if they are a threat, if software needs to be updated, or if it's a false positive.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
By adding in algorithm ciphers to protect information and checking the dependency report for known vulnerabilities, I was able to provide secure software that is hopefully free from leaks.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
By running a second dependency report I could see if there were an increase in vulnerabilities. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The dependency check was a very neat tool that was introduced in this course. I will certainly use it in the future. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show future employers the Manual and static testing review from this assignment as I think it shows attention to detail.
