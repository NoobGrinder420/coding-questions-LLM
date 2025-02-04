# Leetcode-LLM
Made this mini project during a LLM bootcamp at Republic Poly

#Please run code in google colab and change google drive directories accordingly in the code

code does the following:
- asks user for input on the type of question they want
- prompt engineering to send it to openAI to find the closest question
  - deprecated
  - can still see prompt engineering
- scrapes questions from github and finds other questions with relevant topics using PyDantic
- sends it to openai API
  - deprecated as there is no longer an API Key and we had to remove the function for code to still work
  - Langchain and Langgraph code is still visible
- openai returns a modified leetcode question with different context and solution
  - deprecated so code just returns an unedited leetcode question
