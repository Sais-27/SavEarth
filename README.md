# Prithvi

Prithvi is a full-stack web application built on the PERN stack (PostgreSQL, Express, React, Node.js) designed to help households and businesses calculate their carbon footprints. This project was developed as a college project to promote environmental awareness and action.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Motivation](#motivation)
- [License](#license)

## Introduction

Prithvi allows users to calculate their carbon footprint based on various parameters. It provides detailed insights and suggestions on how to reduce their carbon emissions.

## Watch the Demo Video

[Watch the video](https://youtu.be/NNUIMpyxhGg)
## Features

- User authentication and authorization
- Carbon footprint calculator for households and businesses
- Detailed reports and donut chart representation.
- Responsive design for all devices
- User-friendly interface

## Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Hosting**: Render
- **Version Control**: Git, GitHub

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone (https://github.com/Sais-27/SavEarth.git)
   ```

2. Navigate to the project directory:

   ```bash
   cd prithvi
   ```

3. Install backend dependencies:

   ```bash
   npm install
   ```

4. Install frontend dependencies:

   ```bash
   cd ./client
   npm install
   ```

5. Set up environment variables:

   Create a `.env` file in the `server` directory and add your database details:

   ```env
   PG_USER=your_user_name
   PG_HOST=your_host_name
   PG_DATABASE=your_database_name
   PG_PASSWORD=your_password
   PG_PORT=5432
   SESSION_SECRET=your_secret
   MAIL=your_mail
   APP_PASSWORD=your_app_password
   ADMIN_MAIL=admin_mail
   ADMIN_PASS=admin_password
   GEMINI_API_KEY=your_api_key
   OAUTH_CLIENT_ID=your_client_id
   OAUTH_SECRET=your_secret
   
6. Start the backend server:

   ```bash
   cd ./server
   node index.js
   ```

7. Start the frontend development server:

   ```bash
   cd ./client
   npm run dev
   ```

8. Open your browser and navigate to `http://localhost:5173`.
    
## Usage

1. Register a new account or log in with an existing account.
2. Choose whether you want to calculate the carbon footprint for a household or a business.
3. Fill in the required information in the form.
4. View the calculated carbon footprint and suggestions for reducing emissions.
## Collaborators

Thanks to the following people who have contributed to this project:

- [Collaborator1](https://github.com/k-agg17)

## Motivation

It was a hackathon project and the motivation behind Prithvi is to provide a tool that helps individuals and businesses become more aware of their environmental impact. By understanding their carbon footprint, users can take actionable steps towards reducing their emissions and contributing to a healthier planet.
