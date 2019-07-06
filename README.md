- DICTIONARY: Arrays containing number index with vocabularies of the languages to be translated eg [0:a,1:b,2:c]
- MODEL e.g RNN
- H = sigmoid(WX + UHt-1 + B)
        W:    weight matrix of input 
        U:    transition matrix
		X:    input   
		Ht-1: hidden state
		B:    bias
- Output Y = H.W
- TRAIN & VALIDATE: Train RNN and afterwards attempt to translate which will be referred to as a validation. The data from the validation can be used as a parameter to determine the efficiency of the model and provide inference on details that can be used to improve the model
TRANSLATE
- Translate


Error, weight, back propagated through time and layers, diminishing effect of multiple sigmoid function, sequence length, normalisation, memory, probability, alignment, differentiation, LSTM