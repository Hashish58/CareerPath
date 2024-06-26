# Job Portal

Here's a revised version of the description for your MERN Stack based web app, CareerPath:

---

**CareerPath** is a comprehensive MERN Stack web application designed to streamline the job application process. It offers distinct roles for users—applicants and recruiters—enabling them to create and manage accounts with ease. 

Key features of CareerPath include:

- **Persistent Login Sessions:** Users stay logged in across sessions for a seamless experience.
- **Secure REST APIs:** All API interactions are protected using JWT token verification, ensuring secure data transmission.

**For Recruiters:**
- Create, update, and delete job postings.
- ortlist, accept, or reject applications.
- View resumes and manage applicant information.
- Edit their own profile.

**For Applicants:**
- Browse job listings and perform fuzzy searches with various filters.
- Apply for jobs with a Statement of Purpose (SOP).
- View the status of their applications.
- Upload profile pictures and resumes.
- Edit their profile.

CareerPath is an all-in-one solution for managing job applications efficiently, catering to both recruiters and job seekers.

---

This version retains the essential details and clearly outlines the functionalities for both user roles in a concise manner.

Directory structure of the web app is as follows:


Sure, here's the modified instructions for initializing the web app with the updated folder structure and MongoDB Atlas:

---

## Instructions for Initializing CareerPath Web App:

1. **Install Node.js:**
   - Download and install Node.js from [nodejs.org](https://nodejs.org/).

2. **Set Up MongoDB:**
   - You can either install MongoDB locally or use MongoDB Atlas for a cloud-based solution. For MongoDB Atlas, create an account at [mongodb.com](https://www.mongodb.com/cloud/atlas), set up a cluster, and get your connection string.

3. **Start Backend Server:**
   - Move inside the backend directory:
     
     cd backend
     
   - Create a `.env` file in the `backend` directory with your MongoDB Atlas connection string:
     env
     MONGO_URI=your_mongodb_atlas_connection_string
     
   - Install dependencies:
     
     npm install
     
   - Start the Express server:
     
     npm start
     
   - The backend server will start on port 4444.

4. **Start Frontend Server:**
   - Move to the root directory:
      
   - Install dependencies:
     
     npm install
     
   - Start the frontend server:
     
     npm start
     
   - The frontend server will start on port 3000.

5. **Open the Application:**
   - Open your browser and navigate to `http://localhost:3000/`.
   - Proceed with creating jobs and applications by signing up in the required categories.

---

These instructions include using MongoDB Atlas for the database and clarify the folder structure, with `backend` inside a subdirectory and `frontend` directly present in the root.

## Dependencies:

- Frontend
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend
  - bcrypt
  - body-parser
  - connect-fla
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid

# Machine Specifications

Details of the machine on which the webapp was tested:

- Operating System: Elementary OS 5.1 (Hera)
- Terminal: Ba
- Processor: Intel Core i7-8750H CPU @ 2.20 GHz 2.21 GHz
- RAM: 16 GB
