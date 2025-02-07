# Project: Automated Regression Testing Solution for Fictitious SaaS Cybersecurity Company (CyberSIEM Ltd.)

Goal: To exercise Software Project Management knowledge including SDLC methodologies (Feature Driven Development with Agile/SCRUM), Project Planning (MS project), Change Management, Release Management, and Testing/Bug Management. 

---
## Table of Conetents:
1. [Full_Executive_Presentation](./Full_Executive_Presentation/CyberSIEM_Final_Presentation.pptx) : Deck containing all materials listed after 5minute_Project_Pitch. If you want to see all materials at once, download this deck.
2. [5minute_Project_Pitch](./5minute_Project_Pitch/CyberSIEM_Pitch_(IN_CLASS).pptx) : Winning deck for in-class pitch competition. Winner was selected by a tribunal of industry professionals including: Vijay Krish (Head of Business Strategy & Operations @ ServiceNow), Silvia Ahmed (VP of Engineering @ Veritas), Sutanu Ghosh (Director of Program Management & PMO @ VMWare)
3. [Personas & User Stories](./Personas_&_UserStories/Personas&UserStories.pptx)
4. [SDLC Model](./SDLC_model/SDLC_model.pptx)
5. [Product Roadmap & Sprint Planning](./Product_Roadmap_&_Sprint_Planning/Product_Roadmap_&_Sprint_Planning.pptx)
6. [ROV & ROI](./ROV_ROI/ROV_ROI.pptx)
7. [Risk Analysis & Management](./Risk_Analysis_&_Management/Risk_Analysis_&_Management.pptx)
8. [Testing & Bug Management](./Testing_&_BugManagement/Testing_&_BugManagement.pptx)
9. [Architecture & Design](./Architecture_&_Design/Architecture_&_Design.pptx)
10. [Release Management](./Release_Management/Release_Management.pptx)
11. [Change Management & Project Plan](./ChangeManagement_&_ProjectPlan/ChangeManagement_&_ProjectPlan.pptx)
12. [Project Sprints & Retrospective](./Project_Sprints&Retrospective/Project_Sprints&Retrospective.pptx)


---
## Fictitious Company (CyberSIEM Ltd.) Overview

**Company**: CyberSIEM Ltd.  
**Industry**: Cybersecurity  
**Headquarters**: San Francisco, California  
**Number of Employees**: 175  
**Number of Software Developers**: 60  

**Mission Statement**:  
“To provide and enable strategic threat detection and response in the wake of sophisticated security needs.”

**Target Market**:  
Security Information and Event Management (SIEM) solutions, focusing on small to medium-sized firms.

---

## Project Nirvana - Automated Regression Testing with Selenium

### Business Objectives

CyberSIEM Ltd. seeks to:
- Reduce end-to-end regression testing efforts and costs.
- Increase the speed and efficiency of feedback loops to the development team.
- Identify and report bugs impacting strategic threat detection and incident response workflows.

### Challenges Faced

The internal **Security Operation Center (SOC)** team, acting as the first customer (Customer 0) of CyberSIEM's SIEM solution, currently performs manual end-to-end testing. This manual process includes:
- Executing over 200 test cases across major web browsers.
- Verifying pass/fail criteria.
- Manually analyzing results and reporting feedback to developers.

This approach is slow, error-prone, and resource-intensive, resulting in delayed bug detection and longer release cycles, thus impacting CyberSIEM Ltd.'s competitive edge.

### Current State Without Automation

The SOC team:
- Struggles to keep up with the manual execution of regression tests for every product update (both mainline and hotfix releases).
- Experiences delays in feedback loops to the development team, hindering fast fixes.
- Faces potential human errors in testing, risking the oversight of defects and bugs that could affect the solution's threat detection accuracy.

### Solution: Selenium Automation

To address these challenges, CyberSIEM plans to integrate **Selenium**, an open-source testing framework, to automate their regression testing process.

**Key Benefits of Using Selenium**:
- **Speed**: Automating over 200 test cases drastically reduces the time taken for regression testing.
- **Accuracy**: Selenium eliminates human errors in test execution and results verification.
- **Efficiency**: With faster feedback, development teams can quickly identify and resolve bugs.
- **Cross-browser Testing**: Selenium supports multiple browser environments, ensuring comprehensive testing coverage.
- **Cost-effective**: Reduces manual testing costs and optimizes resource allocation.

### Technical Overview

**Chosen Open Source Solution**: Selenium  
**Website**: [Selenium](https://www.selenium.dev/)

**Why Selenium**:
- Open-source and widely supported by the development community.
- Cross-browser compatibility for robust regression testing across different environments.
- Supports integration with CI/CD pipelines to streamline the software development lifecycle.

---

## Project Implementation

1. **Setup & Configuration**:
   - Integrate Selenium with existing testing frameworks.
   - Configure Selenium for multiple browser environments (Chrome, Firefox, Edge, etc.).
  
2. **Test Case Automation**:
   - Automate CyberSIEM’s 200+ manual regression test cases.
   - Design scripts to cover key threat detection and incident response workflows.

3. **CI/CD Integration**:
   - Embed Selenium-based automated tests into CyberSIEM’s continuous integration/continuous deployment (CI/CD) pipeline (Jenkins).

4. **Performance Monitoring**:
   - Track and analyze test execution time.
   - Generate reports for faster bug identification and fix.

