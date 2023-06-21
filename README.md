# Pclub-infosec-task
## Learnt about buffer overflow
- Buffer overflow is a type of software vulnerability that occurs when a program or process tries to write more data into a buffer (a temporary storage area in memory) than it can hold.
- This excess data can overflow into adjacent memory locations, corrupting or overwriting the data stored there

## Underlying hint
- The website had a hint "Suite... yourself & start talking", this is a hint to use burp suite, a popular tool for web penetration testing.


## Burp suite
- Burp Suite is a popular software tool used for web application security testing.
- It is developed by PortSwigger, a company specializing in web security. Burp Suite is widely used by security professionals, penetration testers, and ethical hackers to identify vulnerabilities and perform security assessments of web applications.

## Using burpsuite to find potential vulnerabilities
- Identify input points: Identify input fields or areas in the web application where user-supplied data is accepted, such as text boxes, URL parameters, or request headers. These input points can potentially be the sources of buffer overflow vulnerabilities.

- Craft malicious input: Create payloads or test cases that include intentionally long or malformed data to test for potential buffer overflow conditions. You can use tools like scripting or custom code to generate these payloads.

- Modify requests using Burp Suite: Use the Burp Suite Proxy or Repeater module to intercept and modify the requests sent to the web application. Replace the original input values with your crafted malicious input.
