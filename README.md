# **Startup Ecosystem Web Application**

### **Description**
This is a comprehensive web application designed to foster a startup ecosystem, enabling users to create profiles, build connections, share resources, organize events, and more. The platform is built using **ReactJS**, **NodeJS**, **MongoDB**, and integrates **socket.io** for real-time chatting. It also utilizes the **Natural** NPM module for intelligent profile matching, offering personalized friend and mentor suggestions.

---

### **Table of Contents**
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

### **Features**

1. **User Authentication**
   - Secure user login and registration.
   
2. **User Profile Management**
   - Create, read, update, and delete user profiles.
   
3. **Startup Management**
   - Create, edit, delete, and manage startup listings.
   
4. **Feed with Comments and Likes**
   - Users can post on the feed, comment on posts, and like posts.
   
5. **Filtering Startups**
   - Filter startups based on salary, number of employees, valuation, and more.

6. **Make Friends and Mentors**
   - Users can connect with others and add friends or mentors.

7. **Real-time Chat**
   - Chat with friends and mentors using **socket.io** for real-time communication.

8. **Friend Suggestions**
   - Get personalized friend/mentor suggestions using profile matching via the **Natural** NPM module.

9. **Event Organizing**
   - Create and manage events like webinars, seminars, and more.

10. **Article and Resource Sharing**
    - Share and read articles to help startups, allowing users to contribute startup-related resources.

---

### **Technologies Used**
- **Frontend:** ReactJS
- **Backend:** NodeJS, Express
- **Database:** MongoDB
- **Real-time Communication:** Socket.io
- **Profile Matching:** Natural NPM Module
- **Authentication:** JWT (JSON Web Token)
  
---

### **Installation**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/startup-ecosystem-app.git
   cd startup-ecosystem-app
2. **Install the dependencies for both the backend and frontend:**
   **Backend**
   ```bash
   cd backend
   npm install
   ```
   **Frontend**
   ```bash
      cd frontend
      npm install
   ```
3. **Create a .env file in the backend directory and configure the following environment variables:**
   ```bash
   PORT=5000
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret>
   ```
4. **Run the application:**

   **Backend:**
   ```bash
   cd backend
   npm start
   ```
   **Frontend:**
   ```bash
   cd frontend
   npm start
   ```
   ---
### **Usage**
1. **User Authentication:**
   Sign up or log in using email and password.
2. **Create Profile:**
   Navigate to your profile page to create or update personal and startup details.
3. **Explore Startups:**
   Use the filters to search for startups based on salary, number of employees, and other criteria.
4. **Connect with Others:**
   Use the friend and mentor suggestions to find relevant matches, and chat with them in real time.
5. **Participate in Events:**
   Create, join, or manage startup events like webinars and seminars.
6. **Share Articles:**
   Write and share articles to offer startup insights, or browse resources shared by others.

---

### **Here are some screenshots of the application:**

  1. ![User Authentication (Sign Up / Log In Page)](./screenshots/Auth.png)

  2. **User Profile (Create/Update Profile)**
   
  3. **Startup Listings and Filters**
   
  4. **Feed with Comments and Likes**
   
  5. **Real-time Chat**
   
  6. **Event Organizing Page**
   
  7. **Article and Resource Sharing Page**
---
### **Contributing**
**Contributions are welcome! To contribute to this project, follow these steps:**
   1. Fork the repository.
   2. Create a new branch (git checkout -b feature-branch).
   3. Make your changes and commit them (git commit -m 'Add new feature').
   4. Push to the branch (git push origin feature-branch).
   5. Open a Pull Request.
---
### **Contact**
If you have any questions, feel free to reach out to me via email at gk991789@gmail.com.
