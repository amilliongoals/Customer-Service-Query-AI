#Return Policy Assistant

Returns are a tricky business, the goal of this project is to leverage AI to create a chatbot that in theory could be used by a customer service rep to assist them in making decisions. 



Steps Completed 
1)Acquired data sets
2)Established coding environment in Google Colab, shifting from Kaggle to experience new tools and prepare for practice with Google Gemini and rest/gain experience with their new co-pilot coming out
3)Connected with OpenAI key - tested connection in notebook 
4)Working on cleaning text file 
    -Determined effective normalization and cleaning procedures e.g
, keeping capitalization, removing html, removing specific symbols.

Currently: deciding on tokenization methodology.






To-Do-List 
1) Train a chatbot around a set of return policy data
2) Have it take the role of Customer Service to advise the policy given a scenario prompt
3) Test a variety of scenarios, and place them on a table (prompt & response)
4) For incorrect or poor responses, improve them to be the desired result or remove
5) Utilize that new table for reinforcement learning/fine-tuning
6) Repeat until satisfied with the results
7) Create a feature of 'Was this helpful?' that is stored with the query and response as data to support large-scale reinforcement.
  
In a real-world use case, if calls were recorded they could be encoded speech-to-text into the text being directly fed into the chatbot as a query, and when the result is bad per CS rep, that data can be sent for further training.  
