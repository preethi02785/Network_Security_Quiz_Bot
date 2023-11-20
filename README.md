# Network_Security_Quiz_Bot
## PROJECT DESCRIPTION

This project focuses on building a Quiz bot based on the network security coursework. The bot is designed in a local environment to ensure data privacy is not compromised which helps us learn network work security skills. The quiz bot provides users with randomly generated questions and questions on specific topics we train the bot from a network security database which includes lecture slides, quizzes, homework, textbooks, and information over the internet. Further, it offers a diverse range of question formats which includes True or False, Multiple Choice, and open-ended questions. Based on the choice of user the quiz bot questions are displayed for the user to answer and it also has a feature to provide feedback to the user for the questions answered and also the source of the question which creates an informative learning experience.

## ENVIRONMENT
The project is executed in the Google Colab text editor. Which has its terminal and run time environment.
## SYSTEM ARCHITECTURE


## PREREQUISITES
* The recent Python version used is Python 3.12.0
* An API key for the GPT API from Openai.com
  
## REQUIREMENTS And Adopted Libraries
* Python programming language
Python is an interpreted, high-level, general-purpose programming language. Its language constructs and object-oriented approach aim to help programmers write clear, logical code for all kinds of projects.
* Google Colab text editor
* Open API key
An API key is a unique code that identifies your requests to the API. Your API key is intended to be used by you. The sharing of API keys is against the Terms of Use. As you begin experimenting, you may want to expand API access to your team.
* Installing required packages(open, difflib, PyPDF2):
  * OpenAI: You can install it using pip install OpenAI
  * difflib: It's part of the Python standard library, so no separate installation is required.
  * PyPDF2: Install it with pip install PyPDF2. 

## FEATURES
* Generates questions from a given text using the OpenAI language model.
* Conducts a quiz with multiple question types: MCQ, True/False, and Open-ended.
* Handles different question types gracefully.
* Randomly selects questions for a mixed quiz.
* Checks user answers and provides feedback.

## ISSUES FACED DURING EXECUTION AND THEIR SOLUTION
* API Key: Make sure your OpenAI API key is valid and has the required permissions.
* Missing Packages: If you encounter any "module not found" errors, install the required packages using pip install <package_name>.
* Solutions for Open-ended question answers: Ensure that the answers provided are single sentences.

## SUGGESTIONS AND FEEDBACK
* User-friendly interfaces and accessibility features could be implemented to make the quiz bot more inclusive and widely accessible.
* Potential enhancements could include expanding the question database.

## Step-by-step Instructions for Executions
* Step-1:
Ensure that the Openai API key is Active.
* Step-2:
Upload the Dataset in Google Colab.
*Step-3:
Run the code.
Now, Select a topic of your choice.
*Step-4:
Select a type of question of your choice
  1. Multiple choice questions
  2. True/False
  3. Open-ended questions
 * Code will generate 10 random questions based on the type of question selected.
 * The code will generate feedback and source from where the question is developed from.
 * At the end of execution it will provide us the feedback on the number of questions that are correctly answered.

## Describe Training data and data formats
 It uses pre-defined sets of questions and correct answers for different question types like Multiple choice, True/False, and Open-ended questions.
## REFERENCES
1. https://dev.to/debakarroy/how-to-build-a-personalized-unlimited-quiz-app-in-minutes-chatgpt-api-edition-do1
2. https://blog.devgenius.io/how-to-build-a-multiple-choice-quiz-with-chat-gpt-fcfadbeb2cbe
3. GitHub:https://github.com/langchain-ai/langchain - Building applications with LLMs through composability
4. https://github.com/Chainlit/chainlit
   


 

