
# PEER TO PEER BOOK EXCHANGE

**base URL** : https://peer-to-peer-book-exchange-five.vercel.app/

You can sign in as OWNER or SEEKER of books or if you want trial access you can also use these credetials:
    
    email = agampandey705@gmail.com
    password = agam2003

    **This is trial or create Your own account**

**Owners have the ability to add new books and update the status of the books that are posted by them only.**

**Seekers accounts are allowed to search for there desired book by several filtering aspects**

**Key Features:**
- User Registration (Owner and Seeker Roles)
- Book Listing
- Book Status Management
- Search and Filter Functionality

**Technology Stack:**
Frontend:
- React.js
- Vite
- Tailwind CSS
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Installation Steps:**

**1. Clone the Repository**
   - Open terminal
   - Run: git clone https://github.com/agampandey27/Peer-To-Peer-Book-Exchange
   - Navigate to project directory

**2. Backend Setup**
   - Move to backend folder
   - Run: npm install
   - Create .env file with:
     * MONGODB_URI=[your-mongodb-connection-string]
     * PORT=8080

**3. Frontend Setup**
   - Move to frontend folder
   - Run: npm install

**4. Running the Application**
   - Start Backend: npm run start (in backend folder)
   - Start Frontend: npm run dev (in frontend folder)

Key Components:
- User Authentication
- Book Listing Page
- Owner Dashboard
- Seeker Dashboard
- Book Status Management

API Endpoints:
1. User Registration: /api/auth/register
2. User Login: /api/auth/login
3. Add Book: /api/book
4. Get Books: /api/book
5. Update Book Status: /api/book/:id/status