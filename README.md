# 🌍 WanderLust: Your Ultimate Travel Companion

![WanderLust Logo](https://img.shields.io/badge/WanderLust-MERN%20Stack-blue)

Welcome to the **WanderLust** repository! This project is a fully functional MERN stack clone of Airbnb, designed to help users find and book accommodations effortlessly. With a focus on user experience, security, and scalability, WanderLust brings together essential features for both hosts and travelers.

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Authentication](#authentication)
6. [Image Uploads](#image-uploads)
7. [Map Integration](#map-integration)
8. [Deployment](#deployment)
9. [Contributing](#contributing)
10. [License](#license)
11. [Releases](#releases)

## Features

- **User Authentication**: Secure sign-up and login process.
- **Authorization**: Role-based access control for hosts and guests.
- **MVC Architecture**: Clean separation of concerns for better maintainability.
- **Image Uploads**: Seamless integration with Cloudinary for image storage.
- **Map APIs**: Interactive maps to display property locations.
- **Responsive Design**: Works on both desktop and mobile devices.

## Technologies Used

- **MERN Stack**: MongoDB, Express.js, React, Node.js
- **Cloudinary**: For image uploads
- **Map APIs**: For displaying listings on maps
- **JWT**: For secure user authentication

## Installation

To get started with WanderLust, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/firman-store/WanderLust.git
   ```

2. Navigate to the project directory:

   ```bash
   cd WanderLust
   ```

3. Install dependencies for both the client and server:

   ```bash
   npm install
   cd client
   npm install
   ```

4. Create a `.env` file in the root directory and add your environment variables. You can find a sample in `.env.example`.

5. Start the server:

   ```bash
   npm run dev
   ```

6. Open your browser and go to `http://localhost:3000`.

## Usage

Once the application is running, you can create an account or log in. Explore various listings, view property details, and even make bookings. As a host, you can add your own listings, manage bookings, and respond to inquiries.

## Authentication

WanderLust uses JWT for user authentication. When a user logs in, a token is generated and stored in local storage. This token is then used for subsequent requests to protected routes.

## Image Uploads

For image uploads, we use Cloudinary. Users can upload images of their properties, which are then stored securely in the cloud. This ensures fast loading times and efficient storage management.

## Map Integration

WanderLust integrates with popular map APIs to display property locations. Users can easily visualize where listings are situated, making it easier to find accommodations that fit their travel plans.

## Deployment

WanderLust is hosted on Render, allowing for live access to the application. You can view the deployed version and explore its features without setting up the project locally.

## Contributing

We welcome contributions! If you would like to help improve WanderLust, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest updates and releases, visit our [Releases](https://github.com/firman-store/WanderLust/releases) section. Here, you can download the latest version of WanderLust and execute it locally.

## Conclusion

WanderLust aims to simplify the process of finding and booking accommodations. With its user-friendly interface and robust backend, it serves as a reliable platform for both travelers and hosts. Explore the code, contribute, and help us make WanderLust even better!

![Explore the World](https://source.unsplash.com/1600x900/?travel)

Thank you for checking out WanderLust!