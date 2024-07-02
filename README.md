# Movie recommendation project


### Objective
Using fundamental data structures and algorithms to solve real-world problems with trees.


### Problem    
Ahmed is sitting in the living room in front of the TV, and can't decide which movie to watch. Build a movie recommendation system to help Ahmed **decide** which movie to watch.

- You will be given a list of movies stored in an array.    
- A movie will have the following properties:   
`Id`, `name`, `type`, `rate`, `year`, `generality` (animation, real).

### Implementation
   
- Build a decision tree with questions that help to decide which type of movies the user would like.
- The decision tree should store `Yes` or `No` **questions**.
- Read the movies from the array.
- Based on the user's answers the system should recommend a movie for the user that meets the user's preferences.

Run time example:

Figure 1    
<img width="350" alt="Example" src="https://github.com/SAFCSP-Team/movie-recommendation-project/blob/main/images/movie%20recomendation%20system.jpg">

   
Based on the user's answers, the recommended movie should have the following properties:

- Type: action movie.
- Kind: real movie.
- Year: before 2000.
- When searching for the movie with the above properties, we will pick the most rated movie.

Decision:

Figure 2    
<img width="350" alt="Example" src="https://github.com/SAFCSP-Team/movie-recommendation-project/blob/main/images/Decision.jpg">





