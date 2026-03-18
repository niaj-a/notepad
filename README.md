MERN Notepad Application

Author: Niaj Ahmed

Id: 003184473

Subject: Computational engineering(Late)

Lut University

This is a full-stack MERN (MongoDB, Express, React, Node.js) application for creating and managing notes.

🔧 How to Run the Project

1. Clone the repository
   
          git clone https://github.com/niaj-a/notepad.git
   
          cd notepad
   
3. Setup Backend:
   
          cd backend
   
          npm install

   Go to mongodb cluster: Cluster>Connect>Drivers>Get the connection string below.
   
          mongodb+srv://admin:<db_password>@cluster0.u2befyt.mongodb.net/?appName=Cluster0
   
   Create a .env file in the backend folder: (paste the connection string with changing the password and add repository name> then save with ctrl+s)

          mongodb+srv://admin:<db_password>@cluster0.u2befyt.mongodb.net/<repository-name>

Start backend:

          npm run dev

Check Backend:

   Open another terminal:Paste those:
   
          curl http://localhost:5001/api/notes
          
          curl http://localhost:5001
          
   Or, open browser: run:
   
          http://localhost:5001
          
3. Setup Frontend

   Open a new terminal:

       cd frontend
       npm install
       npm run dev
       
5. Open Application

    Go to:http://localhost:5173
   
🧪 API Test

    http://localhost:5001/api/notes
   
📁 Project Structure

backend/    → Express + MongoDB API

frontend/   → React (Vite) UI

Video Demo: https://youtu.be/Efm53fkpGtc

Thanks!

📘 Notes

MongoDB Atlas is used as the database

Ensure your IP is allowed in Atlas
