# React Budget App

To run:

```
npm install 
npm start 
```

How to Setup a React Project
The first thing we need to do is setup a React project. For this we'll use create-react-app.

Fire up a terminal and type:

npx create-react-app budget-tracker

When that's finished doing its thing we're going to install Bootstrap. This will give us ready-made styles we can use instead of having to create our own in CSS.

In the same terminal, change to your working directory, and install Bootstrap:

cd budget-tracker
npm i bootstrap			
Next we're going to install a package that allows us to generate IDs. We'll be using IDs to identify each expense in the list, so this is important.

Run the following command in your project directory:

npm i uuid
The last package we need to install gives us some icons to use, which saves us from having to create them ourselves.

Run the following command in your project directory:

npm i react-icons			
Now open up the project in VS Code (or whatever IDE you use). You should see some stuff appear in the project tree (this is our empty React project).