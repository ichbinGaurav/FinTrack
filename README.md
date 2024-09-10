# Personal Finance Management System (FinTrack)

### Project Overview
The **Personal Finance Management System** (FinTrack) is a multi-platform solution designed to help users manage their financial transactions, debts, and goals efficiently. It provides a user-friendly interface for tracking personal and business finances, with insights into spending behavior through graphs and charts. The system also allows users to split expenses with others and export financial data for record-keeping and analysis.

This project was developed as part of the 6th-semester final project for the **B.Sc. (Information Technology)** 5-year integrated course at **Veer Narmad South Gujarat University**.

---

### Contributors
- **Gaurav Chauhan (Website)** 
- **Chirag Boghara (Application)** 

---

### Key Features
1. **User Authentication**:
   - OTP-based login system using a valid mobile number.
   - Ensures secure access to personal finance data with JSON Web Tokens (JWT) for session handling.

2. **Personal Finance Tracking**:
   - Track daily, monthly, and yearly income and expense transactions.
   - Add, update, and delete transactions with attached receipts (images).
   - Categorize transactions using predefined and custom categories.

3. **Goal Management**:
   - Create financial goals (e.g., buying a house, saving for a vacation).
   - Track progress by adding saved amounts over time.
   - Visualize the goal completion percentage.

4. **Debtor & Creditor Management**:
   - Keep track of loans or debts with details of debtors and creditors.
   - Add, update, or delete records of financial transactions involving debts.

5. **Group Expense Management**:
   - Split bills and expenses with friends, family, or colleagues.
   - Create groups to manage shared expenses and keep track of each member’s contributions.

6. **Insightful Financial Graphs**:
   - Visualize spending and income data through detailed graphs and charts.
   - Analyze financial data over a specific time frame (day, month, year).

7. **Data Export**:
   - Export all transaction data, debtor and creditor records, or goal information to CSV or Excel files.
   - Share transaction records via social media or messaging platforms.

8. **Customizable App Interface**:
   - Change the app’s color theme according to user preferences.
   - Dark mode and multiple color schemes for a personalized experience.

9. **Reminders and Notifications**:
   - Set daily reminders to ensure users log their transactions regularly.
   - Receive notifications about progress toward financial goals.

---

### Technology Stack

**Frontend**:
- **Mobile Application**: Developed using **Flutter** for a cross-platform mobile experience (Android & iOS).
- **Web Application**: Built using **ReactJS**, a JavaScript framework, ensuring a responsive user interface for web users.

**Backend**:
- **Node.js**: Provides a robust backend API for communication between the app and the database.
- **Express.js**: Serves the API for the frontend applications.
  
**Database**:
- **MongoDB**: A NoSQL database is used for storing all user data, including transactions, groups, goals, debtors, and creditors.
- **Mongoose**: A MongoDB Object Data Modeling (ODM) library is used for managing schema-based models in the application.

**Development Tools**:
- **Postman**: Used for API testing.
- **MongoDB Compass**: GUI tool for managing the MongoDB database.
- **Visual Studio Code**: IDE for coding and development.

---

### System Requirements

#### Hardware Requirements:
- A PC or laptop with an active internet connection for testing and development.

#### Software Requirements:
- **For Mobile Development**:
  - Android Studio or Visual Studio Code with Flutter plugin.
  - An Android Emulator or physical Android/iOS device for testing.
  
- **For Web Development**:
  - Any modern web browser (Google Chrome or Microsoft Edge).
  - A code editor (Visual Studio Code or any other IDE).
  
- **Backend**:
  - Node.js and npm installed for running the backend server.
  - MongoDB server for data storage.

---

### Features in Detail

1. **Authentication**
   - **Sign Up/Log In**: Users can sign up using their mobile number. OTP-based authentication ensures secure access.
   - **Logout**: Users can log out at any time, and their session is securely terminated.

2. **Managing Transactions**
   - **Add Transaction**: Users can add an income or expense transaction. Each transaction includes a description, category, and optional bill image.
   - **Update/Delete**: Transactions can be updated or deleted, with changes reflected in real-time.
   - **Custom Categories**: Users can create new categories for their transactions besides the default ones.

3. **Group Expense Sharing**
   - Users can create groups to split expenses with multiple members. The app calculates who owes whom, simplifying group payments for things like trips, shared living expenses, or events.

4. **Goals Management**
   - **Create Goal**: Set goals with target amounts and deadlines.
   - **Track Progress**: Users can view how much they’ve saved toward a goal, with visual progress indicators.

5. **Debt Management**
   - Track amounts owed to or from debtors and creditors.
   - Users can keep records of their financial obligations and manage settlements with a few clicks.

6. **Data Visualization**
   - Graphs provide insights into income and expense trends, helping users understand their financial situation at a glance.

7. **Data Export and Sharing**
   - Users can export their financial data in CSV or Excel format.
   - Share data directly via email or messaging apps, making it easier to collaborate on group finances.

8. **Daily Reminders**
   - Local notifications can be set to remind users to log their transactions at a specified time.

---

### System Architecture

#### Frontend:
- The mobile app is built using **Flutter**, which ensures cross-platform compatibility (Android & iOS).
- The web app uses **ReactJS**, offering a responsive and interactive user experience.

#### Backend:
- **Node.js** and **Express.js** power the backend, handling requests and serving data to the frontend applications.
- **MongoDB** is used as the database, offering flexibility and scalability for storing and managing user data.

#### API Integration:
- The frontend communicates with the backend via **RESTful APIs**, enabling secure data transactions between the frontend and the database.

---

### Future Enhancements

- **Cloud Data Backup**: Allow users to back up their data to the cloud for access from multiple devices.
- **In-App Purchases**: Add premium features that users can unlock through in-app purchases.
- **Social Media Integration**: Implement a system where users can share financial tips, track trends, and engage with a financial community.
- **Stock & Crypto Alerts**: Notify users of key price changes for stocks and cryptocurrencies.
- **QR Code Scanning**: Enable adding group members by scanning a QR code.


