React project 4: Accordion. This project deploy here Review App: https://1hakann.github.io/04-accordion-app/

To clone the project git clone https://github.com/1hakann/04-accordion-app.git In the project directory, you can run: npm run start Node must be installed to run the project.

This app aims to show the user by pulling the values in our json object. For this, before and after buttons have been added. Also the surprise me button fetches random content.

This project aims to create an accordion using our data in our json object. For this, we added icons and used them as buttons.

Creating the application and css steps are similar to previous projects. Review component has been created. Here we used icons as a new feature. We have installed our package. And we imported the icons we want to use.

First, we structured our project. Then we imported our css, data object and component with react I useState. We created the app return simply. We pulled our data and transferred it to our variable. We split our object with map. and in the return inside, we returned our component, unlike the previous ones. We got our id by giving a key to our component and returned the rest of the array with ...{}.

Then we came to our component and imported our useState and icons. We created our return and called our objects in the relevant places. Then we added the button. We gave our button our icons with ternary instead of name.

We designed with CSS. We used grid and flex structures for this. Finally, we defined onclick in our button. We added a simple function inside. Ta Taa. Our app is ready to be used.

Deployment Now it's time to deploy.

For this, let's add a homepage to package.json. Let's add git remote set-url as origin. Then let's add the predeploy and deploy commands to the scripts. Now let's do npm install gh-pages --save-dev. Now let's perform the build and then deploy operations. That is all.

See you in the next app. Goodbye! Stay with the code...