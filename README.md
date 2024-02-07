
# Rails Yelp MVP
This repository contains the code for a Rails app developed as part of a challenge to build a two-model Rails app with a restaurant and anonymous reviews.

## Setup
To get started with the Rails app, follow these steps:

- Clone this repository: git clone <repository_url>
- Navigate to the project directory: cd rails-yelp-mvp
- Install necessary gems: bundle install
- Setup the database: rails db:migrate
- Seed the database: rails db:seed

## External Specs
This project uses external specs written by the teachers for testing purposes. The specs can be found in the spec directory.

## Front-end Setup
Bootstrap stylesheets have been integrated into the application for styling. The Bootstrap CDN link is added to the application.html.erb layout.

## Testing
Run RSpec to test the code:

```
Copy code
rspec
```
If encountering issues with running RSpec, try bin/rspec.

## User Stories
The application follows the following user stories:

1. A visitor can see the list of all restaurants.
- Route: GET "restaurants"
- 
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
   
## Implementation
Each user story has been implemented separately. Start by writing the route, then code the corresponding controller action and view.

## Improvements
After the initial implementation, consider embedding the review form inside each restaurant's show view for improved user experience.

To run appropriate tests for this version, use the command rspec -t refactoring.

Feel free to reach out if you have any questions or need further assistance!
