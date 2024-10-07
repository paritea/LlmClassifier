# LlmClassifier
CSE-584 midterms

Directory structure and further details :

- The code for making the xi's along with the code calling the LLM pipelines via hugging-face is in the CodeForDatasetCreation folder. 
The completions for each LLM are kept in the datasets_separated folder. 
- The classifier code is in the Bert Classifier.ipynb file. Unfortunately, the lime generated images aren't visible in the jupyter notebook itself. Check out the MLMidtermReport pdf to see the images!
- Finally, the report details the entire process of building the classifier!

Reproducing the results :
- Run the classifier file in kaggle to not deal with any additional package installations as pytorch, transformers and other libraries used are pre-installed there. 
- To run the file, you will have to upload or use (if you choose to do so locally) the separated datasets instead of the combined one. 


