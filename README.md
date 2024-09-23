# Semantic Spotter

Building a semantic spotter pipeline with LlamaIndex.

## Prerequisites to Run the Semantic Spotter

1. **Install Required Libraries and Dependencies**:  
   Run all the cells that install the necessary libraries and code dependencies.

## Steps to Run the Semantic Spotter

1. **Mount Google Drive**:  
   Mount Google Drive and change the path to where the files are stored. Execute the next block to read all the PDF files.

2. **Set API Keys**:  
   Read the `OPENAI_API_KEY` or `cohere_key` from user data if available.

3. **Create Nodes**:  
   Create nodes from the read documents and store them in a vector index.

4. **Query the Index**:  
   - Create templates and pass those templates to the index as a query engine.
   - Start querying the indexed data.

5. **Extract Query Response Details**:  
   Extract source node, filename, page number, and text from the response provided by the query engine.

6. **Define Evaluation Parameters**:  
   Set up the evaluation parameters for assessing the responses.

7. **Loop Through Multiple Questions**:  
   Create a function to loop through multiple questions and process them.

8. **Evaluate the Responses**:  
   Pass the generated responses to the evaluation parameters and check the scores using the response evaluator.
   
## Technologies Used
1. **Pandas**
2. **LLAMAIndex**
3. **OPEN API**
4. **SentenceTransformer Rerank**

## Contact
Created by Gaurav Dhuri
Developed as part of the Advanced Regression Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
