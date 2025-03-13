# Movie Management Application

A full-stack application for managing movies using Spring Boot (backend) and Angular (frontend).

## Default Accounts

### Admin User
- **Username:** admin  
- **Password:** admin

### Regular User
- **Username:** user  
- **Password:** user

## Installation

**Project Setup**

1. Clone the repository:
   ```git clone --recurse-submodules https://github.com/saharfayez/movie-management-app.git```

**Backend Setup**

1. Navigate to the backend directory:
   ```cd backend```
2. Install dependencies:
   ```mvn install```
3. Run the application:
   ```mvn spring-boot:run```
4. No need for database configuration as i used h2 in-memory database for easy setup
5. The tables will be automatically created and filled using flyway migration scripts
 
**Frontend Setup**

1. Navigate to the frontend directory:
   ```cd frontend```
2. Install dependencies:
   ```npm install```
3. Start the Angular application:
   ```npm start```
4. By default, it should be on port 4200. Open your browser and go to http://localhost:4200
