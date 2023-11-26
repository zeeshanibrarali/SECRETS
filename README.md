# Secrets Sharing Web App

Welcome to the Secrets Sharing Web App! This web application, inspired by the concept of Whisper, provides users with a platform to share their secrets either anonymously or through their Google accounts. Users can register, log in, share their secrets, and explore secrets shared by others.

## Introduction

The Secrets Sharing Web App draws inspiration from the Whisper app and extends its functionality by allowing users to share secrets anonymously or via their Google accounts. Built on Node.js, Express, and MongoDB, this application provides a secure and interactive space for sharing and discovering secrets.

## Prerequisites

Ensure you have the following installed before running the project:

- Node.js
- MongoDB
- npm (Node Package Manager)

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/secrets-sharing-app.git

2. **dependencies:**
   
```bash
cd secrets-sharing-app
npm install
```
3. **Configure Environment Variables**
CLIENT_ID=your_google_client_id
CLIENT_SECRET=your_google_client_secret


## Run the application:

```bash
npm start
```
Open your browser and go to http://localhost:3000.

## Features

- User authentication using both local strategy (username and password) and Google OAuth 2.0
- Anonymous secret sharing
- Viewing shared secrets
- Logout functionality
  
## Dependencies
- Express
- Mongoose
- Passport
- Passport-local
- Passport-local-mongoose
- Passport-google-oauth20
- Mongoose-findorcreate

## Secreenshots
### MAIN PAGE
![Home page](./screenshots/Home%20Page.PNG)
### LOGIN PAGE
![login page](./screenshots/login%20page.PNG)
### NEW SECRET PAGE
![secret](./screenshots/new%20secret.PNG)


