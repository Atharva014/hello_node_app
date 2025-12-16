# Hello ECR App

A simple Node.js REST API built with Express.

## Tech Stack
- Node.js
- Express.js
- Docker

## Run Locally
```bash
npm install
node app.js
```

App runs on `http://localhost:3000`

## Docker

**Build image:**
```bash
docker build -t hello-ecr-app:v1.0 .
```

**Run container:**
```bash
docker run -d -p 3000:3000 hello-ecr-app:v1.0
```

## API Endpoints

- `GET /` - Returns welcome message
- `GET /health` - Health check endpoint