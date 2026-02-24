# CS-305-Portfolio

## Project Overview

This repository contains my Artemis Financial Vulnerability Assessment Report, completed as part of CS 305 Secure Coding. The project demonstrates my ability to identify security risks, perform vulnerability analysis, and recommend mitigation strategies for a financial web application.

## Reflection

### Client Summary and Software Requirements

Artemis Financial is a company that provides financial planning services through a RESTful API that manages sensitive customer data such as savings, retirement, and investment information. The client needed to ensure secure communications and protect customer data from threats such as unauthorized access, data interception, and injection attacks. My task was to assess the application for vulnerabilities and recommend improvements to strengthen its security posture.

### Strengths and Importance of Secure Coding

One area I performed well in was identifying vulnerabilities through manual code review and dependency analysis. I recognized issues such as missing authentication, hard-coded credentials, and outdated cryptographic libraries. Secure coding is essential because it protects sensitive data, maintains customer trust, and prevents financial and reputational damage. Strong software security contributes to a company’s stability, regulatory compliance, and long-term success.

### Challenges and Helpful Aspects

The most challenging part of the assessment was analyzing potential risks from incomplete implementations, such as database queries that could introduce SQL injection if written insecurely. However, this process was helpful because it strengthened my ability to think like an attacker and anticipate how vulnerabilities could be exploited.

### Increasing Security Layers and Future Practices

I increased layers of security by recommending authentication controls, HTTPS enforcement, input validation, least-privilege database access, and dependency management. In the future, I would use tools such as OWASP Dependency-Check, static analysis tools, and automated security scanners to assess vulnerabilities and determine appropriate mitigation strategies.

### Ensuring Functionality and Security

To ensure the application remained functional and secure, I recommended secure refactoring practices such as parameterized queries and structured error handling. After refactoring, security testing and dependency scans can verify that no new vulnerabilities were introduced and that the application still behaves as expected.

### Resources, Tools, and Best Practices

This project utilized OWASP Dependency-Check, National Vulnerability Database (NVD) references, and secure coding best practices such as input validation, encryption in transit, and least privilege. These tools and practices will be valuable in future coursework and professional development.

### Demonstrating Skills to Future Employers

From this assignment, I can show future employers my ability to perform vulnerability assessments, identify security risks, and implement mitigation strategies. This artifact demonstrates my knowledge of secure coding practices, risk analysis, and my commitment to protecting sensitive data in real-world applications.

#### Artifact Included

- Artemis Financial Vulnerability Assessment Report (Project One)
