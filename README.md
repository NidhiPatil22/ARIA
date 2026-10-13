# ARIA — AI-Powered Government Scheduling Assistant

**ARIA** is an AI-powered scheduling and productivity system designed to simplify schedule management, task coordination, and access to government-related information. It integrates Retrieval-Augmented Generation (RAG) with a vector database to retrieve relevant information and provide context-aware responses, while JWT authentication and role-based access control help secure the system and manage user permissions.

🔗 **Live Demo:** https://aria-two-mu.vercel.app/
💻 **GitHub Repository:** https://github.com/NidhiPatil22/ARIA

## Overview

Managing schedules, deadlines, tasks, and administrative information can become complex, particularly in structured government workflows. ARIA aims to make these processes more accessible through an AI-assisted interface that combines intelligent information retrieval with secure user access.

The project brings together AI-driven retrieval, backend APIs, and authentication mechanisms to create a more organized and secure scheduling experience.

## Key Features

* **AI-Powered Assistance:** Helps users interact with the system and access relevant scheduling and administrative information.
* **Retrieval-Augmented Generation (RAG):** Combines information retrieval with generative AI to produce responses grounded in relevant retrieved context.
* **Vector Database Integration:** Enables semantic retrieval of relevant information based on the meaning of a query rather than relying solely on exact keyword matches.
* **JWT Authentication:** Uses JSON Web Tokens to support authenticated access to protected resources.
* **Role-Based Access Control (RBAC):** Organizes permissions according to user roles, restricting access to authorized functionality.
* **Scheduling and Task Management:** Focuses on organizing schedules, tracking deadlines, and making administrative workflows easier to manage.
* **Web-Based Interface:** Provides an accessible frontend connected to backend functionality through APIs.

## Technical Stack

| Component                  | Technologies                         |
| -------------------------- | ------------------------------------ |
| Frontend                   | Next.js, TypeScript, JavaScript      |
| Backend                    | Python, Next.js API routes           |
| AI / Information Retrieval | Retrieval-Augmented Generation (RAG) |
| Semantic Search            | Vector database                      |
| Authentication             | JWT                                  |
| Authorization              | Role-Based Access Control (RBAC)     |
| Deployment                 | Vercel                               |

*Note: The exact RAG framework, vector database provider, and individual backend libraries can be added once the implementation details are finalized.*

## How It Works

1. **User Authentication:** Users authenticate to access protected system functionality.
2. **Role Verification:** The system checks the user's assigned role and permissions before allowing access to restricted resources.
3. **Query Processing:** A user submits a question or requests relevant scheduling or administrative information.
4. **Context Retrieval:** The RAG pipeline retrieves relevant information from the vector database using semantic similarity.
5. **Response Generation:** The retrieved context is supplied to the language model to generate a relevant, context-aware response.
6. **Scheduling Assistance:** The system supports the broader goal of organizing schedules, managing deadlines, and simplifying administrative tasks.

## Security and Access Control

ARIA incorporates authentication and authorization as separate layers:

* **JWT authentication** supports identity verification across protected requests.
* **Role-based authorization** determines which resources and actions a user is permitted to access.
* **Protected API endpoints** help enforce access restrictions on sensitive operations.

These mechanisms are particularly relevant to government-oriented systems, where access to administrative information and operations may differ between user roles.

## Getting Started

### Prerequisites

* Node.js and npm
* Python, if running the Python backend
* Access to the configured database and vector database
* Required AI model or API credentials

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/NidhiPatil22/ARIA.git
   cd ARIA
   ```

2. Install the Node.js dependencies:

   ```bash
   npm install
   ```

3. Configure the required environment variables using `.env.example` as a reference. Add the necessary database credentials, authentication configuration, and AI service settings.

4. Start the Next.js development server:

   ```bash
   npm run dev
   ```

5. Open http://localhost:3000 in your browser.

*If the Python backend runs as a separate service, configure and start it according to its dependencies and setup instructions.*

## Future Scope

* Integrate calendar notifications and automated deadline reminders.
* Expand document retrieval across government policies, schedules, and administrative resources.
* Improve retrieval accuracy through better chunking, embedding, and ranking strategies.
* Add comprehensive audit logging and more granular permissions.
* Introduce an interactive AI mascot to make scheduling and task management more engaging.

## What I Learned

Working on ARIA provided practical exposure to integrating AI-based information retrieval with a full-stack application. The project also involved exploring RAG pipelines, vector database integration, secure authentication using JWT, and role-based authorization—connecting AI capabilities with real-world application development.

## Contributors

* [Nidhi Patil](https://github.com/NidhiPatil22)
* [Ankita Nahire](https://github.com/ankitanahire)
* [Rucha Walve](https://github.com/ruchawa-ctrl)

---

**ARIA — Bringing AI-assisted information retrieval and secure scheduling together.**
