# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

inititialize vite app
npm create vite@latest -- --template react client
## Dependences explore

npm install three @react-three/fiber @react-three/drei three maath valtio react-color framer-motion

- threejs library
- react-three/fiber to render the threejs library
- react-thee/drei for usefull items for react from fiber
- maath math helper

- valtio allows to menage react states
  import useSnapshot
  the file store/index.js all can be used on the entire app
  import {proxy} from 'valtio';
  const state = proxy({

            });
        export default state

- react-color color picker
- framer-motion for animations
  import motion for animation, Animatepresence to enables the animation of components removed from the three
  The import for file config/motion and the relative classes animation
  npm install -D tailwindcss postcss autoprefixer
  npx tailwindcss init -p

- vite with tailwind for faster classes styles

To create the server in the server folder run npm init -y
add in to the file   "type": "module", and edit script start 
  "scripts": {
    "script": "nodemon index"
  },
npm install cloudinary cors dotenv express mongoose nodemon openai

- cloudinary use for save images
- cors allow for request
- dotenv to store envoirement
- express
- mongoose
- nodemon
- openai for the api openai

** WARNING **

API KEY OPENAI

1. The openaiAPI' credit is expired, to use the openAiPicker
   create a new account they will give you $5.
   For each interaction with the API they charge you about 2 cents

2 . Decomment the tab from ./config/costants
3 . run npm start on the terminal in flder ./server to active the server Node Express

** WARNING **
