# Steps

## Frontend
### Checkpoint 1
* Open a `powershell terminal` in `vscode`.
*     npm create vite@latest
* `Project Name` >   `React` > `Javascript`
*     cd frontend
*     npm i
*     cls
---------------------------------------------------------------------------
### Checkpoint 3
* `tailwindcss.com` > `Framework Guides` > `Vite` > `Install Tailwind CSS` > `Configure your template paths` > `Add the Tailwind directives to your CSS`
*     npm install -D tailwindcss postcss autoprefixer
*     npx tailwindcss init -p
* Open `tailwind.config.js` and replace the code available from the website as `tailwind.config.js`
*     /** @type {import('tailwindcss').Config} */
      export default {
        content: [
          "./index.html",
          "./src/**/*.{js,ts,jsx,tsx}",
        ],
        theme: {
          extend: {},
        },
        plugins: [],
      }
* Open `index.css` in the `frontend` folder and replace the code with the following
*     @tailwind base;
      @tailwind components;
      @tailwind utilities;
*     cls
*     npm run dev
-----------------------------------------------------------------------------
### Checkpoint 5
* Open `App.jsx` in the  `frontend` folder and write code
* Open another `powershell terminal`
*     cd frontend
*     npm i react-router-dom

<br>

## Backend
### Checkpoint 2
* Open another `powershell terminal` parallelly
*     npm i express-generator
*     npm install -g express-generator
*     express --version
*     express backend --view=ejs
*     cd backend
*     npm i
*     cls
* ----------------------------------------------------------------------------
* ### Checkpoint 4
*     npx nodemon


