# LibriDigital: Digital Library Management 📚

![LibriDigital System Logo](./img/Sistema-LibriDigital-Logo-4.png)

## 📖 Overview

**LibriDigital** is an information system proposed to modernize the library of the Escola Superior AprendeMais. The project aims to replace manual processes with an integrated digital solution, improving operational efficiency and the experience for users such as students, teachers, and researchers.

This web page was developed as part of the evaluation for the Introduction to Informatics course.

## 🎯 The Problem

The library faced several challenges that limited its potential:

- **📝 Manual Processes:** Loan and return management was paper-based, prone to errors and inefficiencies.
- **🌐 No Online Catalog:** Users had difficulty searching the collection remotely.
- **💾 Lack of Digitization:** Important works were not accessible in digital format or indexed for searching.
- **🔄 No Integration:** Lack of connection with the academic database, resulting in duplicated work.

## ✨ The Proposed Solution

To overcome these challenges, **LibriDigital** implements an architecture based on robust, low-cost, open-source technologies.

The core of the system is **Koha**, a world-renowned Integrated Library System (ILS), running on an **Ubuntu** server with a **PostgreSQL** database.

### Key Features

- **🖥️ Digitization and OCR:** Use of **Tesseract OCR** to digitize physical documents, allowing full-text search.
- **💳 Automated Management:** Loans, reservations, and returns are managed centrally and automatically.
- **✔️ Access Control with RFID:** Automation of attendance and library entry records.
- **💻 Query Terminals:** Provision of computers for accessing the catalog and printing.
- **🔗 Academic Integration:** Synchronization with the student database via a **REST API**.

## 🛠️ Technologies and Architecture

The project is based on a combination of carefully selected software and hardware to optimize performance and minimize costs:

- **Software:**
  - **Operating System:** Ubuntu Server
  - **Integrated Library System (ILS):** Koha
  - **Database:** PostgreSQL
  - **Optical Character Recognition (OCR):** Tesseract
- **Hardware:**
  - **Server:** Fujitsu Primergy TX1310 M5
  - **Scanner:** Epson Perfection V39II
  - **Client Terminals:** HP OmniDesk Slim

## 📊 Comparative Analysis

The choice of **Koha** was justified by an analysis that compared it with other market solutions like Alexandria (paid, less flexible) and Pergamum (robust, but proprietary and expensive). Koha stood out for being **free, flexible, and maintained by an active global community**.

## 💰 Cost Analysis

The total estimated investment for the hardware infrastructure implementation is **€1,758.82**, a competitive value that ensures the project's financial sustainability. The main software (Koha) has no licensing costs.

## ✅ Advantages and Risks

| Advantages 👍                                                              | Disadvantages 👎                                                    |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| Immediate reduction in licensing costs.                                  | Need for technical knowledge for installation and maintenance.   |
| High flexibility for customization and integrations (OCR, SIP2, etc.).   | Support depends on the community, with no guaranteed response times. |
| Scalable solution, optimized for 100 to 500 users.                 | Hiring professional support may lead to additional costs. |
| Open-source ecosystem that promotes continuous innovation.             |                                                                    |

### 🛡️ Risk Mitigation

To minimize the disadvantages, the following actions were proposed:
- Develop a preventive maintenance plan.
- Train the internal team to manage the system.
- Consider hiring specialized technical support if necessary.
- Plan progressive hardware upgrades to ensure scalability.

## 🏁 Conclusion

**LibriDigital** is a technically and economically advantageous solution that meets all functional requirements for the library's modernization. Its open and low-cost initial architecture ensures a high return on investment and prepares the institution for the digital future.

## 👨‍💻 Authors

This work was carried out as part of the Introduction to Informatics course by:
- Marcos Marcelo Assis Nunes – 33417
- Pedro Miguel Gomes - 33628
- Raquel Vaz Guerreiro - 33559
- Bernardo Miguel Vieira - 33676

**Instructors:** Raquel Sebastião and Manuel Lopes.