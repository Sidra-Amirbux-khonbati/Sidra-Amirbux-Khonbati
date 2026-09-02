```markdown
<div align="center">

# 👋 Hi, I'm Sidra Amirbux Khonbati

### Software Engineering Student | Mobile & Backend Developer | AI Integration

<p>
  <a href="https://github.com/Sidra-Amirbux-Khonbati">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="mailto:sidraamirbux@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/sidra-amirbux-khonbati-992b9833b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&center=true&vCenter=true&width=750&lines=Designing+Scalable+Backend+Systems;Building+Cross-Platform+Mobile+Apps+(Flutter);Optimizing+PostgreSQL+Queries+%26+Database+Schemas;Integrating+AI+Pipeline+Workflows;Event-Driven+Architectures+%26+RESTful+Services"/>

</div>

---

## ⚙️ System Execution Pipeline

I focus on building software architectures by prioritizing loose coupling, transaction integrity, and predictable response execution across the stack:

```text
[ Client Requests ] ──(REST/JSON)──> [ Node.js Controller Layer ]
                                            │
                                  ┌─────────┴─────────┐
                                  ▼                   ▼
                           [ Middleware ]     [ Service Domain ]
                       (JWT Auth / Validation)       │
                                                      ▼
                                              [ ORM / Query Layer ]
                                                      │
                                                      ▼
                                             [ PostgreSQL Engine ]
                                        (ACID Transactions / Indexing)

```

---

# 🚀 Engineering Projects

## 🏦 Finova — Digital Banking & Transaction Engine

A full-stack fintech platform designed around transactional consistency, secure balance operations, and decoupled notification pipelines.

**Tech Stack:** `Flutter` `Node.js` `Express.js` `PostgreSQL` `REST API`

**Key Engineering Implementations:**

* **Transactional Integrity:** Implemented explicit ACID-compliant database transactions in PostgreSQL to prevent race conditions during concurrent balance transfers.
* **Security Architecture:** Engineered stateless authentication using JWT with encrypted token persistence and role-based access control (RBAC).
* **Asynchronous Processing:** Built background email/SMS notification dispatchers to keep API endpoints non-blocking during transaction completions.
* **Reporting Engine:** Designed stream-based PDF invoice rendering for instant utility bill payment receipts.

**Architecture Flow:**

```text
Flutter Mobile App
       │
       ▼
  REST API (JWT)
       │
       ▼
 Node.js / Express
       │
       ▼
 PostgreSQL DB (ACID Transactions)
       │
       ├── Accounts & Auth
       ├── Ledger & Balances
       ├── Transfer Queue
       └── Utility Receipts

```

---

## 📄 OCR Account Opening System

An automated document processing pipeline that parses unstructured scanned onboarding forms into validated relational database entities.

**Tech Stack:** `Node.js` `Express.js` `Tesseract.js` `PostgreSQL` `Regex / Parsing`

**Key Engineering Implementations:**

* **Multi-Stage Extraction Pipeline:** Designed an ingestion queue that converts incoming PDFs to optimized image binaries for OCR processing.
* **Pattern Matching Engine:** Developed regex-based field resolution algorithms to parse raw OCR output into structured JSON payloads.
* **Data Normalization:** Automated entity mapping to auto-populate relational schemas and reduce manual entry errors.

```text
[ Binary Stream Input ] ➔ [ Image Preprocessing ] ➔ [ Tesseract Engine ]
                                                          │
                                                          ▼
[ SQL Storage Layer ] 🛢️ 🔒 [ Schema Sanitizer ] 🧠 ⬅️ [ Regex Parser ]

```

---

## 🧮 Batch-Wise Academic Analytics Engine

A relational database system optimized for multi-term GPA tracking, dynamic aggregate indexing, and batch-level academic metrics.

**Tech Stack:** `PostgreSQL` `Relational Database Design` `Advanced SQL`

**Key Engineering Implementations:**

* **Complex Query Optimization:** Authored parameterized SQL aggregate queries using Common Table Expressions (CTEs) and window functions (`AVG() OVER`) to calculate batch rankings without application-level overhead.
* **Database Normalization:** Designed schema architectures normalized to 3NF to eliminate redundant record propagation across academic departments.

---

## 🎮 Logic & Systems Projects

Smaller projects built to apply core programming logic, algorithms, and modular design.

| Project | Core Engineering Focus |
| --- | --- |
| 🎮 Tic Tac Toe | Object-Oriented Design & Game State Evaluation (Java) |
| ✊ Rock Paper Scissors | Control Flow Logic & State Machine Rules (Java) |
| 🧮 Responsive Calculator | DOM Event Dispatching & Computational Logic (JS) |
| 👥 HR Management System | Data Structures & Entity Operations Management |

---

# 🧰 Technical Arsenal

### Languages & Frameworks

### Databases & Infrastructure

---

# 📊 Activity & Metrics





---

# 💼 Professional Experience

* **Information Technology Intern | HBL**
* Gained hands-on experience with enterprise banking operations, backend compliance workflows, and enterprise IT infrastructure maintenance.


* **Front-End Developer Intern | Apexcify Technologies**
* Engineered responsive client-side UI components and optimized state rendering performance across web platforms.


* **C Programming Intern | Centura**
* Developed algorithmic scripts and memory-efficient data manipulation utilities using standard C library functions.


* **Software Development Intern | Skills4U**
* Contributed to full-lifecycle software execution, code refactoring, and team-based version control practices.



---

# 🎯 Engineering Focus & Roadmap

* **Backend Architecture:** Advanced Java concurrency models, REST API performance tuning, and microservices design principles.
* **Database Systems:** Indexing strategies, execution plan optimization, and schema normalization.
* **AI Integration Pipeline:** Incorporating OCR engines, LLM orchestration, and vector context integration into production APIs.

---

# 📫 Connect With Me





### Driven by system efficiency, clean abstractions, and robust software architecture. 🚀
