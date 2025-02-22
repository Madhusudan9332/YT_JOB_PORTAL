# Job Portal Application

### url : https://yt-job-portal.onrender.com

This is a full-stack Job Portal application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). It allows users to sign up, search for jobs, apply for them, and, in the case of employers, post new job openings.

## Features

*   **User Authentication:**
    *   Secure user registration and login.
    *   Different user roles (e.g., employee/job seeker and employer).
*   **Job Search:**
    *   Browse available job listings.
    *   Filter and search jobs based on various criteria (e.g., job title, location, industry).
*   **Job Application:**
    *   Employees can apply for jobs directly through the platform.
    *   Track application status (e.g., applied, in progress, rejected).
*   **Job Posting (Employer Functionality):**
    *   Employers can post new job openings.
    *   Manage and edit existing job postings.
    * receive application for their jobs
* **Application tracking**
    * job seeker can track his applications
* **Credentials**
    * this app use credentials to keep secure user data

## Tech Stack

*   **Frontend:**
    *   React.js: For building the user interface.
    *   Redux: For state management. (Implied from `applicationSlice` and `useGetAppliedJobs`.)
    * Axios: for sending request to the server
*   **Backend:**
    *   Node.js: For running the server-side application.
    *   Express.js: A web framework for Node.js, used to create APIs.
*   **Database:**
    *   MongoDB: A NoSQL document database for storing application data.
*   **Other:**
    *   likely use of environment variables for sensitive information (like database credentials and api keys).

## Installation and Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Madhusudan9332/YT_JOB_PORTAL.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd jobportal_youtube
    ```

3.  **Install dependencies:**
    *   **Frontend:**
        ```bash
        cd frontend
        npm install
        ```
    *   **Backend:**
        ```bash
        cd backend # if have backend folder
        npm install
        ```

4.  **Configure environment variables:**
    *   Create a `.env` file in the `backend` directory.
    *   Add necessary environment variables, such as:
        ```
        MONGO_URI=your_mongodb_connection_string
        PORT=your_desired_port (e.g., 5000)
        # Add other sensitive configuration variables.
        ```

5.  **Start the application:**
    *   **Backend:**
        ```bash
        cd backend
        npm start  # Or nodemon server.js or similar command
        ```
    *   **Frontend:**
        ```bash
        cd frontend
        npm start
        ```

6.  **Access the application:** Open your web browser and go to `http://localhost:3000` (or the port specified for your frontend).

## Project Structure (Typical MERN structure)

