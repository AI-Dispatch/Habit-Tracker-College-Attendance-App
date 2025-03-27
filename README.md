# AI Dispatch - README

## Overview
AI Dispatch is an AI-powered newsletter platform designed to deliver the latest insights in artificial intelligence, technology, and innovation. The platform includes an advanced admin dashboard, subscriber management, blog publishing, and user authentication features.

<img width="618" alt="Screenshot 2025-03-27 at 12 41 00 PM" src="https://github.com/user-attachments/assets/89a86248-9a09-4c30-adf4-2a6692c04099" />


## Features

### 1. User Authentication & Account Management
- User registration with secure password hashing
- User login with JWT token authentication
- User profile management
- Protected routes requiring authentication
- Test token generation for development



### 2. Habit Tracking System
- Create, view, update, and delete habits
- Custom habit categories with color coding
- Habit tagging for better organization
- Daily, weekly, and monthly habit frequency options
- Habit completion tracking with statistics
- Habit streak monitoring
- Habit record management with notes

<img width="923" alt="Screenshot 2025-03-26 at 11 30 00 PM" src="https://github.com/user-attachments/assets/8fbb28e9-73cb-45cf-b4cd-e3065b23ced9" />


### 3. College Class Management
- Add and manage college classes
- Schedule classes with recurring day/time settings
- Track class attendance (attended/skipped)
- View attendance statistics and reports
- Associate classes with habits or meetings

<img width="920" alt="Screenshot 2025-03-26 at 11 30 22 PM" src="https://github.com/user-attachments/assets/2bbea7f3-5425-4aa2-b09a-bae413449f11" />


### 4. Meeting Integration
- Schedule virtual meetings (Zoom, Google Meet, etc.)
- Meeting templates for quick scheduling
- Create meetings from templates
- Meeting participant management
- Meeting categorization by type and platform
- Meeting status tracking (scheduled, completed, canceled)
- Associate meetings with habits or college classes



### 5. Calendar Integration
- Google Calendar synchronization for habits and meetings
- Notion Calendar integration
- Two-way calendar sync capabilities
- Google OAuth authentication flow

<img width="921" alt="Screenshot 2025-03-26 at 11 30 07 PM" src="https://github.com/user-attachments/assets/74d2e64f-d126-4082-819f-a5f486239e6e" />


### 6. Notification System
- WhatsApp notifications via Twilio integration
- Email notifications
- Configurable notification preferences
- Notification settings by feature (habits, classes, meetings)
- Configurable reminder times

### 7. Visualization & Statistics
- Habit completion tracking visualizations
- Class attendance statistics
- Meeting trends and analytics
- Data visualization components for performance tracking
- Calendar view of all scheduled activities

### 8. User Interface
- Modern, responsive design
- Dark/light theme options
- Mobile-friendly layout
- Easy navigation between features
- Interactive dashboard with summary statistics
- Beautiful UI components using shadcn/ui

### 9. Security Features
- JWT-based authentication
- Password hashing with bcrypt
- Protected API endpoints
- Secure credential management for third-party services
- Optional authentication middleware

### 10. Data Management
- In-memory storage with persistence
- Data validation using Zod schemas
- Type-safe data operations
- Efficient data querying with filtering options

## Installation
### Prerequisites
- Node.js (latest LTS version)
- PostgreSQL or any preferred database
- Redis (for caching and queue management)

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/ai-dispatch.git
   cd ai-dispatch
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up the environment variables:
   - Copy `.env.example` to `.env`
   - Configure database credentials, API keys, and other environment settings
4. Run database migrations:
   ```sh
   npx prisma migrate dev
   ```
5. Start the development server:
   ```sh
   npm run dev
   ```

## Deployment
- Deploy using Docker:
  ```sh
  docker-compose up -d
  ```
- CI/CD pipeline integration for automatic deployments

## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License.

## 📬 Contact
For any queries, reach out to **V Chaitanya Chowdari** via:
- 🌐 [LinkedIn](https://www.linkedin.com/in/v-chaitanya-chowdari-bb3733202)
- 📩 [Email](mailto:vchaitanyachowdari@gmail.com)
