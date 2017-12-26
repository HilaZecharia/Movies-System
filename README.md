# Movies-System
This project is a client server project over TCP/IP ot UDP connecton .
The server is a movie system which containce movies and allow the client to ordered and know the details  about the movies.
the system works as follows:
Each film contains the following information: code, name, length (in minutes), year of exit, rating, genres can belong to some, summary, professionals.
The professionals are present: directors, actors, screenwriters and producers.

 They have ID. Name, job description, age, gender. Every professional presents himself differently. That is - when a professional is sent to print - each prints differently. The director and producer record their name, the actor registers his name and then his age, the screenwriter writes his name
Then his specific job description.

A film can print its professionals in one of three categories:

1. Default - by ID. From the small number grow.

2. By age from adult to young 3. According to the number of films that the professional is in, the most likely to be a little bit
You can create a new movie by connecting movies together.Connecting movies takes the information of the longer film, except the information about genres and people
Profession: Unites the genres of films and makes a union of professionals.
 
The system allows the following actions:
1. Absorbing a new movie (all the parameters of the movie are transmitted through the input, except for genres and professionals)
2. Absorption of a professional (all parameters of the professional are transferred through the input, including the type of professional)
3. Adding a professional to the film (receiving a movie code and the professional's ID).
4. Adding the relevance of a film to the genre (the absorption of film and genre code).
5. Definition of the classification of professionals into a particular film (the absorption of a movie code and the type of classification)
6. Printing tape professionals (receiving movie code)
7. Recording a movie (receiving a movie code) Profession 
8. Connecting movies (movie code reception - can be more than 2) 
9. Print all movies a professional has attached
10. Deleting a movie (receiving a movie code) 11. Deleting a professional (receiving a professional ID)
12. Deleting a professional from a film (receiving a movie code and identifying a professional)
13. Printing the list of all movies.
14. Print the list of all professionals.

The client side is writing in java using JavaFX
the client show GUI menu to enter new movie,show details,rating movie and more.
