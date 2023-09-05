# RecipeRadar


RecipeRadar leverages generative AI to curate a personalized cooking experience. Discover recipes aligned with your unique tastes and dietary preferences, all with the help of AI-powered recommendations.


# To visit the website [Click here]()

## Project Overview

## Introduction
RecipeRadar is a dynamic recipe recommendation platform designed to provide users with personalized cooking inspiration. Leveraging cutting-edge technologies, this full-stack web application makes cooking an enjoyable and hassle-free experience for users of all culinary levels.

## Key Features
1. **Recipe Suggestions:** RecipeRadar utilizes the OpenAI API to provide personalized recipe suggestions based on user-provided ingredients, ensuring users receive relevant recipe ideas tailored to their available ingredients.

2. **Recipe Management:** Users can create and manage their recipe collections within the platform, allowing easy access to their favourite dishes.

3. **Rating and Feedback:** Users have the ability to rate recipes and provide feedback, helping others make informed decisions about which recipes to try.

## Project Goals
The primary objective of RecipeRadar is to revolutionize cooking by offering users a hassle-free and enjoyable experience. Key goals include:
- **Personalization:** Providing users with recipes tailored to their unique tastes and dietary preferences.
- **Simplicity:** Making cooking accessible and enjoyable for individuals of all culinary skill levels.
- **Data-Driven Recommendations:** Utilizing OpenAI API to offer precise recipe suggestions based on user-provided ingredients.


RecipeRadar represents a fusion of technology and culinary artistry, aiming to make cooking not just a necessity but a delightful and communal experience.

## Tech stack

- **Recipe Suggestions:** RecipeRadar utilizes the OpenAI API to provide personalized recipe suggestions based on user-provided ingredients, ensuring users receive relevant recipe ideas tailored to their available ingredients.
  
## Frontend

- HTML
  
- CSS

- JavaScript

- Vue.js

- Tailwind CSS

## Backend

- Python
  
- OpenAI
  
- Django

- MySQL

- REST framework

## API Endpoints

### User Registration
- **Endpoint:** `/api/register/`
- **Description:** Register a new user.
- **Method:** POST

### User Login
- **Endpoint:** `/api/login/`
- **Description:** Log in as a registered user.
- **Method:** POST

### Get Recipe Suggestions
- **Endpoint:** `/api/get_recipe/`
- **Description:** Get personalized recipe suggestions based on user preferences.
- **Method:** GET

### Create Recipe
- **Endpoint:** `/api/create/`
- **Description:** Create a new recipe.
- **Method:** POST

### Get All Recipes
- **Endpoint:** `/api/all_recipes/`
- **Description:** Get a list of all available recipes.
- **Method:** GET

### Update Recipe
- **Endpoint:** `/api/update_recipe/<int:pk>/`
- **Description:** Update an existing recipe by its ID.
- **Method:** PUT

### Delete Recipe
- **Endpoint:** `/api/delete_recipe/<int:pk>/`
- **Description:** Delete a recipe by its ID.
- **Method:** DELETE

### Get Recipe by ID
- **Endpoint:** `/api/recipe/<int:recipe_id>/`
- **Description:** Get a specific recipe by its ID.
- **Method:** GET

### Create Review
- **Endpoint:** `/api/recipe/reviews/<int:recipe_id>/`
- **Description:** Create a review for a specific recipe.
- **Method:** POST

### Get Reviews
- **Endpoint:** `/api/recipe/get/reviews/<int:recipe_id>/`
- **Description:** Get reviews for a specific recipe.
- **Method:** GET

### Create Rating
- **Endpoint:** `/api/recipe/rate/<int:recipe_id>/`
- **Description:** Create a rating for a specific recipe.
- **Method:** POST

### Get Ratings
- **Endpoint:** `/api/recipe/get/ratings/<int:recipe_id>/`
- **Description:** Get ratings for a specific recipe.
- **Method:** GET

