# RecipeRadar


RecipeRadar leverages generative AI to curate a personalized cooking experience. Discover recipes aligned with your unique tastes and dietary preferences, all with the help of AI-powered recommendations.


# To visit the website [Click here]()

# Tech stacks used in this project are as follows:-

## Frontend

- HTML
  
- CSS

- JavaScript

- Vue.js

- Tailwind CSS

## Backend

- Python
  
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

