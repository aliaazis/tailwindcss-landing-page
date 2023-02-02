# tailwindcss-landing-page
Manage landing page using Tailwind CSS, HTML and JavaSCript

# Manage Landing Page

This is the repositories for Manage Landing Page using Tailwind CSS, HTML and JavaScript.



## Acknowledgements

 - [Traversy Media Youtube](https://www.youtube.com/watch?v=dFgzHOX84xQ)
 - [Frontend Mentor Manage Landing Page Challenge](https://www.frontendmentor.io/challenges/manage-landing-page-SLXqC6P5)


## Installation

Install Tailwind CLI with npm to create tailwind.config.js file

```bash
  npm install -D tailwindcss
  npx tailwindcss init
```

Add path to tailwind.config.js file
```bash
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```  

Add Tailwind directives to main CSS file
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Add CLI to package.json script or run npx in terminal
```bash
"build": tailwindcss -i ./src/input.css -o ./dist/output.css
"watch": tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```
## Tech Stack

**Client:** TailwindCSS, JavaScript, HTML

**Server:** Node, Git, GitHub


## License

[MIT](https://choosealicense.com/licenses/mit/)

