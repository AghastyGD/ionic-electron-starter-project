# Ionic-Electron starter app project

## Pre-requisites:
Ensure you have Node JS 20x installed in your machine

## Quick Start

1. Clone this repository:
```bash
git clone https://github.com/AghastyGD/ionic-electron-starter-project.git
```

2. Change to the new directory and install required components:
```sh
cd ionic-electron-starter-project
npm install
```

3. Run the development server
```bash
npm run dev # this will open a vite dev serving ionic web app at: http://localhost:5173/
```

4. Now if everything is working correctly, lets start the steps to build our electron app, first go to electron folder and check if exists a node_modules folder, if not, run the following command in project root:
```bash
cd electron
npm install
```

5. Then you can build our ionic app to electron, follow the bellow commands
```bash
ionic build
ionic cap open electron # this will open the eletron app with our ionic base template sidemenu
```

**Note:** If you receive command not found errors when running `ionic`, then you only have this installed locally within the project. You may need to install globally, to get it, run the following command:
```bash
npm install -g @ionic/cli
```
After that, go back to step 5 and happy coding!

If you face any issue, please contact-me






