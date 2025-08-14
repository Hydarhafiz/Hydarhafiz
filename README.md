## About Me
I am a passionate and skilled web designer and developer with experience in various technologies and platforms. My expertise includes:

- **Web Design**: Creating intuitive and visually appealing designs using Figma.
- **Web Development**: Building robust and scalable applications using the MEAN stack (MongoDB, Express.js, Angular, Node.js) and PHP.
- **Version Control**: Proficient in using GitHub, Git, and Azure DevOps for efficient version control and collaboration.
- **Data Analysis**: Analyzing and visualizing data using Python and Microsoft Power BI.
- **Database Management**: Experienced in working with MySQL and MongoDB databases.

## Past Projects

### **Prescriptive Analytics for Saline Aquifer Storage Detection (Jan 2025 - Aug 2025)** **(Private)**

#### **Introduction**
This project developed an AI-driven prescriptive analytics framework to identify optimal carbon capture and storage (CCS) locations in deep saline aquifers. The solution integrates modern AI/ML technologies to transform complex geological data into actionable insights for both technical and non-technical stakeholders, contributing to global climate change mitigation efforts.

#### **Technologies Used**
- **Frontend:** React + Vite, TypeScript
- **Backend:** Python, FastAPI
- **Databases:** Neo4j (Graph Database), PostgreSQL
- **AI/ML:** qwen2.5-coder:7b, llama3:8b, K-means Clustering, SHAP (SHapley Additive exPlanations)
- **Conatinerization:** Docker, Docker Compose

#### **Key Features**
- **Full-Stack AI/ML Application:** Designed and built an end-to-end system with a web-based chatbot interface and a robust Python backend.
- **Integrated LLM Framework:** Utilized qwen2.5-coder:7b to translate natural language queries into executable Neo4j database queries and llama3:8b to generate insightful, analytical responses.
- **Knowledge Graph and ML Engine:** Preprocessed over 100,000 geological records into a Neo4j knowledge graph. An ML-driven recommendation engine using K-means clustering was implemented, with SHAP values used to optimize parameters and enhance recommendations.
- **Containerized Deployment:** The entire application was containerized using Docker and Docker Compose, ensuring the system's portability, scalability, and ease of deployment.
- **User Validation:** The system's effectiveness was confirmed through User Acceptance Testing (UAT) with domain experts from Petronas Research Sdn Bhd (PRSB).

***

### Vibe Coder: A Full-Stack AI Coding Assistant Prototype

#### Introduction
Vibe Coder is a full-stack, AI-powered coding assistant prototype designed to streamline the software development workflow. Developed in just two weeks, this project showcases the integration of local large language models (LLMs) into a practical application. Users can interact with the system via a web-based chat interface to generate code and receive automated, expert-level analysis. The architecture is built for privacy and performance, with the AI models running locally on a dedicated environment with GPU acceleration.


#### Technologies Used

* **Frontend**:
    * **React** and **Vite** for a modern, component-based user interface.
    * **TypeScript** for enhanced code quality and maintainability.
    * **Tailwind CSS** for rapid and responsive styling.
    * **Ace Editor** to provide a feature-rich, integrated code editor.

* **Backend**:
    * **FastAPI** for a high-performance, Python-based API.
    * **SQLAlchemy** as the Object-Relational Mapper (ORM) for database interactions.
    * **PostgreSQL** as the relational database for storing project data and chat history.

* **AI & Infrastructure**:
    * **Ollama**: A framework for running large language models locally.
    * **Qwen**: The LLM used for code generation and modification tasks.
    * **Llama**: The LLM used for providing detailed code analysis and suggestions.
    * **WSL2 (Windows Subsystem for Linux)**: The local environment for running the AI infrastructure with access to the host machine's GPU.
    * **Docker**: Used for containerization to simplify the setup and deployment of services.

### Key Features

* **Multi-Model AI Workflow**: The system orchestrates a sophisticated, two-step AI process. It uses a code-generation-optimized model (Qwen) to produce the code and then passes the result to a specialized analysis model (Llama) to provide constructive feedback, all from a single user prompt.
* **Integrated Code Generation & Analysis**: A seamless user experience where a single chat request not only generates code but also provides a comprehensive review of that code, simulating a virtual pair programming session.
* **Local AI Infrastructure**: All AI computations are performed on a local machine, ensuring **complete data privacy** as no sensitive code or data is sent to external cloud services. The use of **WSL2** with GPU passthrough enables high-speed processing.
* **Scalable Architecture**: The FastAPI backend is designed as a central API gateway, providing a clear separation of concerns. The **PostgreSQL** database schema is structured to support project and message data, making it easy to scale the application.

***

## **Organizational Workspace System (OWS) (Jan 2024 - Aug 2024)** **(Private)**

### Introduction
This project focuses on developing and deploying a booking system prototype using the MEAN stack (MongoDB, Express.js, Angular, Node.js) and the Ionic framework. The primary objective is to provide training and onboarding for new staff and interns at Petronas Digital Sdn Bhd, exposing them to the MEAN stack and Ionic framework.

### Technologies Used
- MEAN stack
- Ionic framework

### Features

#### Admin Website using Angular
- Develop a robust and user-friendly administration website using Angular.
- Enable admin users to manage desk bookings across multiple office floors.
- Implement CRUD operations, data fetching, display functionalities, and an intuitive user interface.

#### Staff App using Ionic
- Develop a mobile application for desk booking, ensuring convenience and accessibility for users.
- Include features such as desk booking, QR code scanning for desk check-ins, booking history, and a user profile page.
- Allow users to book desks using their mobile phones, providing a fast and convenient solution.

***

## LeaveSmart Website Project (June 2023 - Feb 2024) **(Public)**
Collaborated with Double Bubble Enterprise to develop LeaveSmart, a web-based application for streamlining leave management processes in companies of all sizes. Built using Angular, PHP, and MySQL, LeaveSmart offers a user-friendly interface for employees and administrators.

**Key Features**:
- **LeaveSmart Client**: Enables employees to manage their leave balances, view current leave requests, and submit new leave applications.
- **LeaveSmart Admin**: Provides administrators with tools to manage company leave policies, create employee accounts, approve or reject leave requests, and generate leave reports.
