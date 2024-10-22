# Fitness App

## Step 1: Installations, Packages and Configurations

1. Installations

```
npm create vite@latest
cd fitnessApp
npm install
npm i framer-motion react-anchor-link-smooth-scroll@1.0.12 @heroicons/react
npm i -D @types/react-anchor-link-smooth-scroll@1.0.2 @types/node

```

2. Modify src folder
3. Configure '@' in vite.config.ts and tsconfig.app.json

## Step 2: Tailwind Installation and Setup

1. Extensions

- Tailwind CSS IntelliSense
- Tailwind Documentations

2. Installing Tailwind, following the instruction here: https://tailwindcss.com/docs/installation

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

3. Add prettier to tailwind to save the class in a particular order

```
npm i -D prettier prettier-plugin-tailwindcss
```

4. Modify Tailwind Config
