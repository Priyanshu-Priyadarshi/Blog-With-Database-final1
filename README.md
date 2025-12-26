# Daily Journal

Daily Journal is a web application that allows users to create, read, and manage blog posts. Built using Node.js, Express, MongoDB, and EJS, this project demonstrates a full-stack implementation of a blogging platform.

## Features

- **User Authentication**: Register and log in to access personalized features.
- **Compose Posts**: Create new blog posts with a rich text editor.
- **Dynamic Home Page**: Displays all posts with a "Read More" option for detailed views.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Pagination**: Navigate through posts efficiently.
- **Professional Styling**: Includes animations, gradients, and modern UI elements.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: EJS (Embedded JavaScript Templates), CSS
- **Database**: MongoDB
- **Styling**: Bootstrap, Custom CSS

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Priyanshu-Priyadarshi/Blog-With-Database-final1.git
   ```
2. Navigate to the project directory:
   ```bash
   cd daily-journal
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the MongoDB server locally.
5. Run the application:
   ```bash
   node app.js
   ```
6. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Project Structure

```
Daily-Journal/
├── app.js               # Main application file
├── package.json         # Project metadata and dependencies
├── public/              # Static files (CSS, images, etc.)
│   ├── css/
│   │   └── styles.css   # Custom styles
├── views/               # EJS templates
│   ├── home.ejs         # Home page
│   ├── post.ejs         # Post details page
│   ├── compose.ejs      # Compose new post
│   ├── partials/        # Header and footer templates
├── README.md            # Project documentation
```

## Routes

- `GET /` - Redirects to the login page.
- `GET /home` - Displays all blog posts.
- `GET /compose` - Form to create a new post.
- `POST /compose` - Saves a new post to the database.
- `GET /posts/:postId` - Displays a specific post.
- `GET /login` - Login page.
- `GET /register` - Registration page.


