![logo](https://github.com/patelsa54/StudyNotion/assets/115445118/cd1f04f4-d7c0-4e3f-9840-4c8edf92a38d)
# An Ed-tech Platform
StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.
StudyNotion aims to provide:
− A seamless and interactive learning experience for students, making education
more accessible and engaging.
− A platform for instructors to showcase their expertise and connect with learners
across the globe.

## Architecture Diagram
Here is a high-level diagram that illustrates the architecture of the StudyNotion ed-tech platform:

![ss](https://github.com/patelsa54/StudyNotion/assets/115445118/522a2b1c-5300-4ce4-a294-43900079ccbc)

## Front-end
To build the front end, we use frameworks and libraries such as ReactJS, which is a popular JavaScript library for building user interfaces. We also use CSS and Tailwind, which are styling frameworks that help make the user interface look good and responsive. Additionally, we use some npm packages to add extra functionality to the front end. To manage the state of the application, we use Redux, which is a popular state management library for React. Finally, we use a development environment called VSCode, which is a popular code editor, to develop the front end.

## Back-end
StudyNotion uses a monolithic architecture, with the backend built using Node.js and Express.js, and MongoDB as the primary database. Monolithic architecture refers to a
design approach where all the modules of the application are combined into a single large program, with a single codebase, to enable better control, security, and performance.
Node.js is a popular JavaScript runtime that allows us to run JavaScript code outside of the browser. Express.js is a web application framework that simplifies the process of building web applications in Node.js. MongoDB is a popular NoSQL database that allows for flexible data storage and retrieval, making it a suitable choice for complex applications like StudyNotion.

## Features and Functionalities of the Back-end
1. User authentication and authorization: Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
2. Course management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
3. Payment Integration: Students will purchase and enrol on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.
4. Cloud-based media management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.

## Frameworks, Libraries, and Tools used
1. Node.js: Node.js is used as the primary framework for the back end.
2. MongoDB: MongoDB is used as the primary database, providing a flexible and scalable data storage solution.
3. Express.js: Express.js is used as a web application framework, providing a range of features and tools for building web applications.
4. JWT: JWT (JSON Web Tokens) are used for authentication and authorization, providing a secure and reliable way to manage user credentials.
5. Bcrypt: Bcrypt is used for password hashing, adding an extra layer of security to user data.
6. Mongoose: Mongoose is used as an Object Data Modeling (ODM) library, providing a way to interact with MongoDB using JavaScript.

## API Design
The StudyNotion platform's API is designed following the REST architectural style. The API is implemented using Node.js and Express.js. It uses JSON for data exchange and
follows standard HTTP request methods such as GET, POST, PUT, and DELETE.

Sample list of API endpoints and their functionalities:
1. /api/auth/signup (POST) - Create a new user (student or instructor) account.
2. /api/auth/login (POST) – Log in using existing credentials and generate a JWT token.
3. /api/auth/verify-otp (POST) - Verify the OTP sent to the user's registered email.
4. /api/auth/forgot-password (POST) - Send an email with a password reset link to the registered email.
5. /api/courses (GET) - Get a list of all available courses.
6. /api/courses/:id (GET) - Get details of a specific course by ID.
7. /api/courses (POST) - Create a new course.
8. /api/courses/:id (PUT) - Update an existing course by ID.
9. /api/courses/:id (DELETE) - Delete a course by ID.
10. /api/courses/:id/rate (POST) - Add a rating (out of 5) to a course.

## Deployment
The deployment process for the StudyNotion ed-tech platform will involve hosting the application on various cloud-based services.
1) Front-end => Vercel [hosting service for static sites built with React]
2) Back-end  => Render [cloud-based hosting services for applications built with Node.js and MongoDB]
3) Media files => Cloudinary [cloud-based media management platform]
4) Database => MongoDB Atlas [fully managed cloud database service]

## Website Link



