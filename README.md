# dev-test

## Description
The application is a catalog of favourite TV Shows and Movies of an user pulled from a Netflix API. The user will be able to search shows/movies based on the title (full title only) and save them as favourites in a database.

## API
The API you will be using it's a public API that pulls movies/shows from Netflix based on the title.

http://netflixroulette.net/api/

## Backend
The backend will be used to store the favorite movies from the user. You can assume there will be only one user so authentication and user models are not needed to be implemented. This means, only the shows/movies the user selects as favourites need to be stored in the database. This way, when the user enters in the site again, they will see their selection.

Feel free to use any backend that you feel comfortable with, but always using the technologies we use: WordPress, PHP, NodeJS (any framework) if possible.

## Frontend
We provide full design for both Mobile and Desktop versions of the application. Normally we use Zeplin (http://zeplin.io) to provide the design and assets, but you can request Sketch files as well if you prefer (ask the person in contact for them). 

To see the zeplin project follow this link: https://zpl.io/Z2mVQUm And request access with your account (create one if you don't have one already). Some notes were added to the design for more clarification, be sure you read them!

For the frontend, you can use any JS framework or library. Preferred are React or Angular, but you can use vanillaJS or jQuery if you feel more comfortable with those, as well as any front-end framework (ui-kit, bootstrap, foundation). Anything that helps you to build faster is completely fine.

Check this Google Drive folder for all the assets you should need (e.g. fonts): https://drive.google.com/drive/u/3/folders/0B7mwU1XUucqxcUZKSWNONGdDdjg

We only ask you to build the Grid of favorites (Named 'Favorites' and 'My Favorites - Mobile' in Zeplin). Do not implement the **detail** pages ('Opened Item layouts')

## User stories
At Nolte, we work Agile! That means, normally developers receive the specifications based on user stories. The following user stories will help you to understand the requirements of the application.

- As a user I want to be able to look for new movies/shows based on titles.
  - Show the movie/show in a dropdown below the input
  - Look for the movie once the user hits enter or click on the search icon
  - Show a "not found" message if the response is empty

- As a user I want to be able to save my favourite movies/shows and see them every time I load the app.
  - Store the favourite movie in the database via Http request.
  - Show basic information in the grid (poster, title, category, duration, show/movie and rating)
  - Grid items will be ordered depending on the type (Movie or TV Shows)
  
## Some examples
The API might show different movies based on time and/or location, so we provide you enough shows to test.
* Attack on Titan
* El Dorado
* Grease
* Pulp Fiction
* Reservoir Dogs
* Terminator 2: Judgment Day

## What will we evaluate
These are the main points we will be looking into it to make our final decision. Although we expect all the work to be finished, don't panic, if you can't finish the whole assingment just send what you can.

* Pixel perfection based on the design
* Code quality
* Code efficiency
* Technologies/tools used
* Overall approach of the solution

## Extra points
These are some nice to have

* Add some animations.
* Travis integration for code lint.
* Production ready code.
* Add some tests.

## Project Delivery
Please provide a copy of your code and a url to a working example.

* Link to the repository (github or bitbucket).
* URL of a working demo of your app (heroku or any other hosting).
* Optionally, any comments you want to share with us.

Feel free to ask any question or clarification and, happy coding!
