#   📝 Event Manager - React & Node.js Project with Token-Based Authentication & Routing

### 👀 Project Overview

This project is a full-stack Event Manager application built with React on the frontend and Node.js on the backend.

It demonstrates routing, authentication, and event management features.

Users must log in to access and manage events. Authentication is handled using token-based authentication (JWT).

Tokens expire after 1 hour, automatically logging out the user to ensure security.

### 🔐 Features

Authentication with JWT Tokens:

* Users can sign up and log in.

* On successful login, the backend issues a JWT token.

* The frontend stores the token and attaches it to API requests.

* Tokens expire after 1 hour, triggering automatic logout.

* Invalid login attempts show clear error messages.

### Protected Routes:

Only authenticated users with valid tokens can access the event management dashboard.

Unauthorized access attempts show error messages and redirect to login.

### Event CRUD Operations:

#### Authenticated users can:

* Create new events

* Edit existing events

* Delete events

All event data is managed through REST API calls to the Node.js backend.

### 🚀 Tech Stack

* Frontend: React, React Router, Axios (for REST API calls), JWT token handling

* Backend: Node.js, Express.js, JSON Web Tokens (JWT)

* Authentication: JWT with token expiration

### ⚠️ Notes

* The JWT token stored in the frontend expires after 1 hour, after which users are automatically logged out.

* REST API calls include the token in the Authorization header to validate user access.

* Invalid credentials or expired tokens result in error messages and restricted access.

### ✅ How to Run Locally

###### Backend: Navigate to backend folder:

###### `cd backend`

###### Install dependencies: 

###### `npm install`

###### Start the server:

###### `npm start`

###### **_Frontend:_** Navigate to frontend folder:

###### `cd frontend`

###### Install dependencies:

###### `npm install`

###### Start the React app:

###### `npm start`

###### Open http://localhost:3000 in your browser.

