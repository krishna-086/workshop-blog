# Blog Website

This project is a fully functional blog website created as part of a web development workshop conducted during Aurora Techweek 2025. The blog allows users to create, edit, and delete posts while interacting with a real-time database using Firebase. The frontend is built using HTML, CSS, and JavaScript, while the backend leverages Firebase for database.

## Features

- **Create, Edit, and Delete Posts:** Users can write and manage blog posts.
- **Real-time Database:** Firebase integration for real-time storage and retrieval of blog data.
- **Authentication:** User authentication through Firebase to manage user access.
- **CRUD Operations:** Full implementation of Create, Read, Update, and Delete operations.
- **Responsive Design:** Works seamlessly across devices with a responsive design.

## Technologies Used

- **HTML & CSS:** For structuring and styling the frontend.
- **JavaScript:** For DOM manipulation, asynchronous operations (using promises and async/await), and frontend logic.
- **Firebase:** For real-time database
  
## Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/krishna-086/workshop-blog.git
2. Navigate to the project directory:
    ```bash
    cd workshop-blog
    ```
3. Add your Firebase configuration in `app.js`
4. Open the `index.html` file in a browser or use a live server.

## Firebase Setup

To connect the project to your Firebase account:

1. Create a Firebase project on [Firebase Console](https://console.firebase.google.com/).
2. Enable Firestore Database.
3. Generate Firebase configuration and replace the existing configuration in `app.js` with your Firebase config.
4. Deploy the website using github pages or any other static website hosting service.

## Usage

- Users can create new blog posts by entering content in the form and submitting it.
- The posts will be stored in the Firebase real-time database.

## Live Demo

Check out the live demo here: [Blog Website](https://workshopblog.netlify.app/)

