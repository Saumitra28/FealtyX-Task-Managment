FealtyX TaskSphere - Bug/Task Tracker Interface

Overview
TaskSphere is a web-based task management application designed to streamline task tracking and collaboration for individuals and teams. This README provides a comprehensive guide to the TaskSphere frontend, detailing its features, technologies used, setup instructions, and project structure. This document also includes information on an assignment requirement for FealtyX—a Bug/Task Tracker Interface built using Next.js/React to showcase frontend development skills, UI/UX design principles, and proficiency with the Next.js/ReactJS framework.

Secure user authentication with registration, login, and logout.
Simple login system (mock authentication) for testing; can be expanded to real backend authentication.
Upon successful login, users are redirected to their dashboard.

Dashboard
An intuitive dashboard where users can view and manage their tasks/bugs.
Dashboard includes a trend line of concurrent tasks managed each day.
Task/Bug list view displaying relevant details for each task.

Task/Bug Creation & Management
Users can create, edit, update, and delete tasks/bugs with comprehensive fields like Title, Description, Priority, Status, Assignee, and Dates.
A time tracker logs hours spent on each task with a total time display.


Team Collaboration
Task and team management features allow users to view and manage tasks assigned to team members.

Notifications
Real-time notifications for task assignments, updates, and reminders.

Profile Management
Users can update profile details and reset passwords.

Responsive Design
Clean, user-friendly, and responsive design to ensure a seamless experience on both desktop and mobile.

Technologies Used
Frontend Framework: Next.js (preferred) / React.js
State Management: Redux
Routing: React Router (for non-Next.js setup) or Next.js built-in routing
CSS Framework: Tailwind CSS for responsive design
Form Handling: React Hook Form
Notifications: React Toastify for real-time alerts
Icons: React Icons
Time Tracking UI: Styled-components or a similar CSS-in-JS solution for task timer and tracker interface

Getting Started:
Follow these instructions to run the TaskSphere frontend locally:

Clone the Repository:
git clone <repository_url>

Navigate to the Project Directory:
cd TaskSphere/client

Install Dependencies:
npm install

Environment Variables:
Create a .env file in the root directory of the client folder and set the following environment variables:
REACT_APP_API_BASE_URL=<backend_api_base_url>

Start the Development Server:
npm start

Access the Application:
Open your browser and visit http://localhost:3000 to view the TaskSphere application.
OR
The Demo Link: https://fealtyx-task-managment.onrender.com