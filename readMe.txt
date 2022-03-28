- All the code files are available in this folder:

- Pre-processing TRAIN and TEST data.ipynb (is the text pre-processing file)
	- Part 1: 
  		- baseline.py 
	- Part 2:
  		(a) lstmANDbilstm.py (code for LSTM and Bi-di LSTM)
		(b) dl-cnn.py (code for the CNN model)
		(c) deepNN.py (code for the Deep Neural network)
  	- Part 3:
		(a) pre_processing.py (code for the pre-processing of the unlabelled data)
		(b) lstm-unlabelled.py (code for predicting the unlabelled data)
		(c) analysis.py 
	- final_results.py (writing the results to the text file)

	- glove.6B file - text file was used for embedding
	- downloaded from here "https://nlp.stanford.edu/projects/glove/"
	- please create a folder 'golve.6B' and paste the glove.6B.300d.txt file in it.

- Apart from the code files there are .pkl files, which were used to store outputs that can be easily used for different files, without having to rerun the code again and again.

	- train.pkl (contains the pre-processed train data)
	- test.pkl (contains the pre-processed test data)
	- LR_GS_Agency.pkl (contains the hyper tuned model for LR on Agency label)
	- LR_GS_Social.pkl (contains the hyper tuned model for LR on Social Label)
	- SGD_GS_Agency.pkl (contains the hyper tuned model for SGD on Agency label)
	- SGD_GS_Social.pkl (contains the hyper tuned model for SGD on Social label)
	- unlabeled_data.pkl (is the pre-processed daraframe for the unlabelled data)
	- predicted_unlabeled_data.pkl (is the data frame with predicted values for the unlabelled data)
	- predicted_data.pkl (is the data frame with the final predicted values for the test dataset using both the train and predicted_unlabeled data)

- The Result is stored in the Results.txt file.
- Please find the report in the Report.pdf file.
