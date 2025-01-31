# 🗳️ Polling Management System

A comprehensive **Full-Stack Web Application** for creating, managing, and participating in polls. Designed with modern technologies to deliver a secure, efficient, and user-friendly platform for collecting opinions, conducting surveys, and facilitating decision-making. 🚀  

---

## 🌟 Features  

### 🔐 User Authentication:  
- Secure registration and login using **JWT**.  
- Password encryption for enhanced security.  
- Session management to restrict unauthorized access.  

### 📝 Create Polls:  
- Add a title, description, and multiple voting options.  
- Customizable poll settings: Single or multiple votes per user.  

### 🛠️ Manage Polls:  
- Edit or delete polls with ease.  
- Admin privileges for overseeing all polls in the system.  

### 🗳️ Voting:  
- Cast votes securely on available polls.  
- Real-time vote count updates.  
- Prevent duplicate voting by tracking user participation.  

### 📊 Results Visualization:  
- Real-time updates as votes are cast.  
- Interactive results displayed via **graphs** and **charts**.  
- Summarized results accessible to poll creators and participants.  

### 🔍 Search and Filter:  
- Search for polls by title, keywords, or creator.  
- Filter polls by categories, popularity, or creation date.  

---

## 🛠️ Technology Stack  

### 🖥️ Frontend:  
- **React.js**: Dynamic and responsive user interface.  
- **CSS**: Styling and layout design.  
- **JavaScript (ES6+)**: Interactivity and functionality.  

### ⚙️ Backend:  
- **Node.js**: Server-side scripting and API handling.  
- **Express.js**: Backend logic and APIs.  

### 📂 Database:  
- **MongoDB**: Flexible, document-oriented NoSQL database.  

---

## 📂 Project Modules  

1. **User Module**:  
   - User authentication, profile management, and session handling.  

2. **Poll Management Module**:  
   - Create, edit, and delete polls with customizable options.  

3. **Voting Module**:  
   - Secure voting with real-time updates.  

4. **Results Visualization Module**:  
   - Display poll results using **charts** and **graphs**.  

5. **Database Module**:  
   - Efficient storage and retrieval of user, poll, and vote data.  

6. **Search and Filter Module**:  
   - Navigate and find polls easily with advanced filters.  

---

## 🚀 Installation  

### Prerequisites:  
- **Node.js**  
- **MongoDB**  

### Steps:  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/Subramanian7986/polling-management-system.git  
   cd polling-management-system  
   ```  

2. **Install Dependencies**:  
   ```bash  
   npm install  
   ```  

3. **Start MongoDB**:  
   - Run `mongod` for a local instance.  

4. **Set Environment Variables**:  
   - Create a `.env` file and set the `MONGODB_URI` and `JWT_SECRET`.  

5. **Start the Application**:  
   ```bash  
   npm start  
   ```  

6. **Access the App**:  
   - Open `http://localhost:5000` in your browser.  

---

## 📊 Database Schema  

- **users**: Stores user credentials and roles.  
- **polls**: Stores poll details and associated candidates.  
- **votes**: Tracks user votes for polls.  

---

## 🎯 Future Enhancements  

- 🌐 Multilingual support for a global audience.  
- 📧 Email notifications for poll updates.  
- 📈 Advanced analytics and visualizations.  

---

## 📜 License  

This project is licensed under the [MIT License](LICENSE).  

---

Crafted with ❤️ for seamless and interactive polling experiences. 🗳️  
