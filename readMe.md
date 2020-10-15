# RecipeMe

Live application: [RecipeMe]

## Summary

RecipeMe is the app that will help you turn fridge fossils into dinner GOLD. Just select the ingredients you have on hand and Fridge2Table will dazzle you with all the recipes you never would have thought of on your own.

## Target Audience

RecipeMe is perfect for harried millennials, ultra-marathoning baby-boomers or agoraphobic gen-xers. Anyone whose fridge has a jar of pickles, week-old block of parmesan and 4 eggs from your neighbor’s chickens.

We chose to develop Fridge2Table for people who want to:
-Cook but have no idea what to do with the odds and ends that populate their fridge
-Tap into the eat-at-home movement
-Get ahead of the Fridge2Instapot stampede after Black Friday’s record pressure cooker sales.

## Technologies Used

The application was developed using client-side and server-side tools and technologies:

- HTML
- CSS
- Javascript
- jQuery
- Unirest node module
- APIs – Spoontacular, Twilio
- Sequelize
- Heroku
- JawsDB

## API, Library, and Database

### API

The primary API used in this project is Spoontacular, a RESTful API that leverages recipe, food, and nutrition API documentation. The Spoontacular Nutrition, Recipe, and Food API allows you to access over 365,000 recipes, 86,000 food, and

### Database

The MySQL database was set up using two primary tables and a join table to connect recipes and ingredients in a many-to-many relationship. This is the database structure:
