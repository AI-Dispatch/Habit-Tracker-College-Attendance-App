# Habit Tracker & College Attendance App

## 🚀 Overview
The **Habit Tracker & College Attendance App** is a feature-rich web application designed to help users visualize their daily habits and routines. Additionally, it includes a **College Attendance Tracker**, allowing students to monitor their class attendance efficiently. The app integrates with **Google Calendar** and **Notion Calendar** for seamless synchronization and enhanced productivity.

## ✨ Features
### 🎯 Habit Tracking
- Create, update, and delete habits
- Categorization & tagging of habits
- Data visualization with charts & graphs
- Customizable reminders & notifications
- Data export functionality for analysis

### 📅 Calendar Integrations
- **Google Calendar**: Sync habits with Google Calendar for scheduling
- **Notion Calendar**: Log habit progress in a Notion database
- Integrated API endpoints for seamless connectivity

### 🏫 College Attendance Tracker
- Log attended and skipped classes
- View attendance statistics
- Monitor trends over time
- Generate reports on class participation

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
