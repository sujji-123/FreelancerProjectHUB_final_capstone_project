 Connect & Collaborate: Freelancer Project Hub
Welcome to the Freelancer Project Hub, a full-stack MERN web application designed to streamline project management and collaboration between freelancers and clients. This platform provides a centralized workspace, moving beyond the initial hiring phase to focus on the active project lifecycle—from proposal to payment.

This project was developed to gain hands-on experience in building a complete, industry-relevant application with a decoupled client-server architecture. It addresses common challenges in project management by offering a dedicated environment for collaboration, task management, and secure transactions.

Key Features in Detail
1. Robust, Role-Based User Authentication
The platform implements a secure and distinct authentication system for two primary user roles: Clients and Freelancers.

Secure Registration & Login: Users can sign up and log in based on their role. All passwords are encrypted using 

bcryptjs to ensure data security.



JWT-Based Authentication: The system uses JSON Web Tokens (JWT) for secure user authentication. Once a user logs in, a unique token is generated and stored, allowing for persistent and secure sessions across the application.




Role-Specific Access Control: The application's architecture ensures that users have access only to the features relevant to their roles. For example, only clients can post projects, while only freelancers can submit proposals.



2. Comprehensive Project & Proposal Management
The Freelancer Project Hub simplifies the process of connecting clients with skilled freelancers through an intuitive project and proposal system.

Project Creation (Clients): Clients can easily post new projects, providing details such as the title, description, and budget. These projects are then listed on a marketplace page for freelancers to browse.

Marketplace & Bidding (Freelancers): Freelancers can explore a list of all "open" projects and submit proposals for those that match their skills. Each proposal includes a cover letter and a bid amount.


Proposal Review (Clients): Clients have a dedicated section on their dashboard to review all incoming proposals for their projects. They can assess each freelancer's bid and cover letter and choose to either accept or reject the proposal, streamlining the hiring process.


3. Real-Time Collaboration & Communication
At the core of the platform is a powerful, real-time collaboration system designed to keep clients and freelancers in sync throughout the project lifecycle.


Project-Specific Chat: Each project has a dedicated, real-time chat window, powered by Socket.IO. This allows for instant and direct communication, eliminating the need for external messaging apps.


Live Notifications: The application features a live notification system that alerts users to important events in real-time. This includes notifications for new messages, updates to task statuses, and the submission of new deliverables.

4. Advanced Task & Deliverable Management
The platform includes a comprehensive set of tools for managing project tasks and deliverables, ensuring clarity and accountability for both parties.


Kanban-Style Task Board: A visual, Kanban-style task board allows users to create, assign, and track tasks through various stages: 'to-do', 'in-progress', and 'done'. This provides a clear, at-a-glance overview of project progress.



Cloud-Based File & Deliverable Uploads: The application is integrated with Cloudinary, a cloud-based solution for managing file and image uploads. Clients can upload project briefs and assets, while freelancers can submit their work for review. This ensures that all project-related files are stored securely and are easily accessible.


5. Secure & Streamlined Payment Workflow
The Freelancer Project Hub provides a secure and straightforward system for managing project payments, ensuring that freelancers are compensated for their work in a timely manner.

Mock Financial Transactions: The platform simulates a professional financial workflow, allowing for secure project payments from clients to freelancers.

Invoice Management: Freelancers can generate and upload invoices (as PDFs) for completed work, which clients can then review and approve for payment.

6. User-Specific Dashboards & Profiles
The application features intuitive and user-friendly dashboards tailored to the specific needs of both clients and freelancers, along with detailed user profiles.


Freelancer Dashboard: The freelancer dashboard provides a centralized hub to view active projects, track pending proposals, and monitor earnings statistics. It also includes job recommendations to help freelancers find new opportunities.




Client Dashboard: The client dashboard allows for easy management of all posted projects, with filters for "open," "in-progress," and "completed" statuses. It also includes a dedicated section for reviewing incoming proposals and a "Task Progress" overview for all active projects.



User Profiles: Both clients and freelancers have profiles that display key information. Freelancer profiles can be enhanced with a portfolio, a list of skills, and reviews from past projects.

Tech Stack
This application is built with the 

MERN stack and other modern technologies to ensure a scalable, maintainable, and efficient platform.


Frontend: React (with Vite), React Router DOM, Axios 


Backend: Node.js, Express.js 


Database: MongoDB Atlas (cloud database) 



Real-time Communication: Socket.IO 


Authentication: JSON Web Tokens (JWT), Bcryptjs 


File Storage: Cloudinary (for file and image uploads) 


Version Control: Git & GitHub 


API Testing: Postman 

Deployment
The application is deployed on an AWS EC2 instance, providing a robust and scalable hosting environment. The database is managed using 

MongoDB Atlas, a fully-managed cloud database service.


Future Enhancements
Future plans for the project include:

Integrating a more robust payment gateway like 

Stripe, complete with webhooks for transaction confirmation.

Implementing public user profiles that display a user's projects, ratings, and reviews.

Adding email notifications for important events such as new messages or project updates.

Developing a native mobile application using a framework like 

React Native to provide users with on-the-go access.

DEPLOYED LINK:
http://51.20.85.41 

GITHUB REPO LINKS :
-FRONTEND:
  https://github.com/sujji-123/FreelancerProjectHub-frontend.git
-BACKEND:
  https://github.com/sujji-123/FreelancerProjectHub-backend.git