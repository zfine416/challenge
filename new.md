FoodRater

We are looking to create a new awesome Ruby on Rails app. Our app allows restaurant owners to login and add a list of items available at their restaurant. Then a user can login and rate food items at a given restaurant. Our product manager has given us some specifications for the the app below:

Part 1

Given that I am a logged-in “restaurant owner” I should be able to create a restaurant. By going to restaurants/new
The new restaurant form should allow our “restaurant owners” to add a name, location, cuisine and list of meals.
Given that I am a logged-in “restaurant owner” who has already created a restaurant, I should be able to edit my existing restaurant at restaurants/:id/edit
Given that I am ANY type of user (logged-in/logged-out) I should be able to view the restaurant show page at restaurants/:id
This page should show all the restaurants information and all of the meals should link to a new page meals/:id
On the meals/:id page we should be able to see a list of all the restaurants that serve that given meal
For example: If Meal.first = “Shrimp Tacos” then when we got to meals/1, I should see every restaurant that serves shrimp tacos

Part 2

A logged in user should be able to go to /restaurants which shows a list of all of the restaurants in our system
Each restaurant should link to its specific show page
On the restaurant show page, a user would be able to give a rating to a specific meal
