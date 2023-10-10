# StudyNotion
StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

StudyNotion aims to provide:
- A seamless and interactive learning experience for students, making education more accessible and engaging.
- A platform for instructors to showcase their expertise and connect with learners across the globe.




## Features ✨

- *User authentication and authorization*: Students and instructors can signd up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification  forgot password functionality for added security.
- *Course management*: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
- *Payment Integration*: Students will purchase and enroll on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.
- *Cloud-based media management*: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
- *Markdown formatting*: Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.


## Table of Contents

System Architecture. 
Front-end.
Back-end.
API Design.
Deployment.
Testing.
Future Enhancements.
System Architecture.

## Front-end
The front end is built using ReactJS, enabling dynamic and responsive user interfaces for an engaging learning experience. It communicates with the back end through RESTful API calls.

The StudyNotion front end is designed using Figma, offering a clean and minimal user interface. It includes various pages for students, instructors, and future admin features. Some key pages are:

Homepage
Course List
Wishlist
Cart Checkout
Course Content
User Details
User Edit Details
Dashboard (for instructors)
Insights (for instructors)
Course Management Pages (for instructors)
View and Edit Profile Details (for instructors)
Dashboard (for admin, future scope)
Insights (for admin, future scope)
Instructor Management (for admin, future scope)
Frameworks and libraries such as ReactJS, CSS, Tailwind, Redux, and VSCode are used for front-end development.

## Back-end
The back end is developed with NodeJS and ExpressJS, providing APIs for user authentication, course management, and content processing. It also incorporates MongoDB for flexible data storage and retrieval.

The StudyNotion back end follows a monolithic architecture, utilizing Node.js, Express.js, and MongoDB. Key features include:

User authentication and authorization
Course management
Payment integration (Razorpay)
Cloud-based media management (Cloudinary)
Markdown formatting for course content
Frameworks, libraries, and tools used include Node.js, MongoDB, Express.js, JWT, Bcrypt, and Mongoose. Data models encompass student schema, instructor schema, and course schema.

## Database
MongoDB serves as the NoSQL database, accommodating unstructured and semi-structured data, including course content like videos, images, and PDFs.


## API Design

StudyNotion's API adheres to the REST architectural style, implemented using Node.js and Express.js. It uses JSON for data exchange and supports standard HTTP request methods. Sample API endpoints include:

-/api/auth/signup (POST)
-/api/auth/login (POST)
-/api/auth/verify-otp (POST)
-/api/auth/forgot-password (POST)
-/api/courses (GET, POST)
-/api/courses/:id (GET, PUT, DELETE)
-/api/courses/:id/rate (POST)
Sample API requests and responses are provided for each endpoint, ensuring seamless communication between front end and back end.



With StudyNotion, we aim to revolutionize the ed-tech landscape by providing a user-friendly, interactive, and comprehensive platform for both students and instructors. The project is a continuous endeavor, with a focus on innovation and delivering a top-notch learning experience.



