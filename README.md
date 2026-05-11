#Cybersecurity Internship – Week 1
Report
Objective
The objective of Week 1 was to perform a basic security assessment of the web
application and identify common vulnerabilities. Tasks Performed
1. Application Setup
Downloaded and configured the Node.js authentication project. Connected the application with MongoDB Atlas. Successfully ran the application on localhost. 2. Cross-Site Scripting (XSS) Testing
Tested the application using the following payload:
<script>alert('XSS')</script>
Result
The script was displayed as plain text. No popup or script execution occurred. Conclusion
The application was not vulnerable to basic XSS attacks. 3. SQL Injection Testing
Attempted SQL injection testing on the login form. Result
Browser validation blocked invalid email formats.Injection attempt did not
bypass authentication.
Conclusion
No basic SQL Injection vulnerability was identified. 4. Input Validation Check
Tested invalid email formats and user inputs. Result
The application rejected invalid email inputs successfully. Conclusion
Basic frontend validation was implemented in the application. Final Findings
XSS Attack: Safe
SQL Injection: Safe
Input Validation: Implemented
Conclusion
Week 1 successfully completed the security assessment and vulnerability testing of
the web application.


Cybersecurity Internship – Week 2
Report
Objective
The objective of Week 2 was to strengthen the security of the application by
implementing authentication and validation improvements. Security Enhancements Implemented
1. Backend Input Validation
Implemented email validation using the validator library. Invalid email formats are now rejected on the backend. 2. Password Hashing
Implemented password hashing using bcrypt. User passwords are now stored securely in encrypted form. 3. Secure Password Comparison
Implemented bcrypt.compare() during login authentication. Improved password verification security. 4. Security Headers
Implemented Helmet.js middleware. Improved HTTP header security against common attacks.
5. JWT Authentication
Implemented JSON Web Token (JWT) generation after successful login. Enhanced secure authentication handling. Results
Passwords are encrypted. Authentication security improved. Input validation strengthened. Secure authentication token implemented. Conclusion
Week 2 successfully improved the application security using modern authentication
and validation techniques.

Cybersecurity Internship – Week 3
Report
Objective
The objective of Week 3 was to implement logging, perform final monitoring setup, and complete the security enhancement process. Tasks Performed
1. Logging System Implementation
Installed and configured the Winston logging library. Created a security.log file for activity monitoring. 2. User Activity Logging
Added logging for:
User Registration
User Login
Server Startup
Database Connection
3. Security Monitoring
Successfully monitored application activities through logs. Verified that logs were being stored correctly in the security.log file.
4. Security Checklist
Input validation implemented
Password hashing implemented
JWT authentication implemented
Helmet.js security enabled
Winston logging enabled
XSS testing completed
SQL Injection testing completed
Results
Security logs are successfully generated. User activities are properly tracked. Application monitoring has improved. Conclusion
Week 3 successfully completed the logging and final security monitoring
implementation for the web application.
