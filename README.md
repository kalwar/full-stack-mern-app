# Full-stack-MERN-App

A simple full-stack-mern bookstore app used for learning cloud database concepts

## Getting Started

You must have mongodb account profile.

### Prerequisites

What things you need to install the application and how to install them

```
sudo npm install -g nodemon
```

### Installing

Go to backend folder and install dependencies

```
cd backend
npm i
```

And move back to frontend folder

```
cd ..
cd frontend
npm i
```

Now go to the root of the folder and run

```
cd ..
npm i
npm start
```

### MongoDB Cloud Database connection

- Go to mongodb.com
- Setup your account, profile
- Use free database tier for learning and exploring mongodb
- Give clustername --> hit on Create button
- Setup username and password (Do not commit these info in github)
- Click on Finish and Close
- Select/Click on "Connect" button
- Select/Click on "Driver"
- Add your connection string into your application code inside backend --> config.js --> mongoDBURL

### Linting

To check for linting issues, you can go to frontend folder
and run

```
npm run lint
```

## Local Deployment

The application can be accessed locally from following address

```
http://localhost:5173/
```

## Built With

- [React](https://react.dev/) - The library for web and native user interfaces
- [MySQL](https://www.mysql.com/) - The world's most popular database
- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [MongoDB](https://mongodb.com/) - NoSQL database
- [Vite](https://vitejs.dev/) - Dev environment for front-end

## Use as reference material

Please use as a reference material

## References

- [MERN Stack](https://www.mongodb.com/mern-stack)
- [Postman](https://www.postman.com/)
- [MERN Stack Tutorial - Book Store Project](https://www.youtube.com/watch?v=-42K44A1oMA)
- [MongoDB Cloud DB](https://mongodb.com)
