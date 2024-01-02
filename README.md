# Movie Application

Command to Run json-server:
* `npm run db`

## Required Features

### When the page loads

* Display a "loading..." message
* Make an AJAX request to get a listing of all the movies
* When the initial AJAX request comes back, remove the "loading..." message and replace it with HTML generated from the JSON response your code receives

### Add a movie
* Create a form for adding a new movie that has fields for the movie's title and rating
* When the form is submitted, the page should not reload/refresh, instead, your javascript should make a POST request to /movies with the information the user put into the form

### Edit a movie
* Give users the option to edit an existing movie
* The form in which the movie will be edited should pre-populate with the selected movie's information
* Like creating a movie, this should not involve any page reloads, instead, your javascript code should make a fetch request when the form is submitted.

### Delete movies
* Each movie should have a "delete" button
* When this button is clicked, your javascript should send a DELETE request

## Bonus Features
* Add a disabled attribute to buttons while their corresponding ajax request is still pending.
* Show a loading animation instead of just text that says "loading...".
* Use modals for creating and editing movie forms.
* Add a genre property to every movie.
* Allow users to sort the movies by rating, title, or genre (if you have it).
* Allow users to search through the movies by rating, title, or genre (if you have it).
* Use a free movie API like OMDB to include extra info or render movie posters.