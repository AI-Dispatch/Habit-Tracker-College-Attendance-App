# Contributing to the Habit Tracker App

Thank you for your interest in contributing to the **Habit Tracker App**! This project aims to provide a seamless habit tracking experience with visualization features, Google Calendar and Notion integration, attendance tracking, and optional WhatsApp notifications.

## Project Features
- **Visual Habit Tracking**: Track habits and routines with customizable visualizations.
- **Google Calendar & Notion Integration**: Sync habits and routines for better organization.
- **College Attendance Tracking**: Monitor attended and skipped classes.
- **WhatsApp Notifications (Optional)**: Receive reminders and updates via WhatsApp.

---

## Getting Started

### Prerequisites
Ensure you have the following installed:
- **Node.js** & **npm**
- **Google Cloud Console account** (for Google Calendar integration)
- **Notion API credentials** (for Notion integration)
- **Twilio account** (for WhatsApp notifications)

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/vchaitanyachowd/habit-tracker-app.git
   cd habit-tracker-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

---

## Contribution Guidelines

### 1. Reporting Issues
If you find bugs, report them in the **Issues** section with:
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots/logs (if applicable)

### 2. Feature Requests
Before suggesting a new feature, check if it already exists. If not, create an issue with:
- Feature description
- Use cases & benefits

### 3. Submitting Pull Requests
1. **Fork the repository** and create a feature branch:
   ```sh
   git checkout -b feature-name
   ```
2. **Commit changes**:
   ```sh
   git commit -m "Added feature: XYZ"
   ```
3. **Push the branch**:
   ```sh
   git push origin feature-name
   ```
4. **Create a Pull Request** and describe your changes.

---

## API Credentials
### Google Calendar
To enable Google Calendar sync, add the following to `.env`:
```
GOOGLE_CLIENT_ID=your-client-id
GOOGLE_CLIENT_SECRET=your-client-secret
GOOGLE_REDIRECT_URI=http://localhost:5000/api/auth/google/callback
```

### Notion Integration
```
NOTION_API_KEY=your-api-key
NOTION_DATABASE_ID=your-database-id
```

### Twilio (For WhatsApp Notifications - Optional)
```
TWILIO_ACCOUNT_SID=your-account-sid
TWILIO_AUTH_TOKEN=your-auth-token
TWILIO_PHONE_NUMBER=your-whatsapp-number
```

---

## Feature Contributions

### Habit Tracking
- Improve visualization options
- Add habit categorization & tagging

### College Attendance Tracking
- Add more statistics (weekly/monthly trends)
- Introduce reminders for upcoming classes

### WhatsApp Notifications
- Customize message templates
- Enable reminders for multiple users

---

## Questions?
If you have any questions, feel free to open an issue or reach out to the project maintainer.

Happy coding! 🚀


