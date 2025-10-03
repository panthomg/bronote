# BroNote: Engine Edition

![Project Status](https://img.shields.io/badge/status-live-brightgreen)
![Version](https://img.shields.io/badge/version-2.4.0-blue)
![License](https://img.shields.io/badge/license-MIT-yellow)

A no-nonsense, neo-brutalist thought processor. Your thoughts, processed.

---

### **[View the Landing Page](https://tintool.netlify.app/bronote) &nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp; [Launch the App](https://tintool.netlify.app/creative/)**

---


*(Please replace this placeholder with an actual screenshot of your app)*

## About The Project

**BroNote: Engine Edition** is a fast, functional, and focused note-taking application designed for clarity and efficiency. It rejects the bloat of modern software and embraces a neo-brutalist aesthetic, prioritizing raw functionality over ornamentation.

Built with vanilla JavaScript and powered by Firebase, it provides a seamless experience with real-time cloud synchronization. Organize your ideas in nested folders, track your productivity with detailed stats in the "Engine Bay," and maintain full control over your data with easy backup and restore options.

This is your digital workspace, stripped down to the essentials. No distractions, just processing.

## Core Features

*   ☁️ **Cloud Sync with Firebase:** Log in with your Google account to securely save and sync your notes, folders, and tags across devices in real-time.
*   🗂️ **Nested Folder System:** Organize your chaos with an intuitive folder hierarchy. Create projects, subjects, or areas of life and navigate them easily with breadcrumbs.
*   ⚙️ **The Engine Bay:** Go under the hood and analyze your output. Get statistics on total items, word counts, unique tags, and even run a word frequency analysis.
*   💾 **Data Sovereignty:** Your data is yours. Download a complete JSON backup of all your notes and folders at any time, or restore your workspace from a previously saved file.
*   🎨 **Neo-Brutalist UI:** A sharp, high-contrast interface that is unapologetically digital. Clear, legible, and built for focus.
*   📱 **Responsive Design:** Fully functional on both desktop and mobile, with a dedicated mobile action bar for quick access to core functions.

## Tech Stack

*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES Modules)
*   **Backend Service:** Firebase
    *   **Authentication:** For secure Google Account sign-in.
    *   **Firestore:** As the real-time NoSQL database for storing and syncing user data.

## Getting Started (For Developers)

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need a modern web browser and a code editor (like VS Code with the Live Server extension).

### Installation & Setup

1.  **Clone the repo:**
    ```sh
    git clone https://github.com/panthomg/your-repo-name.git
    ```
    *(Replace `your-repo-name` with the actual name of your repository)*

2.  **Set up Firebase:**
    *   Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
    *   In your project, go to **Project Settings** > **General**.
    *   Under "Your apps", click the web icon (`</>`) to add a new web app.
    *   Give it a nickname and register the app.
    *   Firebase will provide you with a `firebaseConfig` object. **Copy this object.**
    *   In the project directory, open the `firebase-config.js` file.
    *   **Replace the existing `firebaseConfig` object with the one you copied from your Firebase project.**
    *   Go to the **Authentication** section in the Firebase console. Click "Get started" and enable **Google** as a sign-in provider.
    *   Go to the **Firestore Database** section. Click "Create database", start in **test mode** (for easy setup), and choose a location.

3.  **Run the application:**
    *   The easiest way is to use a live server. If you are using VS Code, install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
    *   Right-click the `index.html` file and choose "Open with Live Server".

## Credits

*   **Developed by:** [itzpanth](https://github.com/panthomg)
*   **A project by:** [TinTools Solutions](https://tintool.netlify.app/bronote)

## License

Distributed under the MIT License. See `LICENSE` file for more information.
