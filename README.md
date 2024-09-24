# Semantic Spotter Project- Build a RAG System
> Build a project in the insurance domain. The goal of the project will be to build a robust generative search system capable of effectively and accurately answering questions from various policy documents.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [how to run](#howtorun)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Project in the insurance domain. Data used is seven HDFC insurance pdf files.

## Technologies Used
- lamaindex 
- pandas 
- sentencetransformer- model-cross-encoder/ms-marco-MiniLM-L-2-v2,
- diskcache 
- openAI API key
- Jupiter Notebook

##howtorun
 - Step 1: Run all the cell in install required library and depended code.
 - step 2: If using google drive mount google drive and change the path.
 - step 3: Read the openAI key from the user data or set the path.
 - step 4: Run the cells of the notebook, run the function initialize_conv(), type in your queries, 
           when you are done , type in exit.
-  step 5:Using testing_pipeline method for multiple questions: 
          Create a list of test questions and passed to testing_pipeline. Sample questions are already given 
          for testing, either use then or change according to your query.It will ask for feedback please reposnd with good or bad.
- step 6: diskcache is used to save cache, if queries are executed for the first time, LLM will generate the response, and query and the response will
          be saved in cache, when the same query is run again, it will be fetched from cache. 
- step 7: Along with the text response, similarity score and evaluation matrix is also generated.
- step 8: Also the name of the document and page no of the document is generated, the user can verify manually if any doubt.
- step 9: Next is #### Using Customized Nodes and LLMs***
          Here customisation is done using settings. Here the default settings can be modified according to need.
          LLM, Max token, nodes etc can be changed according to need. 
          
## Conclusions
- Using this project Users would get responses from insurance policy knowledge base,If they want to refer to the original 
  page from which the bot is responding, the bot should provide a citation as well


## Acknowledgements
The project was based on Assignment given by upgrad EPGP -AIML Program.

## Contact
Created by Madhusmita Ghosh 
