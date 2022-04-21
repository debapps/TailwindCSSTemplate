# TailwindCSSTemplate

This is Tailwind CSS Template.

## The Template Creation Steps

- Run the following commands in sequential order.

`npm init -y`    

`npm install -D tailwindcss postcss autoprefixer vite`

`npx tailwindcss init -p`

- Change the **package.json** file to add the following statement in *sript* section:

`"scripts": { "start": "vite" }`

- Change the *content* section of **tailwind.config.js** as follows:

`content: ["*"]`

## To install node modules

`npm install`

## To create source CSS file, follow the steps follows:

- Create a **src** folder.
- Create *input.css* file inside the **src** folder.
- Copy the following code in input.css file.

`@tailwind base;`
`@tailwind components;`
`@tailwind utilities;`

The source CSS file is already created in this template.

## To start the Development Server

`npm run start` or `npm start`

## To build minify CSS run the following command.

`npx tailwindcss -o ./css/index.css --minify`    

- Minify the source CSS to production ready CSS file.

`npx tailwindcss -i ./src/input.css -o ./css/index.css --minify`