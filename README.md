Vulnerable Web Training Environment (VWTE)
Based on XVWA - Xtreme Vulnerable Web Application

SECURITY WARNING
DO NOT HOST THIS APPLICATION ON A PRODUCTION OR LIVE ENVIRONMENT

This application is intentionally designed with severe security vulnerabilities for educational purposes only. Deploying it on a live server could lead to complete system compromise.

Overview

VWTE is a deliberately vulnerable web application written in PHP/MySQL designed to help security enthusiasts, students, and professionals learn about web application security vulnerabilities in a safe, controlled environment. This training platform provides hands-on experience with real-world security flaws commonly found in web applications.

Purpose

- Educational Tool: Learn web application security fundamentals
- Penetration Testing Practice: Sharpen security testing skills
- Vulnerability Research: Understand how security flaws work
- Security Training: Provide practical experience for security professionals

Included Vulnerabilities

VWTE includes the following security vulnerabilities for training purposes:

Injection Attacks
- SQL Injection (Error Based) - Learn to exploit database queries
- SQL Injection (Blind) - Practice advanced SQL injection techniques
- OS Command Injection - Understand command execution vulnerabilities
- XPATH Injection - Explore XML path language injection
- Formula Injection - Learn about spreadsheet formula attacks
- PHP Object Injection - Understand serialization vulnerabilities

Cross-Site Scripting (XSS)
- Reflected XSS - Practice client-side script injection
- Stored XSS - Learn persistent script attacks
- DOM-Based XSS - Understand client-side DOM manipulation

File and Upload Issues
- Unrestricted File Upload - Explore file upload vulnerabilities
- File Inclusion - Learn about LFI/RFI attacks

Access Control Issues
- Insecure Direct Object Reference (IDOR) - Practice authorization bypasses
- Missing Functional Level Access Control - Understand privilege escalation
- Session Flaws - Learn about session management issues

Advanced Attacks
- Server Side Request Forgery (SSRF/XSPA) - Practice server-side attacks
- Cross Site Request Forgery (CSRF) - Learn about state-changing attacks
- Server Side Template Injection (SSTI) - Understand template engine exploitation
- Cryptography Issues - Explore weak cryptographic implementations
- Unvalidated Redirects & Forwards - Practice redirect attacks

Installation & Setup

Prerequisites
- Web server (Apache/Nginx)
- PHP 5.6+ (with MySQL support)
- MySQL/MariaDB database
- Local development environment (XAMPP, WAMP, LAMP, or Docker)

Installation Steps

1. Clone/Download the application files to your web server directory
2. Database Setup: Navigate to /xvwa/setup/ for database configuration
3. Configure your web server to serve the application
4. Access the application via http://localhost/xvwa/

Quick Setup
Example for XAMPP on Windows
1. Extract files to C:\xampp\htdocs\xvwa\
2. Start Apache and MySQL via XAMPP Control Panel
3. Open browser: http://localhost/xvwa/
4. Follow setup instructions

Getting Started

1. Setup Phase: Use the setup/reset functionality to initialize the application
2. Read Instructions: Check the instructions page for vulnerability details
3. Practice: Start with basic vulnerabilities like SQL injection
4. Progress: Move to more complex attacks as you gain experience
5. Learn: Understand both the attack and defensive measures

Application Structure

xvwa/
├── index.html              # Main application page
├── setup/                  # Database setup and reset
├── instruction.php         # Learning instructions
├── vulnerabilities/        # Vulnerability modules
│   ├── sqli/              # SQL Injection labs
│   ├── reflected_xss/     # XSS practice
│   ├── fileupload/        # File upload tests
│   ├── csrf/              # CSRF demonstrations
│   └── ...                # Other vulnerability modules
├── css/                   # Stylesheets
├── js/                    # JavaScript files
└── img/                   # Images and assets

Learning Approach

For Beginners
1. Start with SQL Injection basics
2. Move to XSS attacks
3. Practice File Upload bypasses
4. Learn Session manipulation

For Intermediate Users
1. Explore Blind SQL Injection
2. Practice CSRF attacks
3. Learn SSRF techniques
4. Understand Access Control issues

For Advanced Users
1. Master PHP Object Injection
2. Practice Template Injection
3. Explore Advanced Cryptography flaws
4. Combine multiple attack vectors

Legal and Ethical Use

- Local Testing: Use in controlled, local environments
- Educational Purpose: Learn and improve security skills
- Authorized Testing: Practice on systems you own or have permission to test
- Never use these techniques on systems without permission
- Don't use knowledge for illegal activities

Security Best Practices

While using VWTE, remember these security principles:

1. Input Validation: Always validate and sanitize user input
2. Output Encoding: Properly encode data before display
3. Authentication: Implement strong authentication mechanisms
4. Authorization: Ensure proper access controls
5. Encryption: Use strong cryptography for sensitive data
6. Error Handling: Don't expose sensitive information in errors

Contributing

Suggestions for improvements or additional vulnerabilities are welcome:
- Report issues or suggestions
- Contribute new vulnerability modules
- Improve documentation
- Share learning resources

Support & Community

For questions, discussions, or support:
- Review the application's instruction pages
- Practice in a safe, isolated environment
- Share knowledge responsibly within the security community


Disclaimer

IMPORTANT: This application contains intentional security vulnerabilities and should NEVER be deployed on production systems. The authors are not responsible for any misuse of this educational tool. Users are responsible for using this knowledge ethically and legally.


Remember: The goal is to learn about security vulnerabilities to better defend against them. Use this knowledge to build more secure applications and protect systems from real attacks.

Stay Safe, Stay Ethical, Keep Learning!
