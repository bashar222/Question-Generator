# Question-Generator
### in this project I have created a Question Generator in two ways, the first way by using text only and the second way by using the sentence mapping ,  and we made 4 steps before generating the model.
## Steps :
### 1- Text preprocessing : remove uncessary sentences and words which will affect the accuracy , such as : emails , number fo pages , punctuations (except comma and dots) and contractions.

### 2- Key phrase Exrtraction using 5 algorithms (Topic tank - Text Rank - Single Rank - Position Rank - YAKE ).

### 3- Most common keys : I collected the most frequently repeated keys and re-arranged them in descending order and choose only the most frequent.

### 4- Sentence mapping for each keyphrase : i identified for each key the sentence in which it exists and put them in a DataFrame.

### 5- Question / Answer Generator : i used ElasticSearch to Generate by HayStack.
