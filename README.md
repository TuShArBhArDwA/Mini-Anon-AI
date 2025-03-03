# Mini Anon Ai - A Gemini Clone
![image](https://github.com/user-attachments/assets/mini-anon-ai-banner)

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project
**Mini Anon Ai** is a Gemini clone designed to provide AI-powered assistance. It includes user authentication, database integration, API services, and a scalable architecture for high performance. The project aims to replicate Gemini's AI capabilities with optimized processing and security.

🚀 **Current Status:** The model is functional, responding to user queries, and storing history. However, several features from the to-do list are still under development.

## Features
- 🔐 **User Authentication** *(To Be Implemented)*
  - Secure login and registration system
  - OAuth and JWT-based authentication

- 📦 **Database Integration** *(To Be Improved)*
  - Persistent data storage and management
  - Optimized queries for faster response times

- 🚀 **API Services** *(To Be Developed Further)*
  - RESTful APIs for seamless integrations
  - Webhook support for real-time updates

- ⚡ **Performance Optimization** *(Planned)*
  - Asynchronous processing for low-latency responses
  - Load balancing for scalable performance

- 🛠 **Testing Suite** *(Pending Implementation)*
  - Unit tests and integration tests
  - Continuous integration setup

- 📖 **Documentation Enhancements** *(Ongoing)*
  - Comprehensive guides and setup instructions
  - Troubleshooting tips for common issues

- 🐞 **Bug Tracking** *(To Be Established)*
  - Issue tracking system for resolving bugs efficiently

## Tech Stack
- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** OAuth, JWT
- **Monitoring:** Sentry
- **Deployment:** Vercel

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/TuShArBhArDwA/Mini-Anon-AI.git
   cd Mini-Anon-AI
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Set up environment variables**
- Create a `.env` file in the root directory.
- Add the required environment variables (see Environment Variables).

4. **Start the development server**
   ```sh
   npm run dev
   ```
- The application will be available at http://localhost:3000.

## Environment Variables
Create a `.env` file and configure the following:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   SENTRY_DSN=your_sentry_dsn
   API_KEY=your_api_key
   ```

## Usage
1. **Run the development server**
   ```sh
   npm run dev
   ```

2. **User Authentication** *(Pending)*
   - Sign up or log in with secure authentication.

3. **Interact with AI**
   - Send API requests for AI-powered responses.
   - User history is stored for better contextual understanding.
   
4. **Monitor Performance**
   - Track errors and optimize API performance using Sentry.

## Deployment
- The project is deployed on **Vercel** for seamless hosting.
- To deploy the frontend and backend, use the following command:
   ```sh
   vercel
   ```
- Configure environment variables on Vercel to match your local `.env` file.
- After deployment, access the live application via the provided Vercel URL.

## Contributing
Contributions are welcome! Follow these steps:
1. **Fork the repository**
2. **Clone your forked repository**
   ```sh
   git clone https://github.com/TuShArBhArDwA/Mini-Anon-AI.git
   cd Mini-Anon-AI
   ```
3. **Create a new branch**
   ```sh
   git checkout -b feature-name
   ```
4. **Make your changes and commit them**
   ```sh
   git add .
   git commit -m "Add feature: description of changes"
   ```
5. **Push your changes**
   ```sh
   git push origin feature-name
   ```
6. **Create a Pull Request (PR)**

### Guidelines
- Follow best coding practices.
- Write clear and concise commit messages.
- Ensure the code is properly formatted and linted.
- Test your changes before submitting a PR.

## License
- Distributed under the MIT License. See LICENSE for details.

## Contact
- **Tushar Bhardwaj** - [Portfolio](https://tushar-bhardwaj.vercel.app/)
- **GitHub:** [TuShArBhArDwA](https://github.com/TuShArBhArDwA)
- **LinkedIn:** [Tushar Bhardwaj](https://www.linkedin.com/in/bhardwajtushar2004/)
- **Email:** [tusharbhardwaj2617@example.com](mailto:tusharbhardwaj2617@example.com)
