This project demonstrates a hands-on approach to identifying, exploiting, and mitigating SQL Injection vulnerabilities using Damn Vulnerable Web Application (DVWA). The goal of the project is to understand how SQL Injection works in practice, 
how attackers can manipulate HTTP requests to extract sensitive data, and how proper defensive techniques can effectively prevent such attacks.

The project is divided into three exercises, starting from basic vulnerability identification, moving to data extraction, and finally implementing secure coding practices to mitigate the issue.

Tools and Environment
For this project, DVWA was hosted locally using XAMPP on a Windows operating system. Apache and MySQL services were enabled through the XAMPP control panel, allowing DVWA to run on a local web server. 
The application was accessed through the browser at http://localhost/DVWA/, and the SQL Injection module was located at http://localhost/DVWA/vulnerabilities/sqli/.

Fiddler was used as the HTTP interception and request manipulation tool. It allowed inspection, modification, and replaying of HTTP requests sent from the browser to the DVWA application. 
In order to properly format SQL Injection payloads for use inside URLs, the website urlencoder.org was used to encode special characters such as quotes, spaces, and SQL operators before sending the requests.

This environment simulates a realistic attacker workflow where web traffic is intercepted, modified, and resent to the target application.

1. Discovering and Exploiting Basic SQL Injection Vulnerability
2. Extracting Database Structure Using UNION SQL Injection
3. Defending Against SQL Injection with Prepared Statements

**This project demonstrates the concepts and skills I gained through hands-on practice in web application security.
All techniques shown are intended for ethical and educational use only.**

-------------------------------------------------------------------------
## References & Inspiration
The methodology and high-level steps used in this project were inspired by publicly available GitHub resources related to web penetration testing, particularly the following repository:
https://github.com/0xrajneesh/Web-Pentesting-Projects-For-Beginners/blob/main/Project-1-Identifying-and-Exploiting-SQL-Injection-Vulnerabilities.md
