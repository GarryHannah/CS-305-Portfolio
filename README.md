# CS-305-Portfolio

​​CS 305 – Portfolio Artifact: Artemis Financial Practices for Secure​ ​Software (Project Two​) 

1. ​​Briefly summarize your client, Artemis Financial, and its software​ ​requirements. Who was the client? What issue did the company want you to​ ​address? 

Artemis Financial is a​ financial ​consulting company that​ makes ​financial plans for customers. They​ wanted ​their​ web app updated to be more secure, especially around protecting customer data and using secure communication. 

2. ​​What did you do well when you found your client’s software security​ ​vulnerabilities? Why is it important to code securely? What value does​ ​software security add to a company’s overall well-being? 

I did well​ by working in small steps and testing as I went, instead of changing everything at once. Coding securely matters because if an app is weak, customer data can be exposed or changed. Good security helps protect the company’s reputation, avoids expensive problems later, and helps keep customers’ information safe. 

3. ​​Which part of the vulnerability assessment was challenging or helpful to​ ​you? 

The helpful part was​ running the security scan because it clearly showed what might be risky in the project. The ​challenging part was​ ​understanding the​ results ​and figuring out​ what was coming from the libraries/dependencies versus what was coming from my own code. 

4. ​​How did you increase layers of security? In the future, what would you​ ​use to assess vulnerabilities and decide which mitigation techniques to​ ​use? 

I added​ HTTPS to ​protect data​ while it travels ​between the​ browser ​and the server​, and I added a SHA-256 checksum feature to help verify data was not changed. ​In the future, I​ would ​keep using tools like​ ​dependency-check and​ also do a manual review to decide what to fix based on how serious the issue is. 

5. ​​How did you make certain the code and software application were​ ​functional and secure? After refactoring the code, how did you check to​ ​see whether you introduced new vulnerabilities? 

I made sure it​ worked by running the application, ​checking the​ HTTPS page in the browser, and verifying the checksum output. After I made changes, I ran dependency-check again ​to make sure I didn’t​ add ​new security​ problems. 

6. ​​What resources, tools, or coding practices did you use that might be​ ​helpful in future assignments or tasks? 

I used​ Java Keytool to create a certificate, Java’s built-in MessageDigest for hashing, and OWASP dependency-check for vulnerability scanning. Helpful practices were using trusted built-in tools, picking stronger algorithms, and not showing too much detail in error messages. 

7. ​​What might you show future employers from this assignment? 

I would show​ the finished ​report​ and the updated code that demonstrates HTTPS working and the checksum feature. I would also show that I can run a vulnerability scan and explain what the results mean at a basic level. 
