# Tailwind CSS Setup

A brief description of seting up project of tailwind css from scratch. 

### Create basic node project
Use command to create node project inside the folder.
 


## Installation

Install nodejs and create the ptoject with npm. 

```bash
  npm init 
```
After Installation use this script to intall tailwnd

```bash
npm install -D tailwindcss postcss autoprefixer vite
npx tailwindcss init -p
```

There will be two files named **'postcss.config.js'**  and **'tailwind.config.js'**. 
In the **'tailwind.config.js'** file just change **'content':['*']**. 
   
Now create **'input.css'** files. Add the following    
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```   
And link this **'input.css'** file in your **'index.html'**. 

Finally, in **'package.json'** just add scripts tag. 
```bash
scripts:{
    "start": "vite"
}
```
Now you can run local server with tailwind css with 
```bash
npm start
```

Visit your localhost. 