# MERN-Stack Boilerplate

!Boilerplate

## Features

- User Authentication:
  - Login
  - Signup
  - Forgot Password
  - Reset Password via Email
- User Management:
  - User Profiles
  - All Users Profile Page
  - User Role Management
  - Permissions Management
  - Roles Management
- Additional Features:
  - Welcome Page
  - Pagination
  - Search

## Technologies Used

This boilerplate leverages a variety of technologies:

- Nodemailer
- MongoDB
- React.js
- Moment.js
- React Query
- Axios
- react-confirm-alert
- Bootstrap v5
- React-Hook-Form
- Yandex Mail
- react-icons
- And more...

## Installation

To run this NEXT.js boilerplate, ensure you have the following technologies installed:

- [Node.js](https://nodejs.org/) v12+
- [MongoDB](https://mongodb.com/) (either local MongoDB or MongoDB Atlas)

Follow these steps to set up the project:

```sh
cd MERN-Stack-Boilerplate
cd frontend && npm install
cd ../backend && npm install
npm run dev
```

### Seeding Default Data

To insert default seed data, copy and paste the following URL into your browser's address bar:

```sh
http://localhost:5000/api/auth/seed?secret=js
```

You can find the default `super admin` credentials in the following directory:

```sh
/backend/src/config/data.js
```

### Default Super Admin Credentials

- **Email:** _raushang4@gmail.com_
- **Password:** _123456_

**_Free NEXT.js Boilerplate by raushang4!_**