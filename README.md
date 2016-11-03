# Winning Jeopardy.

Jeopardy is a popular TV Show in the US where participants answer questions to win money. It's been running for a few decades, and is a major force in popular culture.
Let's say that we are thinking about competing on Jeopardy, and that we want to look for an edge to help us win. This project will examine Jeopardy questions to discover if there is any pattern in the questions that help us win.
Our dataset jeopardy.csv contains 20000 rows of Jeopardy questions, with the next additional information:
Show Number: Jeopardy episode number where the question was asked.
Air Date: The date the episode aired.
Round: The round of Jeopardy the question was asked in.
Category: The category of the question.
Value: The prize a person could get answering the question correctly.
Question: Text of the question.
Answer: Text of the answer.
The dataset is formated in JSON and can be found [here](https://www.reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/).

# Table of Contents

1.- Jeopardy. Introduction to the Data.
2.- Libraries.
3.- Importing Data and Normalizing Data.
4.- Normalizing Numeric Values.
5.- Questions.
6.- Low Value Vs High Value Questions.
7.- Applying the Chi-Squared Test.
