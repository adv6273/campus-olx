
**Installation**  
  Prerequisites  
 * Node.js (version 14.x or later)  
 * npm (version 6.x or later)  
**Steps**
    * Clone the Repository   
      * git clone https://github.com/yourusername/campus-olx.git
      * cd travo-app
        
    * Install Backend Dependencies
       * cd backend
       * npm install
         
    **Set Up Environment Variables**
    
    Create a .env file in the backend directory with the following content:
    
    **env**
      MONGO_URI=your_mongodb_uri  
      JWT_SECRET=your_jwt_secret  
      PORT=4000  

   **Start the Backend Server :**   
    node index.js

   **Install Frontend Dependencies :**  
    
     Open a new terminal and navigate to the client directory:  
      cd ../client  
      npm install
     
     Set Up Frontend Environment Variables  
      Create Urls.js file in your src folder and store your base url as  
      export const baseUrl=your_base_url  on local machine write here `http://localhost:3000`
   
    Start the Frontend Development Server  
      npm run start
   
    Usage
    Once both the backend and frontend servers are running,
    open your browser and go to http://localhost:3000 to access the application.
