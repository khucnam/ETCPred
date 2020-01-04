# ETCPred
This is the public site for the paper under submission named: "Using NLP approach to efficiently identify protein complex categories in electron transport chain"

 
Every cell uses cellular respiration machinery to oxidize food molecules such as glucose (sugars) to carbon dioxide and water, thus obtaining energy-carrying molecules in the form of adenosine triphosphate. This crucial process cannot occur without the aid of electron transport chains, a series of 5 protein complexes embedded in the inner mitochondrial membrane. A variety of human diseases such as Parkinson's disease, pulmonary hypertension, and Alzheimer's disease involve the functional loss of these protein complexes. Thus, investigating these electron complexes is an ongoing concern for biologists to better understand the molecular mechanisms of important human diseases. In this research, we employed two representation learning methods namely word embedding and transfer learning to analyse electron complex sequences and create efficient feature sets before using support vector machine algorithm to classify them. On an average, our final classification models achieved performance of 96%, 96.1%, 95.3%, and 0.86, respectively on cross-validation data. For the independent test data, those corresponding performance scores are 95.3%, 92.6%, 94%, and 0.87. Using representation learning methods, we show that simple machine learning method is on par with existing deep neural network method on the task of categorizing electron complexes while enjoying much faster way for feature generation. 

FILES:

Dataset.rar

Models.rar

fastText embedding vectors.rar

Predict.py


INSTRUCTION: 

1. Using git bash to clone all the required files in "YOUR FOLDER" folder

git clone https://github.com/khucnam/ETCPred

2. python Predict.py your_fasta_file.fasta

(your_fasta_file.fasta file contains the sequences you want to classify)

Running the Predict.py script will generate the Result.csv file. In Result.csv file, there are 6 columms: first one contains the protein ID, second sixth ones contains 5 different probabilities corresponding to each of the 5 complexes.  


