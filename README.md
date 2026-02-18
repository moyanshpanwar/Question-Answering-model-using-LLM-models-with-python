In the competitive landscape of the airline industry, customer satisfaction and brand loyalty are critical for sustaining long-term success. This study introduces the Question Answering System using Python and LLM Models”. This project presents an intelligent query-driven data analysis system using a Large Language Model (LLM) integrated with Pandas for exploring ICC Cricket World Cup datasets. The system leverages the QueryPipeline architecture, which combines natural language understanding, prompt engineering, instruction parsing, and automated Pandas code generation. By utilizing the Llama3 model via Ollama, the system effectively converts user queries into executable dataframe expressions and delivers meaningful, human-readable responses.
The dataset includes match statistics such as total runs, overs played, run rates, match outcomes, team performance, opponent details, venues, and dates. Using natural language queries, the system accurately performs operations like filtering, aggregation, comparison, and statistical evaluations. This enables detailed insights into team performances, historical trends, and match dynamics without manually writing code.
The results demonstrate that the model can successfully interpret contextual cricket-related questions, generate correct Pandas expressions, and produce accurate outputs—highlighting its efficiency, interpretability, and reliability. This approach provides a powerful solution for automated sports analytics, making complex cricket data exploration more intuitive and accessible for analysts, researchers, and enthusiasts.






1.	Installation of Ollama:
•	Install the Ollama from the official website of ollama “http://ollama.com”.
•	Install the required model from the ollama for the work.


2.	Install the jupyter:
•	Install the anaconda from the official website “http://anaconda.com”.
•	Create a jupyter notebook inside the folder “project fr”.


3.	Connect the mode to jupyter notebook:
•	Build the connection between the model and jupyter notebook by typing in command prompt “llamaenv\scripts\activate”
•	Type “jupyter notebook” to create the python file.


4.	Extract the csv file:
•	Extract the csv file from the internet and install it into the folder,
•	To download the csv file type “https://raw.githubusercontent.com/BUFONJOKER/icc-cwc-dataset/main/icc_cwc.csv"

 
5.	Import the libraries:
•	Import the required libraries for query engine, query pipeline and input component
•	Use pandas to work with csv file.
•	Import the ollama library to run the model locally


6.	Import model into the source file:
•	Import the model into the source file


7.	Write the prompts :
•	To make the model run accordingly, write the prompts for providing the instructions to the model.
•	To specify the quality of the response, write the specific response prompts for the model

8.	Connect the query engine and other modules with the LLM model:
•	Now we will build connection between the modules.
•	To establish the connection, use link function and add_chain function to connect all the modules. 
