# Messenger 

A real-time messaging web application built with React, Vite, Express, MongoDB, and Socket.IO. Users can sign up, chat with others, and send text or images in real-time. Either locally or https://messenger-esbc.onrender.com

## Features

- User authentication (signup/login)
- Real-time messaging with Socket.IO
- Send text and images
- Responsive UI with Tailwind CSS & daisyUI
- REST API for messages and users

## Tech Stack

- Frontend: React, Vite, TailwindCSS, daisyUI
- Backend: Node.js, Express, MongoDB, Mongoose
- Real-time: Socket.IO
- Cloud Storage: Cloudinary

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
