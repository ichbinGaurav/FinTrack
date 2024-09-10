# Personal Finance Management System (FinTrack)

### Project Overview
The **Personal Finance Management System** (FinTrack) is a multi-platform solution designed to help users manage their financial transactions, debts, and goals efficiently. It provides a user-friendly interface for tracking personal and business finances, with insights into spending behavior through graphs and charts. The system also allows users to split expenses with others and export financial data for record-keeping and analysis.

This project was developed as part of the 6th-semester final project for the **B.Sc. (Information Technology)** 5-year integrated course at **Veer Narmad South Gujarat University**.

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

