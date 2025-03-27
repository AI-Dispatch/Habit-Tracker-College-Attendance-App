# Habit Tracker & College Attendance App

## 🚀 Overview
The **Habit Tracker & College Attendance App** is a feature-rich web application designed to help users visualize their daily habits and routines. Additionally, it includes a **College Attendance Tracker**, allowing students to monitor their class attendance efficiently. The app integrates with **Google Calendar** and **Notion Calendar** for seamless synchronization and enhanced productivity.

<img width="928" alt="Screenshot 2025-03-26 at 11 29 53 PM" src="https://github.com/user-attachments/assets/9c44c9d2-65d4-4f8a-ad86-44378c0848d6" />


## ✨ Features
### 🎯 Habit Tracking
- Create, update, and delete habits
- Categorization & tagging of habits
- Data visualization with charts & graphs
- Customizable reminders & notifications
- Data export functionality for analysis

<img width="923" alt="Screenshot 2025-03-26 at 11 30 00 PM" src="https://github.com/user-attachments/assets/bce14a56-d87c-421f-a50e-094f95c51469" />


### 📅 Calendar Integrations
- **Google Calendar**: Sync habits with Google Calendar for scheduling
- **Notion Calendar**: Log habit progress in a Notion database
- Integrated API endpoints for seamless connectivity

<img width="921" alt="Screenshot 2025-03-26 at 11 30 07 PM" src="https://github.com/user-attachments/assets/521ef7c9-61e0-4e29-a2e6-34844cf2b48f" />


### 🏫 College Attendance Tracker
- Log attended and skipped classes
- View attendance statistics
- Monitor trends over time
- Generate reports on class participation

<img width="920" alt="Screenshot 2025-03-26 at 11 30 22 PM" src="https://github.com/user-attachments/assets/9f6490f5-8d12-4188-ac2e-6a04f644209b" />


### 🖥️ User Interface
- Intuitive dashboard for habit visualization
- Calendar view for tracking routines
- Attendance log with real-time updates

## 🛠️ Tech Stack
- **Frontend**: React, TypeScript
- **Backend**: Node.js, Express
- **Database**: In-memory storage (for now, can be extended to a database)
- **API Integrations**: Google Calendar API, Notion API

## 📦 Installation & Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/AI-Dispatch/Habit-Tracker-College-Attendance-App.git
   cd Habit-Tracker-College-Attendance-App
   ```
2. **Install Dependencies**
   ```sh
   npm install
   ```
3. **Set Up API Credentials**
   - Google Calendar API
   - Notion API
   - Add credentials in a `.env` file
4. **Run the Application**
   ```sh
   npm run dev
   ```

## 🔑 API Configuration
### 🌍 Google Calendar API
To enable Google Calendar integration, provide the following environment variables:
```env
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
GOOGLE_REDIRECT_URI=http://localhost:5000/api/auth/google/callback
GOOGLE_REFRESH_TOKEN=your_refresh_token
```

### 📝 Notion API
To enable Notion integration, provide the following environment variables:
```env
NOTION_API_KEY=your_notion_api_key
NOTION_DATABASE_ID=your_database_id
NOTION_PARENT_PAGE_ID=your_parent_page_id
```

## 📈 Future Enhancements
- AI-driven habit recommendations
- Multi-user support with account authentication
- Mobile app version with push notifications
- Advanced statistics with AI insights

## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License.

## 📬 Contact
For any queries, reach out to **V Chaitanya Chowdari** via:
- 🌐 [LinkedIn](https://www.linkedin.com/in/v-chaitanya-chowdari-bb3733202)
- 📩 [Email](mailto:vchaitanyachowdari@gmail.com)
