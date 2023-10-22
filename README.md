# fine tune language model
###  This project uses the following [dataset](https://github.com/PolyAI-LDN/task-specific-datasets/tree/master/banking_data) containing data about a customer service system in a US bank. The data set contains the customer request (txt) and the label - the category of the request.
## The notebook contains 3 main parts
- #### Preprocessing
- #### Data Exploration
- #### Text Classification

## Preprocessing
1. Download the task files from google drive
2. Convert the data structures csv to DataFrame
3. Convert labels categorical to numeric
4. Convert the DataFrame to DatasetDict
## Data Exploration
- Printing the first 10 records in the training file and in the test file
- Printing the frequency of the categories in the training file and the test file
- Performing tokenization and displaying word frequency
- Showing word frequency after removing stop words

## Text Classification
### Prepare a dataset
1. Tokenizer and remove stopwords
2. Selection small data set (optional)
### Train with PyTorch Trainer (bert-base-cased model)
1. Building a model
2. Evaluate
3. Training arguments
4. Trainer (Fine-tune)
5. Training summary from previous runs
