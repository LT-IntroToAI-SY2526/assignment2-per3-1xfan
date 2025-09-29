# Assignment 2 - Write UP
## Description
This assignment is about learning and applying the while loop and iterating through multiple lists at a time.  We also will discuss how we match things in chatbots in order to extract what a user is trying to find.  Next assignment we will work with data bases and how we can extract information from them.

## What to complete
1. Go through the notes.py file w/ Mr. Berg
2. Complete `a2.py`, Mr. Berg will walk everyone through the process
3. Make sure you pass all asserts in `a2.py`
4. Complete the reflection problems below
5. Push your code to github for grading

## Reflection Questions
1. What was difficult for you while completing the match function?

The most difficult part for me while completing the match function was the syntax for #2, when we handled what happens when we have a % in the pattern. I had a hard time understanding the syntax we used for this case.

2. Explain how you could use the match function for extracting information from a movie database.

I could use the match function for extracting information from a movie database by using it to match user queries with specific patterns that correspond to movie attributes. For example, if a user asks "Who directed Inception?", the match function could identify the pattern "Who directed _" and extract "Inception" as the movie title. This would allow the chatbot to retrieve the director's name from the database. Similarly, for a query like "What is the genre of The Dark Knight?", the function could match "What is the genre of _" and extract "The Dark Knight" to find its genre in the database.
