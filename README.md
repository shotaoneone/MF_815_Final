# MF_815_Final

Mutual_fund_chat_4_shota (1).ipynb answers following question from the project guidline
- Using Langchain and OpenAI API to apply RAG to all fund prospectus in the
dataset. Ask the RAG algorithm to classify funds into Balanced Fund, Fixed
Income Long Only, and Equity Long Only. Ask the RAG algorithm to return
supporting evidence.

RAG_Comparison.ipynb answers following question
- Compare the RAG results with the Investment Strategy
labes in “Mutual Fund Labels”. Report your comparison results. Pick several
funds where the labels from these two sources are not the same. Comment on
which source is closer to the truth.

To do
3. Use the classification results from RAG as the “ground truth” to train your
classification algorithm next.

  3.1 ~~Split the data into training, validation, and testing.~~ Done! 4/29 
  
  3.2 Following the NLP application in class, use the skip-gram model to build a
  word embedding dictionary from the mutual fund prospectus in the training
  set. <- working on this right now
  
  3.3Design a strategy to build knowledge bases associated to aforementioned
  three main mutual fund styles.
  
  3.4Measure distance of each summary to each knowledge base. Design a
  classification algorithm to predict the investment strategy of each fund.
  
  3.5Use validation data to tune your parameters of your classification
  algorithms.
  
  3.6Apply your classification algorithm to predict the investment strategy of each
  fund in the test data. Report your classification results in the test set.
