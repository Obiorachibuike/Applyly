
# Job Portal Application

**Live Link**: [Job Portal](https://job-portal-client-git-main-impulseadis-projects.vercel.app/)  
**GitHub Repository**: [Job Portal GitHub](https://github.com/Obiorachibuike/Apply)  

## Project Overview

The Job Portal Application is a full-stack web application built using the **MERN Stack** (MongoDB, Express, React, Node.js) with integrated **Clerk Authentication** for secure user login, role-based access control, and session management. This app allows job seekers to search, apply for jobs, and upload resumes, while recruiters can post jobs, manage applications, and track real-time status updates.

## Features

- **Job Seeker Dashboard**:
  - Search and apply for jobs.
  - Upload resumes (PDFs) for job applications.
  
- **Recruiter Dashboard**:
  - Post and manage job listings.
  - Review job applications with real-time status updates.
  
- **Authentication & Authorization**:
  - Secure login and role-based access using **Clerk**.
  - **JWT-based authentication** to secure routes, allowing recruiters to manage job listings while job seekers have access to search and apply for jobs.
  
- **Performance Monitoring**:
  - Integrated **Sentry** for error tracking and performance monitoring to optimize MongoDB queries and improve app performance.
  
- **Responsive UI**:
  - Built with **React**, **Vite**, and **TailwindCSS** for a fast and responsive user interface.
  - Designed with modern UI principles to ensure a seamless experience across devices.

## Technologies Used

- **Frontend**: React.js, Vite, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Clerk, JWT
- **Error Tracking**: Sentry
- **Deployment**: Vercel (Frontend), Render (Backend)

![Screenshot 2025-02-18 025910](https://github.com/user-attachments/assets/45bdfe2a-1614-495b-99b0-d6f97d6f9b2f)  
![Screenshot 2025-02-18 025919](https://github.com/user-attachments/assets/adfec915-a2a2-4d19-80d1-8d5037a289c4)  
![Screenshot 2025-02-18 025929](https://github.com/user-attachments/assets/18b83c69-db07-4240-8045-c86a30167b65)  
![Screenshot 2025-02-18 025938](https://github.com/user-attachments/assets/154331ec-ba6e-4b53-a1a0-dd3eae3a4d88)  
![Screenshot 2025-02-18 025950](https://github.com/user-attachments/assets/c34209fd-9da4-443e-82fa-7bc18f674fa6)  
![Screenshot 2025-02-18 030004](https://github.com/user-attachments/assets/f757b247-a9d4-49d2-a3a6-40ad621451d9)  
![Screenshot 2025-02-18 030016](https://github.com/user-attachments/assets/c6e0c16a-4c42-4e2d-8604-3796cabafad4)  
![Screenshot 2025-02-18 032706](https://github.com/user-attachments/assets/d4ee4c93-42b3-4d3d-9428-303a81bb00c6)  
![Screenshot 2025-02-18 032715](https://github.com/user-attachments/assets/24cfc95e-6cae-4cc5-bbee-5c6258ca3e1d)  
![Screenshot 2025-02-18 032730](https://github.com/user-attachments/assets/2f993548-61bc-42da-b970-c247269ee891)  

*Above: Screenshot of the Job Seeker and Recruiter Dashboards.*

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/impulseadi/job-portal.git
   ```

2. Navigate to the project directory:
   ```bash
   cd job-portal
   ```

3. Install the dependencies for both frontend and backend:
   - For the frontend:
     ```bash
     cd client
     npm install
     ```
   - For the backend:
     ```bash
     cd server
     npm install
     ```

4. Set up environment variables:
   - Create a `.env` file in the `server` directory and add the necessary environment variables (e.g., MongoDB URI, Clerk API keys).

5. Start the backend server:
   ```bash
   cd server
   npm start
   ```

6. Start the frontend application:
   ```bash
   cd client
   npm start
   ```

7. Open your browser and navigate to `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to report a bug, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the developers of the MERN stack and Clerk for providing the tools that made this project possible.
- Special thanks to the open-source community for their contributions and support.