# React-Project-Initializition
React Project Initialization

**Laravel Install**
1. composer create-project laravel/laravel example-app   

**React Create Project:**
1. npm create vite@latest
2. npm install && npm run dev
   
**Tailwind Css**
**step 1 :**
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
**Step 2**
**postcss.config.js**

module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  }
}
**step 3**

**tailwind.config.js**
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

****step 4** **
**main.css**
@tailwind base;
@tailwind components;
@tailwind utilities;



**For HeroIon Install**
npm install @heroicons/react

**uses**
import { BeakerIcon } from '@heroicons/react/24/solid'

function MyComponent() {
  return (
    <div>
      <BeakerIcon className="h-6 w-6 text-blue-500" />
      <p>...</p>
    </div>
  )
}
