# Fullstack MERN Blogging Website

Fork this repo of "MERN Blogging Website" to start following the video tutorial.

Checkout website demo - [Demo](https://youtu.be/J7BGuuuvDDk)

![Thumbnail](https://c10.patreonusercontent.com/4/patreon-media/p/post/90122909/dd5363bd03fb4a6c8fcd5d15df98e6bf/eyJ3Ijo4MjB9/1.png?token-time=1697414400&token-hash=BZ-Mzp19WnBLcCFB8LmJFDw98mpnCRGcOCt_T615miY%3D)

Features
1. Modern Blog Editor
Powered by Editor.js, a rich text editor that supports various content blocks like paragraphs, headings, images, lists, quotes, and embeds.

Real-time preview of blog content while editing.

2. User Authentication
Google Authentication: Users can sign up and log in using their Google accounts.

Email/Password Authentication: Traditional sign-up and login options are also available.

Secure password storage using bcrypt for hashing.

3. Dynamic Blog Pages
Each blog is assigned a unique, dynamic URL for easy sharing and accessibility.

Blogs are rendered dynamically with proper SEO-friendly metadata.

4. Search Functionality
A dedicated Search Page allows users to search for blogs and other users.

Real-time search results with filters for blogs and users.

5. User Profiles
Dedicated profile pages for each user, showcasing:

Social links (e.g., GitHub, LinkedIn, Twitter).

Bio and username.

List of published and draft blogs.

Users can edit their profiles to update social links, bio, and username.

6. Dashboard for Blog Management
A personalized dashboard for users to manage their blogs.

Features include:

Viewing published and draft blogs.

Editing or deleting existing blogs.

Analytics for each blog (e.g., views, likes, comments).

7. Blog Interactions
Like Feature: Users can like blogs to show appreciation.

Comment System:

Users can comment on blogs.

Nested replies to comments for engaging discussions.

Notifications:

Every interaction (likes, comments, replies) generates a notification for the respective user.

Notifications are categorized into Recent and Old for better organization.

8. Blog Analytics
Detailed analytics for each blog post, including:

Number of views.

Number of likes and comments.

Users can track the performance of their blogs over time.

9. Profile Settings
Users can update their profile information, including:

Social links.

Bio and username.

Change Password: Users can update their login password securely.

10. Mobile Responsiveness
The website is fully responsive, ensuring a smooth experience across all devices (desktop, tablet, mobile).

Modern design with fade-in animations for a polished user experience.

11. Additional Features
Draft System: Save blogs as drafts and publish them later.

Pagination: Blogs are paginated for better performance and usability.

SEO Optimization: Blogs are optimized for search engines with proper metadata and dynamic URLs.

Tech Stack
Frontend
React.js: For building a dynamic and interactive user interface.

React Router: For seamless navigation and dynamic routing.

Context API/Redux: For state management.

Axios: For making API requests to the backend.

Editor.js: For the modern blog editor.

React Icons: For a clean and consistent icon set.

Framer Motion: For animations and transitions.

Backend
Node.js: For building the server.

Express.js: For creating RESTful APIs.

MongoDB: For database management.

JWT (JSON Web Tokens): For secure user authentication and authorization.

Google OAuth: For Google authentication.

bcrypt: For password hashing.

Deployment
Backend deployed on Heroku or Render.

Frontend hosted on Netlify or Vercel.

Database hosted on MongoDB Atlas for cloud-based storage