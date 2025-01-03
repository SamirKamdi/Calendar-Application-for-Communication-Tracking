# Calendar-Application-for-Communication-Tracking

## Overview
This project is a React-based Calendar Application designed to help maintain strong professional relationships by tracking communications with various companies. It provides a centralized platform for logging past interactions, planning future communications, and managing engagement frequency.

## Features
- **Admin Module**: Manage and monitor the overall communication system.
- **User Module**: View and manage personal communication data and calendar.
- **Responsive Design**: Access the app seamlessly on any device.
- **Clear Separation of User Roles**: Different functionality for admins and regular users.

## Technologies Used
- **React.js**: Frontend framework for building dynamic user interfaces.
- **React Router**: For handling navigation and routing within the app.
- **TypeScript**: To ensure type safety across the application.
- **CSS**: Styling for the application components.

## Project Structure
```
communication-tracking-calendar/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── AdminModule/
│   │   │   ├── AdminModule.tsx
│   │   │   ├── CommunicationMethodManagement.tsx
│   │   │   ├── CommunicationMethodManagement.css
│   │   │   ├── CompanyManagement.tsx
│   │   │   └── CompanyManagement.css
│   │   ├── UserModule/
│   │   │   ├── CalendarView.tsx
│   │   │   ├── CalendarView.css
│   │   │   ├── CommunicationAction.tsx
│   │   │   ├── CommunicationAction.css
│   │   │   ├── Dashboard.tsx
│   │   │   ├── Dashboard.css
│   │   │   ├── index.tsx
│   │   │   ├── Notifications.tsx
│   │   │   └── UserModule.css
│   │   ├── Common/
│   │   │   ├── Footer.tsx
│   │   │   ├── Footer.css
│   │   │   ├── Header.tsx
│   │   │   ├── Header.css
│   │   │   └── Sidebar.tsx
│   │   ├── ReportingModule/
│   │   │   ├── CommunicationFrequencyRepost.tsx
│   │   │   ├── DownloadableReports.tsx
│   │   │   ├── OverdueCommunicationTrends.tsx
│   │   │   └── RealTimeActivityLog.tsx
│   ├── services/
│   │   ├── api.ts
│   │   └── index.ts
│   ├── styles/
│   │   ├── App.css
│   │   └── index.css
│   ├── utils/
│   │   ├── App.css
│   │   ├── App.tsx
│   │   └── index.tsx
│   ├── App.css
│   ├── App.tsx
│   ├── index.tsx
│   ├── react-app-env.d.ts
│   └── serviceWorker.ts
├── .gitignore
├── package.json
├── README.md
└── tsconfig.json

```

## Setup Instructions
1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd calendar-app
   ```

2. **Install dependencies**:
   ```
   npm install
   ```

3. **Run the application**:
   ```
   npm start
   ```
   The application will be available at `http://localhost:3000`.

## Functionality
- **Admin Module**: Admins can add, edit, and delete companies and communication methods.
- **User Module**: Users can view company communications, log new communications, and manage notifications.
- **Calendar View**: Users can visualize past and upcoming communications.

## Known Limitations
- The Reporting and Analytics Module is optional and may not be fully implemented.
- User authentication is not included in this version.

## Future Enhancements
- Implement user authentication and role management.
- Enhance the Reporting and Analytics Module with more detailed insights.

## License
This project is licensed under the MIT License.
