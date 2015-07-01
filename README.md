##BREAKING DOWN AN APP 

###Objective SWBAT:
* As a group, write the bulk of the design doc for a previous CSSI App

###Motivation / Why Should You Care?
* Essentially you already know how to build each component of any webapp
* When each piece comes together they become amazingly powerful
* By the end of today, you will have submitted your design doc for your group. This is a great tool to help you plan your project and the components that will make it up. You have all the skills to make an amazing web app, and today is the first step to getting it done.


###What makes Movie Spotter Work?

 [Movie Spotter](https://movie-spotter.appspot.com/home) is an app from CSSI - Cambridgelast year.

Let's think through what the heart of their [Design Doc](https://docs.google.com/document/d/1bYyLZscWxT5jP8cB9Wu0n3mmgksxmMlka3TJKzVWYyw) might have looked like last year - Questions 5,6 and 7

####5. What technology are you going to need?
* HTML/CSS- for the views, to show and style each page
* Python- to provide the logic, used to show the parameters that are passed from the search to the API back to the results page
* AppEngine - used to gather input from the user and access the IMDB API
* IMDB API - used to access a list of all the movies!


####6. What is the flow of data within your MVC? Draw a flowchart and describe each step
![a moviespotterflowchart](http://www.gliffy.com/go/publish/image/8381929/L.png)


####7. How are you going to build this? List specific steps you will take. 
* Day 1 - Build the basic search.html view. Need a <form> tag, <input name=”search_movie”> and logging in the console so we know that the parameter is stored. 
* Day 2 - determine logic to process the “search_movie” parameter and output the matching information on the results page. If there are no matches, build a condition for that. In this case, just match it against a pre-built dictionary of movies and worry about API intergration later. award_winning_movies = {Forrest Gump {year : “1994”, link=”www.forrestgump.com”}, Lion King {year : “1992”, link : “www.thereallionking.com”}
* Day 3 - Make API Integration. Figure out how to get the dictionary from IMDB as the comparision dictionary
* Day 4 - Style up the views and make it pretty! 

Since this is a mock-up, we can be happy understanding a) what each component will look like and b) what logic we will need to implement.

### Conclusion
Notice we don’t need to fully understand HOW to implement our logic, but rather we should have a general understanding of what technology we can use. 

