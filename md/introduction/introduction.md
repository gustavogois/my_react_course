## Introduction

### Create a React App

1. Create a React App using [Facebook Tool](https://github.com/facebook/create-react-app)
    - See the instructions
    - You'll need NodeJS installed
2. Go to the App's directory and execute ```npm start```
3. Most important application files\directories created:
    - ```package.json``` - you can see the dependencies.
    - ```\node_modules``` - where all the dependencies are stored. Typically, you don't need to put anything manually in this directory, because it´s all automatically installed. 
        - This content is not stored on the repository. So, when you pull for the first time an app, you have to execute the command ```npm install```.
    - ```public\index.html``` - the only html file\page.
    - ```src\index.js``` - get the *root element* and render our application, using the App component.
    - ```src\App.js``` - our only component.
4. Delete all the content inside div tags, and insert some text that you want. See the results.
5. At the ```src\App.css``` file, remove everything except ```.App```.
6. Analyse App component.
    - You always have to return some HTML by the *render* method, to be rendered on the DOM.
    - Due to the ```export default App```, if you import this class\component, you only have to import ```App```.
        - Note: you can use any name to reference the component imported, but, by convention, you maintain the component name.
    - The language inside the divs tags looks be html, but only looks: it´s JSX, a language used by React similar html, but with some little differences.

[Go back](../../My_Course.md) || 