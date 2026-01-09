# Hi, I'm Erwin Wilson Ceniza

💻 **Full Stack Software Developer** with over **𝟭𝟬 years** of experience designing, developing, and deploying robust **Line of Business (LOB)** applications and **ERP solutions**.  

I specialize in **ASP.NET Core MVC, C#, MS SQL Server** and modern frameworks like **Blazor, React, Flutter, and .NET MAUI**.
My focus is on **Full Stack Development**, **automation**, and **AI integration** to solve complex problems and deliver scalable, secure, and intelligent solutions.

---

## 📦 Commercialized Projects Developed

### 👨‍💼 Cloud HRIS (2020)
A comprehensive, cloud-native Human Resources and Payroll management system designed to automate and streamline core HR operations from recruitment to retirement. The platform enhances security and efficiency with biometric integration and provides employees with modern, accessible tools.

* **Key Features**:
    * **Intelligent Payroll & Timekeeping**:
        * **Automated DTR Calculation**: Seamlessly processes Daily Time Records (DTR) by automatically calculating work hours, undertime, and tardiness based on facial recognition check-ins.
        * **Dynamic Payroll Engine**: Handles complex calculations for salaries, overtime, night differentials, and holiday pay. It also manages a wide range of deductions (government contributions, loans, cash advances) and other income sources (bonuses, commissions), ensuring accuracy and compliance.
        * **Integrated Leave Management**: Automatically factors approved leaves (sick, vacation, etc.) into payroll computations.
    * **Facial Recognition Timekeeping**: Utilizes AI-powered facial recognition for secure, touchless employee check-ins, eliminating buddy-punching and providing real-time data for DTR and payroll.
    * **Employee Self-Service (ESS) Portal**: A cross-platform mobile app empowering employees to view payslips, file for leaves and overtime, and update their personal information anytime, anywhere.
    * **Multilingual AI Chatbot**: Provides instant, 24/7 support for common HR queries, reducing the administrative load on HR personnel.

**Tech Stack:** ASP.NET Core, MAUI.NET, SQL Server, OpenCV, Telerik, DevExpress, FaceNet  

🔗 [GitHub Repo](https://github.com/ewceniza9009/litestaff)

### 🏢 NexPoint CRM (2026)
An industry-grade, monolithic Customer Relationship Management system designed for scalability, security, and user cohesion. It leverages a modern technology stack to provide a comprehensive solution for managing customer interactions, sales pipelines, marketing campaigns, and support tickets.

* **Key Features**:
    * **Customer 360**: Comprehensive view of customer profiles, contacts, and interaction history.
    * **Sales Pipeline**: Drag-and-drop opportunity management, lead scoring (Einstein Scoring), and sales forecasting.
    * **Marketing & Support Hub**: Automated campaign management and a robust ticketing system with priority-based handling.
    * **Real-time Analytics**: Interactive dashboards and instant notifications powered by SignalR.

**Tech Stack:** ASP.NET Core 10, EF Core, PostgreSQL, Angular 20, Tailwind CSS, MediatR, SignalR, Docker

🌐 [Demo Site](https://nex-point.vercel.app/)
🔗 [GitHub Repo](https://github.com/ewceniza9009/NexPoint)

### 📦 CloudPallet - 3PL Cold Storage WMS (SaaS)

A specialized Warehouse Management System (WMS) built for the unique complexities of **Third-Party Logistics (3PL) cold storage**. This project tackles critical requirements like real-time temperature monitoring, perishable lot/batch tracking (FEFO), and precise, hierarchical location management (Warehouse > Room > Bay > Row > Column > Level).

Beyond simple tracking, CloudPallet provides a robust, **event-driven 3PL billing engine** to automatically calculate client charges for storage (tiered by temperature), handling, and value-added services (like blasting, kitting, and fumigation). It features automated receiving with scale integration, on-the-fly SSCC pallet barcode generation, and barcode-enforced picking/shipping workflows to minimize errors.

The system is built on a modern, decoupled architecture using **Domain-Driven Design (DDD)**, **CQRS**, and Clean Architecture principles for high scalability. It also includes comprehensive **Role-Based Access Control (RBAC)** (with Admin, Operator, and Finance roles) and uses **SignalR** for live dashboards tracking dock status and room temperatures.

**Tech Stack:**
* **Backend:** ASP.NET Core 9, EF Core 9, & SQL Server
* **Frontend:** Angular 20 & Angular Material
* **Architecture:** MediatR (for CQRS), AutoMapper
* **Performance:** StackExchangeRedis (Caching)
* **Real-time:** SignalR (Live Dashboards & Notifications)
* **Reporting:** QuestPDF (PDF Invoice/Report Generation)
* **Security:** JWT & ASP.NET Core Identity (RBAC)

🔗 [GitHub Repo](https://github.com/ewceniza9009/cloudpallet)

### 🛒 drobble - Ecommerce (SaaS) 

Drobble is a modern, scalable e-commerce platform leveraging a microservices architecture built with **ASP.NET Core (.NET 8/9+)**. It features modular services including a **Product Catalog** (MongoDB with change streams), **User Management** (PostgreSQL with MFA support), **Order Management** (PostgreSQL), **Payment** (Stripe, PayPal, Apple Pay), **Search** (Elasticsearch), and **Reviews** (MongoDB with moderation). These services are orchestrated via an **Ocelot API Gateway** and use **RabbitMQ** for event-driven communication.

The frontend is a **React 19+ SPA** (PWA-enabled), built with Vite, TypeScript, and Tailwind CSS. Global state is managed by **Redux Toolkit**, with **RTK Query** handling all API data fetching, caching, and invalidation.

Fully containerized with **Docker** and optimized for Kubernetes deployment, the platform adheres to **Clean Architecture** and **CQRS** patterns. It ensures reliability with robust security (JWT, rate limiting, OWASP compliance) and production-grade observability via OpenTelemetry. This project serves as a comprehensive, production-ready blueprint for a high-performance e-commerce solution.

**Tech Stack:**
#### Backend
* **Framework:** ASP.NET Core (targeting .NET 8/9+)
* **Architecture:** Microservices, Domain-Driven Design (DDD), Clean Architecture, and CQRS (using MediatR)
* **API Gateway:** Ocelot
* **Asynchronous Communication:** RabbitMQ, likely using MassTransit
* **Authentication:** JWT (JSON Web Tokens)
* **Validation:** FluentValidation
* **Observability:** OpenTelemetry, Serilog (for structured logging)
* **Resiliency:** Polly (for retries and circuit breakers)
* **API Documentation:** Swashbuckle (Swagger)

#### Frontend (react-spa)
* **Framework/Library:** React (`^18.3.1`)
* **Build Tool:** Vite
* **Language:** TypeScript
* **Styling:** Tailwind CSS
* **State Management:** Redux Toolkit (`^2.2.5`)
* **Data Fetching:** RTK Query (via `@reduxjs/toolkit`)
* **Routing:** React Router (`^6.23.1`)
* **HTTP Client:** Axios (`^1.7.2`)
* **UI Components:** `react-icons`, `react-slick`, `react-hot-toast`

#### Databases & Infrastructure
* **Containerization:** Docker
* **Orchestration:** Kubernetes (planned)
* **Databases:**
    * PostgreSQL (v16+) (Used for User Management, Order Management, Payment)
    * MongoDB (v7.0) (Used for Product Catalog, Shopping Cart, Reviews & Ratings)
    * Elasticsearch (v8.14.1) (Used for Search & Discovery)
* **Caching:** Redis (for API Gateway caching and rate limiting)
* **Local Logging:** Seq

🔗 [GitHub Repo](https://github.com/ewceniza9009/drobble)

### 💰 Cloud FMIS (2019)

An integrated Financial Management and Information System built to serve as the **single source of truth** for trading and manufacturing businesses. It centralizes financial data to provide a real-time, 360-degree view of the company's financial health.

  * **Key Features**:
      * **Core Accounting Modules**: Includes General Ledger, Accounts Payable, and Accounts Receivable to manage day-to-day financial transactions.
      * **Inventory & Cost Control**: Specifically designed for trading and small sized production with features for robust inventory management & reporting, raw material costing, and finished goods valuation.
      * **Financial Reporting**: Generates critical financial statements like Balance Sheets, Income Statements, and Cash Flow Statements with robust reporting tools.
      * **Sales & Purchasing Workflows**: Manages the entire order-to-cash and procure-to-pay cycles, from purchase orders and sales invoicing to payment processing.

**Tech Stack:** ASP.NET MVC, SQL Server, Telerik Reports

### 🏦 Cloud Loan (2022)

An end-to-end platform that automates the entire loan lifecycle, from initial application to final settlement. Built with a modern Blazor front-end, it offers a rich, interactive user interface for loan officers and administrators to manage portfolios with greater efficiency and transparency.

  * **Key Features**:
      * **Loan Origination & Underwriting**: Streamlines the application process with digital forms, credit scoring, and automated approval workflows.
      * **Portfolio Management**: Provides a centralized dashboard to monitor active loans, payment schedules, and delinquencies.
      * **Automated Servicing**: Manages automated billing, payment collection, and amortization schedule calculations.
      * **Reporting & Analytics**: Delivers detailed insights into portfolio performance, risk exposure, and collection effectiveness.

**Tech Stack:** Blazor.NET, SQL Server, Syncfusion, DevExpress

### 🛍 POS System (2023)

A modern, cross-platform Point-of-Sale (POS) system engineered for retail and F&B environments. Its hybrid architecture ensures **uninterrupted sales** even with unstable internet, making it highly reliable for dynamic business operations.

  * **Key Features**:
      * **Real-Time Data Synchronization**: Leverages SignalR for instant updates on sales, inventory levels, and customer data across all terminals and the back-end server.
      * **Inventory Management**: Features real-time stock tracking, low-stock alerts, and purchase order management directly from the POS interface.
      * **Cross-Platform by Design**: Built with Flutter, the front-end runs natively on iOS, Android, Windows, and web from a single codebase.

**Tech Stack:** Flutter/Dart, ASP.NET Core, SQLite, SignalR  

🔗 [GitHub Repo](https://github.com/ewceniza9009/pos24)

---

## 🚀 Emerging Initiatives

### 📹 gstream - Video Streaming

A high-performance, scalable video streaming backend designed for **low-latency** delivery. This initiative explores modern real-time communication protocols to build a foundation for interactive applications like live auctions, virtual events, and remote monitoring, powered by the latest in .NET.  

**Tech Stack:** ASP.NET MVC Core, EF Core, Tailwind CSS, Javascript(Front End), Redis, WebRTC, LiveKit(Docker Hosted for development), SignalR(For Live Chat), JWT Authentication 

🔗 [GitHub Repo](https://github.com/ewceniza9009/gstream)

### 📹 iVA (Intelligent Video Analysis)

An AI-driven service that transforms raw video feeds into **structured, actionable data**. Moving beyond simple surveillance, iVA aims to provide contextual understanding by detecting objects, reading text (OCR), and identifying patterns, enabling applications in retail analytics, industrial automation, and smart security.  

**Tech Stack:** ASP.NET MVC Core, EF Core, Tailwind CSS, Javascript(Front End), SignalR(For Video Bit Transmission), ONNXRuntime, OpenCVSharp, Gemini API, JWT Authentication 

🔗 [GitHub Repo](https://github.com/ewceniza9009/iVA)

### 🧠 Dev2ndBrain - Development Tools

A personalized knowledge management system or "Second Brain" built specifically for developers. The goal is to create a central hub for organizing code snippets, architectural notes, terminal commands, and technical documentation, helping to combat information overload and accelerate project development.  

**Tech Stack:** ASP.NET Core, OctoKit(For Github Gist), Roslyn(For C# SandBox), React + Vite + TypeScript + Tailwind CSS, Babel(For React TSX SandBox), Monaco(For Notes and Snippets Editor), React-Flow(For Graphs), MiniSearch, DexieJS, Zustand(State Management), Electron, Docker(Development Testing)

🔗 [GitHub Repo](https://github.com/ewceniza9009/Dev2ndBrain)

---

## 💻 Tech Stack
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-512BD4?style=for-the-badge&logo=windows&logoColor=white)
![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Xamarin](https://img.shields.io/badge/Xamarin-3498DB?style=for-the-badge&logo=xamarin&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Dapper](https://img.shields.io/badge/Dapper-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Telerik](https://img.shields.io/badge/Telerik-00B140?style=for-the-badge&logo=telerik&logoColor=white)
![DevExpress](https://img.shields.io/badge/DevExpress-FF7200?style=for-the-badge&logo=devexpress&logoColor=white)
![Syncfusion](https://img.shields.io/badge/Syncfusion-FFB400?style=for-the-badge&logo=syncfusion&logoColor=black)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

---

## 📊 GitHub Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ewceniza9009&show_icons=true&theme=dark&hide_border=true&count_private=true" height="180px"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ewceniza9009&layout=compact&theme=dark&hide_border=true" height="180px"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=ewceniza9009&theme=dark&hide_border=true" height="180px"/>
</p>
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ewceniza9009&theme=dark&no-frame=true&margin-w=5&margin-h=5" height="180px"/>
</p>

---

## 🌐 Connect with Me
[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=for-the-badge)](https://ewceniza23.bsite.net/)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/erwin-wilson-ceniza-1b42ba32/)  
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ewceniza90)  

📧 **Email:** [erwinwilsonceniza@gmail.com](mailto:erwinwilsonceniza@gmail.com) | [erwinwilsonceniza@yahoo.com](mailto:erwinwilsonceniza@yahoo.com)

---

> _“The best thing about a boolean is even if you are wrong, you are only off by a bit.” – Anonymous_
