# Campus Recruitment Management Portal

A full-stack placement portal built for managing student profiles, recruitment drives, job applications, notices, and placement records.

---

## Project Overview

This repository contains a placement portal with separate `client` and `server` applications:

- `client/` - React + Vite frontend for students, admins, and recruiters.
- `server/` - Node.js + Express backend with MongoDB for data storage.

---

## Key Features

- User authentication and role-based access
- Job posting and application management
- Student placement records and company tracking
- Noticeboard and query/forum management
- No dues request handling
- Admin dashboard and recruiter workflows

---

## Tech Stack

### Frontend
- React
- Vite
- JavaScript
- Tailwind CSS / CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Additional Services
- Cloudinary (file uploads)
- Clerk Authentication / Custom Auth Middleware

---

## Repository Structure

```bash
Campus-Recruitment-Management-Portal/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── context/
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   └── routes/
│
├── README.md
└── scratch.js
```

---

## Setup Instructions

### 1. Backend Setup

Open terminal inside the `server/` folder:

```bash
cd server
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your-mongodb-connection-string
CLOUDINARY_CLOUD_NAME=your-cloud-name
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret
```

Start backend server:

```bash
npm run dev
```

---

### 2. Frontend Setup

Open terminal inside the `client/` folder:

```bash
cd client
npm install
```

Create `.env` or `.env.local` if required.

Start frontend server:

```bash
npm run dev
```

---

## Usage

- Frontend usually runs on:

```bash
http://localhost:5173
```

- Backend API usually runs on:

```bash
http://localhost:5000
```

Use the login/dashboard flows for:
- Students
- Admins
- Recruiters

---

## Notes

- Ensure MongoDB is running and accessible.
- Verify Cloudinary credentials before testing uploads.
- `scratch.js` is used for local database testing.

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a pull request

---

## License

This project is provided for academic and demonstration purposes.
