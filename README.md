# Book rental web application

Booksmania is a web application that provides a dynamic platform for book searching and rental. 

The key features of the application are:

1. Users can search book by Name or ISBN#.
2. Users will get notified via email 7 days prior to the end of the subscription.
3. Auto-suggestion of books according to the user search patterns.
4. Cart feature to save books in a cart for checkout.
5. Automatic email notification for subscription renewal as well as new book added.

# Deployment - DevOps Engineer role/activities
## Technologies used to deploy the application:

1. GitHub - Source code management tool
2. Maven - Builds the package
3. SonarQube - Code quality report generating tool
4. Nexus - Artifact storage tool
5. Jenkins - Continuous Integration tool
6. Tomcat - Web server to deploy the application onto it.

## DevOps Workflow.
### Continuous Integration:
1. Developers used to write and push the code to GitHub repository. Whenever the code changes happened, commits pushed by the developer Jenkins will check for the code changes, clone the repository and trigger the build. 
2. In build stage, Maven will start building the application by running maven lifecycle goals like validate, compile, test, package, install and deploy. So then package is ready to deploy. 
3. Meanwhile Sonarqube will starts with 'mvn clean sonar:sonar' goal and checking the code for code coverage, unit test cases, and generates the code quality report with the help of quality profile and quality gates threshold values.
### Continous Deployment:
1. With the help of 'mvn clean deploy' goal the war file will be pushed onto Nexus for storing and distributing the application package. Then with the help of integration of Tomcat and Jenkins this war file will be deployed to Tomcat automatically



# Development
## Technologies Used in the application:
Java, Spring, Hibernate, Maven, Bootstrap, Ajax, Jquery, HTML, CSS, MySQL, Sonar, jUnit, Rest API, Spring-scheduling, Spring-security

## learnings:

1. Creating a 4+1 view (includes ER diagram, class diagram, sequence diagram, component interaction diagram, deployment diagram etc.)
2. Basic Design Patterns (Object Factory, Singleton etc.)
3. MVC Framework
4. ORM
5. Logging
6. Scheduler for feed file processing and any other scenario as necessary
7. DB concepts (Stored Procedure)
8. XML/XLS parsing
9. PDF Report Generation
10. Basic idea of Ajax, jQuery
11.	Profiling
12.	Build Scripts
13.	Continuous Integration.
14.	Unit Test Cases.
15.	Code Quality Metrics and tools
