# Learning Management System (LMS) - MERN Stack

This repository contains a complete Learning Management System (LMS) built using the MERN stack. It features both Instructor Panel and Student Panel, allowing instructors to manage courses and students to enroll and purchase courses securely using PayPal (Sandbox mode). Video lectures and course materials are uploaded and streamed via Cloudinary, while MongoDB Atlas handles secure data storage.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The LMS offers a professional online learning platform where:

- Instructors can create, manage, and publish video-based courses.

- Students can browse courses, purchase them via PayPal, and access learning materials.

- The platform handles secure file uploads (video lectures) to Cloudinary and manages course, user, and payment data in MongoDB Atlas.

## Installation

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Learning-Management-System-MERN-Stack.git
```

2. Backend Setup:

```
   cd server
   npm install

```

3. Set up environment variables by creating a .env file (Use .env.sample as a reference for setting up your .env file.)

4. Start the backend:

```
   npm run dev

```

4. Frontend Setup:

```
   cd ../client
   npm install
   npm run dev

```

## Usage

- Access the application at http://localhost:5173

- Instructor Panel and User Panel are accessible based on login roles.

- Users can browse courses and purchase via PayPal Sandbox.

- Instructors can upload video lectures directly to Cloudinary.

- Purchased courses are available for streaming to the user.
