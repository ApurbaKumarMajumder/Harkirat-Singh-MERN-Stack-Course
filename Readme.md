## Why use Tailwind CSS

* No reinventing of class names required
* Your CSS doesn't grow with your html and designs.
* WWhen you make a change, no risk of breaking existing templates!
* If you try to build the site from the last video using Pure CSS, you will get answers to a lot of questions you have about tailwind.
* Will this make sites slow? Will it increase bundle size? -> No
* What about responsiveness?

## Setting up Tailind CSS

* To setup tailwind css, run these commands
    1. npm init -y // This initializes the directory as a NodeJs project
    2. npm install -D tailwindcss postcss autoprefixer vite // installs required packages
    3. npx tailwindcss init -p
    4. Create a css file "input.css", add it to your html and edit it with this content:
        @tailwind base;
        @tailwind components;
        @tailwind utitities;
    5. Inyour tailwind.config.js file replace content: [], with content: ["*"],
    6. Add "start": "vite" to your scripts in package.json
    7. Run npm run start command to start a dev server.