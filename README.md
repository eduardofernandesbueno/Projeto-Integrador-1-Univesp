# Paió Brechó — Customer Management Web Application

**UNIVESP Integrative Project I | 2023**

**Full-Stack Web Development · PHP · MySQL · Relational Databases · Bootstrap · Software Engineering · Data Privacy**

**Original Academic Title:** *Desenvolvimento de um sistema web para a gestão de clientes de uma loja*  
**Institution:** Virtual University of the State of São Paulo (UNIVESP), Brazil  
**Academic Period:** 2023 — Integrative Project I  
**Academic Programs:** Information Technology, Data Science, and Computer Engineering  
**Application Domain:** Customer Management, Small Business Digitalization, and Sustainable Retail  
**Project Type:** Collaborative Academic Software Engineering Project  
**Status:** Completed academic prototype; historical source code

[Academic Presentation](https://youtu.be/wp8_hPguMc8) · [GitHub Profile](https://github.com/eduardofernandesbueno) · [Professional Portfolio](https://eduardofernandesbueno.github.io/)

---

## 1. Overview

**Paió Brechó** is a customer management web application originally developed during Integrative Project I at the Virtual University of the State of São Paulo (UNIVESP) in 2023.

The project investigated the design and implementation of a web-based system capable of collecting, storing, and retrieving customer registration data for a small second-hand retail business located in Capão Bonito, São Paulo, Brazil.

The original implementation combined frontend development, server-side programming, relational database design, local web server configuration, and academic software engineering practices.

The project used:

- HTML5 for page structure.
- CSS3 for styling and responsive layouts.
- Bootstrap 5.3 components for interface improvements.
- PHP for server-side programming.
- MySQL for relational data persistence.
- SQL for database schema and data operations.
- MySQL Workbench for database management.
- XAMPP and Apache for local execution.
- Visual Studio Code, Sublime Text, and PyCharm for development.
- Git and GitHub for source versioning and academic dissemination.
- Design Thinking for requirements discovery and iterative prototyping.
- Brazilian LGPD principles as part of the privacy discussion.

The application demonstrated successful customer data submission and retrieval from a MySQL database in the historical academic environment.

**Project maturity:** This repository is an academic prototype from 2023. It has not been independently validated as a production-ready customer management system.

---

## 2. Business Problem and Motivation

Small businesses often face challenges involving customer information management, fragmented records, and limited digital infrastructure.

The academic project focused on a second-hand retail store, Paió Brechó.

The team investigated whether a web-based customer registration system could help the business organize customer records and strengthen communication.

The identified challenges included:

- Lack of structured customer registration.
- Difficulties organizing and retrieving customer information.
- Limited digitalization of customer relationships.
- Dependence on manual records.
- Difficulty connecting physical retail activities with online communication.
- Concerns regarding privacy and personal data protection.

The project also considered sustainability, product reuse, and the economic role of small retailers.

---

## 3. Academic Objectives

### General Objective

Design and implement a web application for customer registration and information management using frontend technologies, PHP, and a relational database.

### Specific Objectives

1. Investigate the business requirements of a small retail organization.
2. Identify customer registration and information-management needs.
3. Develop a functional web interface.
4. Implement HTML and CSS pages.
5. Introduce a frontend framework.
6. Develop a PHP-based customer registration form.
7. Create a relational data model.
8. Connect the web application to MySQL.
9. Test data insertion and retrieval.
10. Explore responsive design and basic accessibility.
11. Study privacy and Brazilian LGPD considerations.
12. Apply software version control.
13. Document the results in an academic technical report.

The work was conducted as a collaborative undergraduate project.

---

## 4. Technology Stack

The technology stack below distinguishes the tools used in the prototype from languages and concepts discussed only as part of the academic background.

### 4.1 Frontend Engineering

| Technology | Project Role |
|---|---|
| HTML5 | Page structure and web forms |
| CSS3 | Interface styling and layout |
| Bootstrap 5.3 | Frontend framework and reusable components |
| CSS media queries | Responsive layout adaptation |
| HTML Forms | Customer information collection |
| Google Chrome | Browser-based testing |
| Safari | Browser-based testing |

The original system included informational pages and data-entry interfaces.

### 4.2 Backend Engineering

| Technology | Project Role |
|---|---|
| PHP | Form handling and server-side processing |
| Apache HTTP Server | Local web server |
| XAMPP | Local development environment |
| SQL | Data insertion, retrieval, and database operations |

The PHP components were responsible for processing customer information and communicating with the relational database.

### 4.3 Database Engineering

| Technology | Project Role |
|---|---|
| MySQL Server | Relational database management |
| MySQL Workbench | Database administration and inspection |
| SQL | Table and schema operations |
| Relational Data Modeling | Organization of customer records |
| Entity-Relationship Modeling | Conceptual database design |

The project created a database schema for customer registration.

### 4.4 Development Tools

| Tool | Role |
|---|---|
| Visual Studio Code | Source-code editing |
| Sublime Text | Web development |
| PyCharm | Development environment |
| Git | Version control |
| GitHub | Source-code hosting |
| Windows 11 | Development and testing |
| macOS | Development and testing |

### 4.5 Research and Engineering Methods

- Design Thinking.
- Stakeholder interviews.
- Requirements analysis.
- Qualitative research.
- Questionnaires.
- Prototyping.
- Iterative software development.
- Browser-based functional testing.
- Database connectivity testing.
- Technical-scientific documentation.

### 4.6 Academic Background — Not Core Implementation

The report also discusses Python, C, C++, object-oriented programming, and data warehousing as part of the broader computing curriculum.

These subjects should not be interpreted as proof that the completed application implemented a Python backend, C/C++ modules, or a data warehouse.

The primary implementation was based on HTML, CSS, Bootstrap, PHP, and MySQL.

---

## 5. Application Architecture

The application followed a browser-based client/server model.

### Conceptual Architecture

```text
Customer / Store Employee
          |
          v
     Web Browser
          |
          v
  HTML5 + CSS3 + Bootstrap
          |
          v
      Apache / PHP
          |
          v
      SQL Operations
          |
          v
      MySQL Server
          |
          v
   Customer Records
```

### System Components

**Frontend:** Presents business information, products, privacy information, and customer registration forms.

**Backend:** Processes submitted form data using PHP.

**Database:** Stores and retrieves customer records through MySQL.

**Development Environment:** Uses XAMPP/Apache and local MySQL services.

**Version Control:** GitHub preserves source code and the academic development history.

### Scope

This represents the original academic application architecture.

The 2023 project used local database connectivity.

Cloud migration and Azure-hosted database integration belong primarily to the subsequent PI2 project.

---

## 6. Application Features

The final academic report describes five principal web pages.

### 6.1 Home — `index.html`

The homepage introduced Paió Brechó, its products, and business information.

It included navigation elements and communication features.

### 6.2 About — `sobre.html`

The About page described the store and provided information relevant to customers.

### 6.3 Products — `produtos.html`

The Products page displayed information and imagery associated with merchandise.

The page served as an informational catalog rather than a fully implemented transaction-processing checkout.

### 6.4 Customer Registration — `formulario.php`

The registration page was designed to collect customer information and submit it to the database.

The report documents data fields including:

- Name.
- Email.
- Telephone.
- Sex/gender.
- Date of birth.
- City.
- State.
- Address.

The exact registration schema should be inspected in the current source files.

Modern use should apply data minimization and ensure a valid legal basis for personal data processing.

### 6.5 Privacy Information — `ler_os_termos.html`

The project included a page explaining terms related to the collection and storage of customer information.

This reflected the academic interest in privacy and the Brazilian LGPD.

The presence of a privacy notice does not establish full legal compliance.

---

## 7. Relational Database Design

The project investigated how a small business could persist customer information in a structured relational database.

### Historical Database

The original report identifies a MySQL schema named:

```text
formulario-paio
```

The customer records were stored in a table named:

```text
clientes
```

### Data Flow

```text
Customer Registration Form
          |
          v
       PHP Script
          |
          v
       SQL INSERT
          |
          v
     MySQL Database
          |
          v
   Stored Customer Data
```

### Historical Validation

The report documents:

- Database schema creation.
- MySQL Server configuration.
- PHP database connectivity.
- Submission of registration data.
- Successful retrieval of stored records using MySQL Workbench.

These results establish the functionality demonstrated in the academic environment.

They do not establish production database security, backup policies, or high availability.

---

## 8. Development Environment and Troubleshooting

The original implementation was developed using local web and database services.

### macOS

The team attempted to configure XAMPP, Apache, MySQL Server, and MySQL Workbench on an Apple Silicon Mac.

Database connectivity issues occurred because of service and port configuration conflicts.

### Windows 11

The team subsequently configured a Windows environment.

The report documents MySQL connectivity and successful data submission and retrieval in that environment.

### Engineering Lessons

This process provided practical experience with:

- Local web server configuration.
- Database connectivity.
- Network ports.
- MySQL service configuration.
- Environment compatibility.
- Cross-platform troubleshooting.
- Integration testing.

The original local setup is historical and may require adaptation for current operating systems and software versions.

---

## 9. Frontend Design and Responsiveness

The project developed its interface using HTML5, CSS3, and Bootstrap.

### Interface Components

The documented pages included:

- Headers.
- Navigation menus.
- Content sections.
- Product imagery.
- Buttons.
- Customer registration forms.
- Footer elements.

### Responsive Design

CSS media queries were used to adapt layouts to smaller screens.

### Bootstrap

Bootstrap 5.3 documentation and components were used in frontend development.

The framework supported interface styling and reusable UI patterns.

### Accessibility Scope

The academic objectives included developing a responsive and accessible interface.

However, the report does not establish a comprehensive accessibility audit or independently verified WCAG conformance.

---

## 10. Privacy, Security, and LGPD

The project involved customer registration data.

The academic report explicitly considered Brazil's General Data Protection Law (LGPD).

### Privacy Considerations

The system raised questions related to:

- Collection of personal information.
- Purpose limitation.
- Customer consent and transparency.
- Storage and retrieval of records.
- Confidentiality.
- Data security.
- Legal responsibilities for processing personal data.

### Historical Implementation

A privacy information page was included in the original system.

### Security Limitations

The repository should not be represented as a production-secure system.

Before any reuse, the implementation requires review of:

- Database credentials.
- SQL injection risks.
- Form validation.
- Password handling, if applicable.
- Authentication and authorization.
- Sensitive data in source files.
- Git history.
- Data retention.
- Transport security.

LGPD discussion in an academic report is not equivalent to a formal compliance assessment.

---

## 11. Repository Structure

The historical GitHub repository contains web pages, PHP scripts, styling resources, and development artifacts.

Representative files:

```text
.
├── .idea/
├── css/
├── img/
├── README.md
├── index.html
├── sobre.html
├── produtos.html
├── ler_os_termos.html
├── formulario.html
├── formulario.php
├── formulario original.php
├── formulario - Copia.php
├── config.php
├── select.php
├── info.php
├── tela_de_login.html
└── ...
```

Additional archived files include database screenshots, configuration demonstrations, and experimental materials.

The file names reflect the historical academic repository.

Not every file represents a separate completed application feature.

### Repository Organization

A future maintenance effort should distinguish:

- Application source code.
- Academic documentation.
- Screenshots and media.
- Experimental code.
- Database configuration.
- Local IDE artifacts.
- Sensitive information.

Any cleanup should preserve academic authorship and the historical development record.

---

## 12. Running Locally

### Prerequisites

The original application requires:

- Git.
- PHP.
- Apache or another compatible web server.
- MySQL.
- A supported web browser.

XAMPP was used during the historical development.

### Clone the Repository

```bash
git clone https://github.com/eduardofernandesbueno/univesp-paio-customer-management-2023.git
cd univesp-paio-customer-management-2023
```

These commands assume the proposed repository rename has been completed.

### Static Frontend Preview

For visual inspection of HTML and CSS pages, run:

```bash
python3 -m http.server 8080
```

Open:

```text
http://localhost:8080/
```

This does not execute PHP or connect to MySQL.

### PHP and Database Execution

The complete registration workflow requires a compatible PHP/MySQL environment.

The historical repository includes database-related scripts and configuration files.

Before attempting execution:

1. Review all PHP database configuration files.
2. Ensure no obsolete or exposed credentials are reused.
3. Create a local test database.
4. Use synthetic customer records.
5. Review the database schema.
6. Configure credentials securely.
7. Verify PHP and MySQL compatibility.
8. Test database insertion and retrieval.

The exact setup has not been independently validated against the current branch.

Do not use live customer data or historical production credentials.

---

## 13. Historical Results

The academic report documents the completion of a web-based customer registration prototype.

### Demonstrated Outcomes

- Informational web pages.
- Responsive frontend styling.
- Customer registration form.
- PHP form processing.
- MySQL schema creation.
- Successful local database connection.
- Customer data insertion and retrieval.
- Browser-based testing.
- Academic technical documentation.

### Significance

These results represent the initial implementation of a database-backed web application for a real small-business problem.

The later PI2 and PI3 projects extended the original work into cloud integration and mobile-oriented application development.

### Limitations

The original implementation did not establish:

- A production-ready CRM.
- A complete e-commerce checkout system.
- Cloud database hosting.
- Automated inventory management.
- Production-grade authentication.
- Comprehensive automated tests.
- Verified WCAG compliance.
- Independently certified LGPD compliance.

---

## 14. Software Engineering Methodology

The project used a qualitative and descriptive research approach.

### Design Thinking

The team investigated the business problem through stakeholder engagement and empathetic listening.

### Requirements Discovery

Questionnaires and interviews were used to identify the business's needs.

### Prototyping

The team developed web pages and database-related components incrementally.

### Implementation

HTML, CSS, Bootstrap, PHP, and MySQL were integrated to demonstrate the proposed solution.

### Evaluation

The application was tested in browsers and through database connectivity experiments.

### Documentation

The project was reported in a technical-scientific academic document.

---

## 15. Academic Continuity — PI1, PI2, and PI3

The Paió project evolved across three UNIVESP academic stages.

### PI1 — 2023

**Foundation:**

- Initial web application.
- Frontend development.
- Local PHP/MySQL integration.
- Customer registration.
- Relational data persistence.
- Privacy-related documentation.

### PI2 — 2023

**Extension:**

- Code reuse and refactoring.
- Frontend improvements.
- Additional JavaScript functionality.
- Remote database integration.
- Microsoft Azure deployment.
- Accessibility assessment.
- API experimentation.

### PI3 — 2024

**Further Development:**

- Mobile web application.
- PWA components.
- Additional cloud integration.
- CI/CD experimentation.
- Software testing.
- Web analytics.

The three phases should be documented separately to preserve their respective academic contributions.

---

## 16. Academic Contributors

**Original Title:** *Desenvolvimento de um sistema web para a gestão de clientes de uma loja*

**Institution:** Virtual University of the State of São Paulo (UNIVESP)  
**Year:** 2023  
**Academic Project:** Integrative Project I

### Project Team

- Cristiano Manoel dos Santos
- Débora Cristina Gonçalves dos Santos
- Eduardo Fernandes Bueno
- Raquel Virginia Papini de Lucena Oliveira

**Academic Tutor:** Leonardo Richeli Garcia

### Attribution

This project was developed collaboratively.

Eduardo Fernandes Bueno maintains this GitHub repository as part of his professional and academic portfolio.

Repository ownership does not imply exclusive authorship of the original project.

All original contributors retain appropriate academic attribution.

---

## 17. Professional Context — Eduardo Fernandes Bueno

Eduardo Fernandes Bueno is a Data Engineer, Data Scientist, and M.Sc. candidate in Computer Science at the State University of Londrina (UEL), Brazil.

He contributes to Research & Development activities at UEL's Information Technology Office (**ATI/UEL**).

His broader technical and academic interests include:

- Data Engineering.
- Data Architecture.
- Software Engineering.
- Data Science.
- Machine Learning.
- Data Governance.
- Data Integration.
- Applied Research.
- Responsible AI.
- Privacy and Regulatory Compliance.

His academic background includes Information Technology, Data Science, and Law.

### Institutional Clarification

This repository documents undergraduate academic work completed at UNIVESP in 2023.

Eduardo's later affiliation with ATI/UEL is included for professional context only.

The project was not an official ATI/UEL or UNIDATA software deliverable.

---

## 18. Security and Repository Maintenance

Because the repository contains historical PHP and database-related files, a security review is recommended before further public promotion.

### Priority Files

```text
config.php
formulario.php
formulario original.php
formulario - Copia.php
select.php
info.php
```

These files should be inspected for:

- Embedded passwords.
- Database connection details.
- Personal data.
- Insecure SQL handling.
- Debug output.
- Legacy development configuration.

The repository also includes a historical `bfg.jar` file, whose purpose and provenance should be reviewed before retention or execution.

Do not execute unfamiliar binary files solely because they are present in a repository.

### Historical Git Commits

Removing a secret from the current working tree does not necessarily remove it from earlier Git history.

Any verified secret exposure should be addressed through credential revocation or rotation and an appropriate repository remediation process.

---

## 19. Future Improvements

Potential future work includes:

- Improving source-code organization.
- Replacing hardcoded database configuration.
- Introducing secure environment variables.
- Applying prepared SQL statements.
- Strengthening backend input validation.
- Implementing proper authentication where needed.
- Adding automated testing.
- Improving accessibility.
- Documenting database schema and migrations.
- Creating a reproducible development environment.
- Building a static demonstration using synthetic data.
- Modernizing dependencies.
- Reviewing application privacy requirements.

These are proposed improvements, not completed functionality.

---

## 20. Academic Reference

SANTOS, Cristiano Manoel dos; SANTOS, Débora Cristina Gonçalves dos; BUENO, Eduardo Fernandes; OLIVEIRA, Raquel Virginia Papini de Lucena. *Desenvolvimento de um sistema web para a gestão de clientes de uma loja*. Technical and Scientific Report, Integrative Project I, Virtual University of the State of São Paulo (UNIVESP), 2023.

**Academic Tutor:** Leonardo Richeli Garcia.

**Project Presentation:**

https://youtu.be/wp8_hPguMc8

This is an undergraduate academic project report, not a peer-reviewed journal or conference publication.

---

## 21. Licensing and Responsible Reuse

Public access to this repository does not automatically grant unrestricted reuse rights over every file, third-party image, academic document, or business asset.

Any licensing decision should respect the rights of the original project contributors.

Customer information, credentials, and sensitive data must not be redistributed.

---

## 22. Professional Links

**Eduardo Fernandes Bueno**

- **GitHub:** https://github.com/eduardofernandesbueno
- **Professional Portfolio:** https://eduardofernandesbueno.github.io/
- **LinkedIn:** https://www.linkedin.com/in/eduardofernandesbueno/
- **ORCID:** https://orcid.org/0009-0000-8620-0211
- **Curriculum Lattes:** http://lattes.cnpq.br/8716619580595259

---

## 23. Project Summary

Paió Brechó — Integrative Project I documents the initial development of a customer management web application using HTML5, CSS3, Bootstrap, PHP, SQL, and MySQL.

Its technical contributions include:

**Frontend Development:** Web pages, forms, navigation, responsive layouts, and Bootstrap components.

**Backend Development:** PHP form processing and relational database interaction.

**Database Engineering:** MySQL schema design, data insertion, retrieval, and local database configuration.

**Software Engineering:** Requirements analysis, iterative prototyping, integration testing, and source versioning.

**Data Governance:** Initial consideration of privacy, personal data collection, and Brazilian LGPD requirements.

**Applied Research:** Design Thinking, stakeholder interviews, questionnaires, and technical-scientific documentation.

The project formed the foundation for subsequent UNIVESP Integrative Projects II and III.

Its value is the documented implementation of an end-to-end academic web prototype and the practical experience gained integrating browser interfaces, server-side processing, and relational data persistence.

---

**UNIVESP — Integrative Project I, 2023**

*HTML5 · CSS3 · Bootstrap · PHP · MySQL · SQL · Software Engineering*

**Collaborative academic project maintained by Eduardo Fernandes Bueno — currently R&D at ATI/UEL, Brazil.**
