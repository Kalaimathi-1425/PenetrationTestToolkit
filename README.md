# PenetrationTestToolkit
COMPANY:CODTECH IT SOLUTIONS
NAME:KALAIMATHI G
INTERN ID:CT04DG1843
DOMAIN:CYBER SECCURITY & ETHICAL HACKING
DURATION:4 WEEKS
MENTOR:NEELA SANTHOSH
DESCRIPTION:
📄 Internship Project Report
As part of the CodTech Cyber Security Internship, Task 3 required the design and development of a Penetration Testing Toolkit using Python. The aim was to simulate basic offensive security tasks, such as port scanning and brute force attacks, in a safe and controlled environment. The toolkit serves as a foundational project to understand how penetration testing tools operate and how attackers might probe systems for weaknesses.

🎯 Objective
The core objective of this task was to create a modular Python application that includes multiple penetration testing tools such as:

A Port Scanner – to detect open network ports on a target system.

A Brute Force Simulator – to demonstrate how password brute-forcing works.

By building these tools, I gained hands-on experience in cybersecurity operations and deepened my understanding of how ethical hackers identify and exploit vulnerabilities.

🧰 Tools & Technologies Used
Programming Language: Python 3.x

Libraries:

socket – for creating the port scanner

time – for simulating delays in brute-force attempts

Environment: Visual Studio Code on Windows 10

All tools were built with Python’s standard libraries, which helped avoid third-party dependencies and maintain simplicity and portability.

🔍 Toolkit Features
Port Scanner
This tool allows users to enter a target IP address and scan a range of ports to determine which ones are open. It uses the socket module to attempt connections to each port and reports back those that are open. This simulates what tools like Nmap do on a much smaller scale.

Brute Force Simulator
This tool mimics a password brute-force attack on a simulated login system. It uses a hardcoded password list and checks each password against a predefined correct one. While this tool does not attack real login systems, it provides valuable insight into how attackers might use automated scripts to guess passwords.

Menu-Driven Interface
The toolkit features a simple command-line menu where the user can select which tool to use. This makes it user-friendly and easy to extend in the future by adding more tools.

✅ Testing and Results
To test the toolkit:

The Port Scanner was run against 127.0.0.1 (localhost) and correctly identified open ports such as 80 (HTTP) or 443 (HTTPS), depending on which services were running.

The Brute Force Simulator successfully found the correct password from a small list and demonstrated how easily weak passwords can be broken.

Although these tools are basic, they effectively illustrate the risks of misconfigured systems and weak authentication.

💡 Learning Outcomes
This task taught me how to:

Use Python to interact with network sockets

Write modular code that can scale with more tools

Simulate security attacks in a safe, ethical way

Think like both a defender and an attacker

It also improved my programming skills, especially in error handling, user input, and structuring code for usability.

📝 Conclusion
Task 3 was a crucial step in understanding real-world cybersecurity practices. By building a Penetration Testing Toolkit from scratch, I learned how attackers think and act, and how systems can be tested for vulnerabilities. The project is a strong foundation for future ethical hacking tools, and it opened doors for further enhancements like adding GUI support, more modules (DNS lookup, banner grabbing), or real network protocol integration (e.g., SSH, FTP). This task was not only educational but also rewarding and inspiring.
OUTPUT:
![Image](https://github.com/user-attachments/assets/431b4b38-d7e7-46b9-8f72-fb430ed6eccd)

