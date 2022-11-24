# NN-PROJECT
Group project
# Climate Change Sentiment Analysis 

## Obtaining the Data

The `data` folder contains labelled tweets based on their sentiment towards climate change: 

* 2 - the tweet links to factual news about climate change 
* 1 - the tweet supports the belief of man-made climate change 
* 0 - the tweet neither supports nor refutes the belief of man-made climate change 
* -1 - the tweet does believe in man-made climate change 
 
## Building the Model

Download the pre-trained embedding vectors from the Stanford GloVe page and extract it to the repo directory.  

`wget http://nlp.stanford.edu/data/glove.twitter.27B.zip && unzip glove.twitter.27B.zip`

Run the model script in a terminal which will train the model, output its weights and also test it against the testing set. 

The weights of a trained model is stored in the `weights` folder. 
