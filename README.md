# Semantic Spotter

Building a semantic spotter pipeline with LlamaIndex.

## Prerequisites to Run the Semantic Spotter

1. **Install Required Libraries and Dependencies**:  
   Run all the cells that install the necessary libraries and code dependencies.

2. **Mount Google Drive**:  
   Mount Google Drive and change the path to where the files are stored. Execute the next block to read all the PDF files.

3. **Set API Keys**:  
   Read the `OPENAI_API_KEY` or `cohere_key` from user data if available.

4. **Create Nodes**:  
   Create nodes from the read documents and store them in a vector index.

5. **Query the Index**:  
   - Create templates and pass those templates to the index as a query engine.
   - Start querying the indexed data.

6. **Extract Query Response Details**:  
   Extract source node, filename, page number, and text from the response provided by the query engine.

7. **Define Evaluation Parameters**:  
   Set up the evaluation parameters for assessing the responses.

8. **Loop Through Multiple Questions**:  
   Create a function to loop through multiple questions and process them.

9. **Evaluate the Responses**:  
   Pass the generated responses to the evaluation parameters and check the scores using the response evaluator.
