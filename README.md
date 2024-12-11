# README

## Overview
This project is a React Native application designed for a bike-themed platform. It includes functionality for user authentication (sign-in and sign-up) and navigation through various pages such as Home, About, and Contact.

## Key Features
- **Authentication Overlay**: Users can sign in or sign up using a dedicated overlay on the home screen.
- **Dynamic Pages**:
  - Home Page: Displays a welcome message and background image with dynamic content.
  - About Page: Provides information about bikes, including history and benefits.
  - Contact Page: A form for users to send inquiries.
- **Responsive Design**: Optimized for various screen sizes with adaptive styling.

## Process
1. **Home Page**:
   - Implemented a full-screen background image.
   - Added an overlay for authentication with email and password fields.
   - Configured Firebase Authentication for sign-in and sign-up functionality.
   - Used `onAuthStateChanged` to manage user sessions.

2. **About Page**:
   - Added detailed text sections about bicycles, their history, and benefits.
   - Included a relevant image with responsive styling.

3. **Contact Page**:
   - Created a form with inputs for name, email, and message.
   - Styled for clarity and ease of use.

4. **Styling**:
   - Applied professional and adaptive styling using `StyleSheet`.
   - Ensured images and elements resize properly on different devices.

## Tools and Libraries
- **React Native** for building the application.
- **Firebase** for user authentication.
- **Expo Router** for navigation.
- **React Native Paper** for UI components.

## How to Run
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Configure Firebase by adding your credentials to `firebaseConfig.js`.
4. Run the app using `expo start`.

## Notes
- Replace placeholder image URLs with actual image links.
- Ensure Firebase is set up properly with your project credentials.

Enjoy exploring the Bike World app!
