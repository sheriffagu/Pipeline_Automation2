# Pipeline_Automation2
 Jenkins CI/CD Pipeline Automation

Project Overview

Designed and implemented a declarative Jenkins CI/CD pipeline to automate application builds, code quality checks, security scanning, artifact management, and environment approval workflows.

The project demonstrates hands-on experience integrating DevOps and DevSecOps tools into an automated software delivery process.

Technologies Used

- **CI/CD:** Jenkins Declarative Pipeline
- **Cloud Infrastructure:** AWS EC2
- **Version Control:** Git and GitHub
- **Build Automation:** Apache Maven
- **Code Coverage:** JaCoCo
- **Code Scanning:** SonarQube
- **Security Scanning:** Trivy
- **Artifact Management:** Nexus Repository
- **Notifications:** Slack
- **Deployment Environment:** Apache Tomcat

 CI/CD Pipeline Stages

1. **Tool Installation:** Prepare the required build tools.
2. **Checkout:** Retrieve application source code.
3. **Build:** Compile and package the application.
4. **Code Coverage:** Run code coverage analysis.
5. **Code Scanning:** Perform automated code analysis.
6. **Security Scanning:** Execute vulnerability checks.
7. **Quality Gate:** Check the configured quality requirements.
8. **Binary Storage:** Store build artifacts.
9. **Development Environment:** Execute the development environment stage.
10. **Development Notification:** Send a development workflow notification.
11. **QA Approval:** Request approval before proceeding.
12. **QA Environment:** Execute the QA environment stage.
13. **QA Notification:** Send a QA workflow notification.
14. **Production Approval:** Request authorization for production.

 Jenkins Pipeline Execution

**Build:** #44  
**Date:** October 22, 2026  
**Result:** All 14 displayed stages green  
**Average pipeline runtime:** Approximately 1 minute, 9 seconds

The Jenkins Stage View demonstrates the execution of automated build, code analysis, security scanning, artifact storage, notification, and approval stages.

 Pipeline Screenshot

![Jenkins Pipeline Build 44](screenshots/jenkins-build-44.png)

 Key Skills Demonstrated

- Jenkins declarative pipeline development
- CI/CD workflow automation
- DevSecOps security integration
- Build and artifact management
- Code quality and coverage analysis
- Environment approval workflows
- Troubleshooting and pipeline configuration

 Project Purpose

This hands-on project demonstrates the integration of development, security, and operational processes into a structured CI/CD workflow.
