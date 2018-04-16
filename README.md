## Project Name:  Seminole Movie Connection Application using TMDB API

### Course Title:
LIS 2360:  Web Application Development

### Assignment Date:  
April 14, 2018

### Student Name:  
Cole Sheridan

### Project Description:
In this assignment, students used Ajax to obtain infromation from an API and display it to their page.  The API used in this project was TheMovieDB (TMDB) and the Seminole Movie Connection page was created to send an API request to this third party database whenever the user searched for a movie title.  The page is set up to display the movie's title, plot, rating, original language, release date, and poster.

### View Project:
(Replace this statement with your Github Page URL that was created when you 
 published the project.)

### Lessons Learned in the Assignment:
1. Ajax, or Asynchronous Javascript XML allows for developer to connect their page in a way that allows it to request data from an external site or server and display it to the page without having to reload the page in its entirety.  Using AJAX, the client (your page and the person viewing it) sends a request for information to a server, which responds with the information in order to provide the requested informatin (which is dependant on the scope of the website and the input of the user).   An example of this is when Google attempts to autocomplete a search.  An Ajax protocol is used to read the user input for each character entered in the search bar and update the search engine's drop down menu with popular relevant searches based on the current input.
2. There are two methods in which a server may respond to a client request.  This is in XML or JSON.  XML, or Extensible Markup Language, is a metalanguage used to have no inherant semeantics so that both a human and a computer could undersrand the data that is transported.  However, this means that XML is only cappable of seperating markup language from data, thus making it unable to read responses not designed in the XML format.  JSON, or Javascript Object Notation is a markup language that preforms the same function as XML, with the exception the JSON uses a parser, which allows it to understand what JSON documents mean.  JSON tends to be the more popular of the two methods of data transport as parsing for JSON documents take less time, and their tendancy to have a smaller size in comparison to XML documents makes it quicker for data to be transported between the client and server.   
3. An API or application programming interface, is a set of subroutine definitions and protocols that are used to design applications so that they may connect with a server.  In our assignment, we used an API to connect with The Movie Database (TMDB) in order to send a request for data about a certain movie (the movie is dependant on what the user inputs in the "Movie Name" field). When the user searched for the movie, the API sent a request to the server (TMDB, who's website provided the directions for the input required to send a request to the server, and the link that our application would use to contact the server) and recieved all of the database's information on that movie.  We had to use Javascript to parse the data in order to obtain the information that we wished to display to the page.   
