# Let-stalk
>>>>>>> origin/main
# Let's Talk - MERN Chat Application

Let's Talk is a Full Stack Real-time Chatting Application built with the MERN stack. It uses Socket.io for real-time communication and stores user details securely in MongoDB.

## Tech Stack

**Client:** React JS

**Server:** Node JS, Express JS

**Database:** MongoDB

## Features

### Authentication
- User signup and login
- JWT token-based authentication
- Secure password hashing

### Real-time Communication
- Instant messaging with Socket.io
- Typing indicators
- Online/offline status

### Chat Features
- One-to-one private chats
- Group chat creation
- Search users functionality
- Add/remove users from groups
- User profile viewing

### Notifications
- Real-time message notifications
- Group chat notifications

## Run Locally

Clone the project

```bash
  git clone https://github.com/Rishu1724/Let-stalk.git
```

Go to the project directory

```bash
  cd Let-stalk
```

Install dependencies

```bash
  npm install
```

```bash
  cd frontend/
  npm install
```

Set up environment variables:
- Create `.env` file in backend directory
- Add your MongoDB URI and PORT

Start the server

```bash
  npm run server
```

Start the Client

```bash
  //open new terminal
  cd frontend
  npm start
```

## Environment Variables

Create a `.env` file in the backend directory with:

```
MONGO_URI=your_mongodb_connection_string
PORT=8080
JWT_SECRET=your_jwt_secret
```

## Author

**Rishu Kumar**

[GitHub Profile](https://github.com/Rishu1724)
=======
# Let-stalk
>>>>>>> origin/main
