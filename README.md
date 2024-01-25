# Ionic Electron starter app project

## Prerequisites
Ensure you have Node.js 20 installed on your machine.

## Quick start
1. **Clone this repository and install dependencies:**
   ```bash
   git clone https://github.com/AghastyGD/ionic-electron-starter-project.git
   cd ionic-electron-starter-project
   npm install
   ```

2. **Run the vite dev server for the Ionic web app:**
   ```bash
   npm run dev # opens the vite dev server for the Ionic web app at http://localhost:5173/
   ```

3. **Navigate to the electron folder:**
   - Check for the `node_modules` folder.
   - If it doesn't exist, run:
     ```bash
     cd electron
     npm install
     ```

4. **Build the ionic app for electron:**
   ```bash
   ionic build
   ionic cap open electron # opens the electron app with the ionic base template sidemenu
   ```

   *Note: If you encounter "command not found" errors for Ionic, install it globally using:*
   ```bash
   npm install -g @ionic/cli
   ```

## Contact information
For any issues or questions, please feel free to contact me.