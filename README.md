# Reactfolio 👩🏽‍🚀

Reactfolio is a modern and customizable personal portfolio web template built using the popular React library. It provides me to showcase my work, skills, and achievements in a professiona and visually appealing way with its responsive design and clean code.

<center>
<img src="https://github.com/0ujjwal0/my_portfolio/blob/main/public/screenshot.png" alt="Reactfolio" />
</center>

Live demo here: <a href="https://reactfolio-plum.vercel.app" target="_blank">ujjwal.portfolio</a>
<br/>


 📙 Features

-   📖 Multi-Page Layout
    -   Home
    -   About
    -   Projects
    -   Articles
    -   Contact
-   📱 Fully Responsive
-   🛠 Easy configurations

 📚 Getting started

Clone down this repository. You will need `NodeJS` and `git` installed globally on your machine.

 🛠 Setup Instructions

1. Installation: `npm install`

2. Run the project: `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.

 📁 Folder structure

-   `/public`: publicly accessible contents (ex: images, media).
-   `/src`: all the components used in this project.
    -   `/src/components/`: each reusable components of each pages.
    -   `/src/data`: configurations of the web app.
    -   `/src/pages`: pages that include in the web app.

 🚀 Building the React App

To build the React app, you can use the `npm run build` command. This will create a production-ready build of your app in the `build/` directory.

Here are the steps to follow:

1. Open a terminal window and navigate to the root directory of your React app.
2. Run the `npm run build` command to create a production build of your app. This will generate a static bundle of your app in the `build/` directory.
3. Copy the contents of the `build/` directory to your server's public directory. You can do this using an FTP client or by running a command like `scp` to transfer the files to your server. Make sure to replace `example.com` and `/var/www/html` with your server's domain name and public directory, respectively:

    ```bash
    scp -r build/* user@example.com:/var/www/html
    ```

4. My portfolio app should now be accessible from your server's domain name. You can verify this by opening a web browser and navigating to http://example.com (replace example.com with your server's domain name).

That's it! My React portfolio app should now be up and running on your server. 


 🌱 Contribution

If you have any suggestions on what to improve in Reactfolio and would like to share them, feel free to leave an issue or fork project to implement your own ideas
