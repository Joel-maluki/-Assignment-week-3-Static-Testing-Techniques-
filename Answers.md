1. What is static testing, and why is it important in software development?
Static Testing:
Static testing is a software testing technique that examines code, design documents, and requirements without executing the program. 
It focuses on detecting errors early in the development process by reviewing and analyzing artifacts.

Importance in Software Development:
Early Bug Detection – Identifies defects before execution, reducing costs.
Improves Code Quality – Ensures adherence to coding standards and best practices.
Saves Time & Effort – Fixing issues at an early stage is more efficient than after deployment.
Enhances Maintainability – Clean, well-reviewed code is easier to maintain.
Example: A software team reviews requirement documents before writing code to ensure clarity and avoid misinterpretation.

2. Differentiate between walkthroughs, technical reviews, and inspections. How do they help in static testing?
Method												Description						Purpose	Who is Involved?
Walkthrough	Informal meeting where the author explains the document/code to team members.	Knowledge sharing and gathering feedback.	Developers, testers, business analysts.
Technical Review	A formal review where experts analyze the document/code for defects and improvements.	Detect technical errors, improve code quality.	Senior developers, architects, testers.
Inspection	A rigorous, structured review with predefined checklists and defect logging.	Identify defects systematically before testing.	Moderator, author, reviewers, scribes.
How They Help in Static Testing:
Identify issues before execution.
Improve software quality and maintainability.
Ensure compliance with coding standards.
Reduce defects reaching later development stages.
3. What are static analysis tools, and how do they improve software quality?
Static Analysis Tools:
Static analysis tools automatically examine source code without executing it, identifying vulnerabilities, coding violations, and inefficiencies.

How They Improve Software Quality:
Early Detection of Errors – Find security flaws, syntax issues, and logical errors before execution.
Ensure Code Consistency – Enforce best practices and coding standards.
Enhance Maintainability – Cleaner, structured code reduces future development effort.
Security Assurance – Detects potential security vulnerabilities like SQL injection and buffer overflow.
Example: A static analysis tool scans a Java project and reports unused variables, memory leaks, and deprecated methods.

4. Mention two benefits of using static analysis tools in software development.
1. Reduces Debugging Effort
Detects errors before runtime, saving time spent on debugging.
Eliminates hard-to-trace defects that might cause failures later.
2. Enhances Security & Compliance
Identifies security loopholes such as SQL injection, cross-site scripting (XSS), and buffer overflow.
Ensures compliance with industry standards like OWASP, ISO/IEC 27001.

5. List two popular static analysis tools and briefly describe their key features.
1. SonarQube
Feature: Detects code smells, bugs, and security vulnerabilities.
Supports: Multiple languages (Java, Python, C++, etc.).
Benefits: Provides detailed dashboards and integrates with CI/CD pipelines.
2. ESLint
Feature: Checks JavaScript code for syntax errors, style violations, and best practices.
Supports: JavaScript and TypeScript projects.
Benefits: Customizable rules and real-time linting in code editors.
