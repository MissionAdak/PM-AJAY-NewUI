<<<<<<< HEAD
# PM-AJAY Agency Mapping System

A modern, responsive website for mapping and managing implementing and executing agencies across PM-AJAY components. Built for Smart India Hackathon 2024.

## 🎯 Features

- **Agency Mapping**: Manage implementing and executing agencies with CRUD operations
- **Fund Tracker**: Monitor fund allocation and utilization with progress visualization
- **Communication Hub**: Task-based communication system for inter-agency coordination
- **Reports Dashboard**: Comprehensive analytics and performance metrics
- **Modern UI**: Clean, government-tech aesthetic with smooth animations
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🚀 Tech Stack

### Frontend
- React 18 with Vite
- Tailwind CSS for styling
- Framer Motion for animations
- React Router DOM for navigation
- Recharts for data visualization
- Axios for API calls
- Lucide React for icons

### Backend
- Node.js with Express.js
- SQLite database
- CORS enabled for frontend communication
- RESTful API endpoints

## 📦 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Start the server:
```bash
npm start
```

The backend server will run on `http://localhost:5000`

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The frontend will run on `http://localhost:3000`

## 🗄️ Database

The application uses SQLite database with the following tables:
- `agencies`: Stores agency information
- `funds`: Stores fund allocation and utilization data
- `tasks`: Stores task-based communication data

Sample data is automatically inserted when the server starts.

## 📡 API Endpoints

### Agencies
- `GET /api/agencies` - Get all agencies
- `POST /api/agencies` - Create new agency
- `PUT /api/agencies/:id` - Update agency
- `DELETE /api/agencies/:id` - Delete agency

### Funds
- `GET /api/funds` - Get all fund records
- `POST /api/funds` - Create new fund record
- `PUT /api/funds/:id` - Update fund record
- `DELETE /api/funds/:id` - Delete fund record

### Tasks
- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create new task
- `PUT /api/tasks/:id` - Update task
- `DELETE /api/tasks/:id` - Delete task

### Dashboard
- `GET /api/dashboard/stats` - Get dashboard statistics

## 🎨 Design Features

- **Government Tech Aesthetic**: Blue (#0057A3) and white color scheme
- **Smooth Animations**: Framer Motion for hover effects and transitions
- **Responsive Layout**: Mobile-first design with Tailwind CSS
- **Interactive Components**: Cards, modals, and form elements
- **Data Visualization**: Charts and progress bars for better insights

## 🔧 Development

### Project Structure
```
pm-ajay-system/
├── backend/
│   ├── server.js
│   ├── package.json
│   └── pm_ajay.db (SQLite database)
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
└── README.md
```

### Key Components
- **Navbar**: Responsive navigation with mobile menu
- **Footer**: Contact information and quick links
- **Home**: Hero section with feature overview
- **Agencies**: Agency management with search and filter
- **Funds**: Fund tracking with progress visualization
- **Communication**: Task-based messaging system
- **Reports**: Analytics dashboard with charts

## 🚀 Deployment

The application is designed to run locally and can be deployed to any Node.js hosting platform.

### Environment Variables
No environment variables are required for local development.

### Database
The SQLite database file (`pm_ajay.db`) will be created automatically in the backend directory.

## 📱 Mobile Responsiveness

The application is fully responsive and optimized for:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## 🎯 Unique Features

### Task-based Communication Hub
Unlike typical dashboards, this system includes a unique task-based communication system where agencies can:
- Assign tasks to other agencies
- Track task progress and deadlines
- Update task status (Pending, In Progress, Completed)
- Set task priorities (High, Medium, Low)
- View overdue tasks

## 🤝 Contributing

This project was built for Smart India Hackathon 2024. For any issues or suggestions, please contact the development team.

## 📄 License

This project is developed for educational purposes as part of Smart India Hackathon 2024.

---

**Built with ❤️ for Smart India Hackathon 2024**
=======
# PM-AJAY
>>>>>>> 029530f679bdbba405b5a4aa5702587150705bfa
