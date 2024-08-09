# JATE - Just Another Text Editor

## Description

JATE (Just Another Text Editor) is a progressive web application (PWA) that allows users to create, edit, and save notes or code snippets directly in their browser. This application is designed to work both online and offline, ensuring that your work is always saved and accessible, even without an internet connection.

The application leverages IndexedDB for data persistence and uses service workers to cache assets for offline functionality. It also includes a simple yet effective installation process, allowing users to install the application on their desktop or mobile device.

## Table of Contents

- Installation
- Usage
- Features
- Technologies Used
- Deployment
- License
- Contributing
- Questions

## Installation

### Local Installation

1. **Clone the Repository:**

   Clone the repository from GitHub and navigate into the project directory.

2. **Install Dependencies:**

   Run the command `npm install` to install all necessary dependencies.

3. **Build the Application:**

   Use `npm run build` to bundle the application with Webpack.

4. **Start the Application:**

   Run `npm run start:dev` to start the application in development mode.

5. **Open the Application:**

   Open your browser and navigate to `http://localhost:3000` to use the application.

### Installation as a PWA

1. **Open the Application:**

   Visit the deployed application in your browser.

2. **Install the PWA:**

   Click the "Install" button that appears in the browser or find the install option in your browser's menu.

3. **Launch the PWA:**

   After installation, launch the app directly from your desktop or home screen.

## Usage

- **Creating Notes:** Start typing in the editor. The content is automatically saved to IndexedDB when you move away from the editor.
- **Offline Access:** The application works offline, so you can continue editing and saving notes even without an internet connection.
- **PWA Installation:** You can install the application on your device for easy access.

## Features

- **Offline Functionality:** Works without an internet connection.
- **Data Persistence:** Saves content using IndexedDB, ensuring your data is never lost.
- **PWA:** Can be installed as a Progressive Web Application, providing a native app-like experience.

## Technologies Used

- **JavaScript**
- **Webpack**
- **IndexedDB**
- **Service Workers (Workbox)**
- **HTML/CSS**
- **Express.js**

## Deployment

The application is deployed on Render. You can access the live application [here](#).

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Questions

If you have any questions or issues, please contact me via GitHub: [Tristn Rohr](https://github.com/TristinRohr).

---

This README provides a clear and concise overview of your project, including instructions for installation, usage, and more. You can customize it further as needed!