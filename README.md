# CINEPHILE
#### Video Demo: <https://youtu.be/FVnPspVhYgQ>
#### General Description:
This is a game called cinephile. I made this game for the ones who are fond of movies and the ones who want to test their knowledge in the world of cinema.
###### What Languages and Tools Are Used?
This game is built using Python and one of its coolest libraries, IMDbPy. This library provides us everything about a movie, from the plot to the list of cast and crew.
Writing this program's codes happened to be quite challenging for me since I had to start learning more and more Python syntaxes and algorithms in order to advance in my work. In addition, I've gone through the documents of IMDbPy library to get to know how it is used. Using this library, I tried to create a list of all the movies I want to be in the game. I chose Top 250 Movies of All Time. After Having a list of these movies' names, I created a dictionary that the key is the name of the movie and the value is its ID in IMDb. This algorithm and the Random library helped me choose a movie randomly from this list in each round of the game. This, alone, makes the game more fun and exciting.
###### What It Is and How It Works:
In Cinephile game, you have to guess the name of a movie based on its plot, actors, and director. In brief, this is how it works. It is consisted of three rounds. Each round has three different parts. At the start of each round and in their part one, the system prints the plot of a movie in a couple of sentences. The user must guess the name of the movie. If they can guess the name of movie in the first part, they get 20 points, else if they don't guess the correct name of the movie, they will be given 2 more chances in part one. If they don't tell the name of the movie in part one, they lose 10 points and they go into the part two. In part two, they have 2 chances to guess. In this part, they are given the list of the most famous actors/actresses of the movie. If they answer, they get 10 points in this part, else they lose another 5 points and they head to the final part of the round which is part three. In part three, they only have one chance to guess. They either answer correctly and get 5 points or cannot tell the name of the movie and get no point in the round.
After part three, the round is over and they go to next round with the information of a new movie. The cycle repeates for three times in three rounds and when all the rounds are completed, the game is over and a dragon shows up and tell the total point of the user. Now the game is over.
###### Possible Future:
I might have some plans for this game. One feature that can be added in the future, is a graphical user interface for the game because the game currently has no graphical user interface and it can be fancier and more user friendly to rhink about a user interface for it rather than playing it in the terminal.
Another thing I'm thinking of is using a database to keep the name and the total score of each player. I can make it a tournament of so many players who want to test their cinematic knowledge.