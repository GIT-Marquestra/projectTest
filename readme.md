# EmployWise User Management System

A React-based user management system built with TypeScript, Tailwind CSS, and React Router. This application integrates with the Reqres API to provide user authentication and management capabilities.

## Features

- 🔐 User Authentication
  - Secure login system
  - Token-based authentication
  - Protected routes

- 👥 User Management
  - View paginated list of users
  - Edit user details
  - Delete users
  - Search and filter users

- 🎨 Modern UI/UX
  - Responsive design
  - Clean and intuitive interface
  - Loading states and transitions
  - Toast notifications

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- React Router v6
- Axios
- React Hot Toast
- Lucide React Icons
- Vite

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd employwise-assignment
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

## Usage

### Authentication

Use the following credentials to log in:
- Email: eve.holt@reqres.in
- Password: cityslicka

### Features

1. **User List**
   - View all users in a paginated table
   - Search users by name or email
   - Navigate through pages of users

2. **User Management**
   - Edit user details (first name, last name, email)
   - Delete users with confirmation
   - Instant feedback with toast notifications

3. **Navigation**
   - Protected routes for authenticated users
   - Automatic redirect to login for unauthenticated users
   - Clean URL structure

## API Integration

This project uses the Reqres API (https://reqres.in/) for:
- User authentication
- User data management
- CRUD operations

## Project Structure

```
src/
├── components/        # Reusable components
├── pages/            # Page components
├── services/         # API services
├── types/            # TypeScript interfaces
└── App.tsx           # Main application component
```

## Error Handling

- Form validation on all inputs
- API error handling with user feedback
- Protected route authentication
- Loading states for async operations

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.