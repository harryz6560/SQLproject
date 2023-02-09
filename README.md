# Movie Database Management System

The SQL project allows the user to manage and organize a movie database. It provides features for searching, entering, and saving information about movies and their crew members. The user can categorize the movies into different genres and store relevant details such as title, release date, and cast. The project also enables the user to add and save the names and roles of the crew members associated with each movie as well as search users. The project is implemented using the Python programming language and makes use of SQL to store and retrieve data from the database.

#General overview:
On the main screen the user has an option to choose between 5 different options:

“1” – search for a movie. We enter a few keywords, and the user sees all titles that match all those keywords. The user is also able to select a movie from the list, and the number of votes, the names of cast/crew members and their characters are displayed for this particular movie.

“2” – search for a genre. The user provides a genre and a minimum vote count and sees all titles under the provided genre (again case-insensitive match) that have the given number of votes or more. The result is sorted based on the average rating with the highest rating on top.

“3” – search for cast/crew members. The user provides a cast/crew member name and sees all professions of the member and for each title the member had a job, the primary title, the job and character (if any).

“4” – add a movie. The user adds a row to title_basics by providing a unique id, a title, a start year, a running time and a list of genres. 

"5" - Add a cast/crew member. The user provides a cast/crew member id, a title id, and a category.

“q” – exits from the system
