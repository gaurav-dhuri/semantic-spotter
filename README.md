# semantic-spotter
Building a sematic spotter pipeline with LlamaIndex.

Prerequisite to run the Symantic Spotter.
Step1. : Run all the cell in install all required library and depended code.
Step2. : Mount google drive - change the path where the files are store - execute the next block to read all the pdf files.
Step3. : Read the OPENAI_API_KEY/cohere_key if you have from the userdata
Step4. : Create nodes from the read documents - store it in a vector index.
Step5. : Create template and pass those templates to the index as query engine and start quering in the index data.
Step5. : Extract Source node, filename, page no, text from the response from the query engine.
Step6. : Define the evaluation parameter.
Step7. : Create a function to loop through multiple questions.
Step8. : Pass the response generated to the evaluation parameters check the score from response evaluator.
 
