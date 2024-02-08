
# Rails Yelp MVP
This repository contains the code for a Rails app developed as part of a challenge to build a two-model Rails app with a restaurant and anonymous reviews.

## User Stories
The application follows the following user stories:

1. A visitor can see the list of all restaurants.
- Route: GET "restaurants"

2. A visitor can add a new restaurant and be redirected to the show view of that new restaurant.
- Routes:
  - GET "restaurants/new"
  - POST "restaurants"
    
3. A visitor can see the details of a restaurant, including all reviews related to the restaurant.
- Route: GET "restaurants/:id"

4. A visitor can add a new review to a restaurant.
- Routes:
  - GET "restaurants/:id/reviews/new"
  - POST "restaurants/:id/reviews"
   
