# Keno
Try to solve keno
This is a Neural Network that attempts to predict the next 20 numbers of keno.  
I try to comment my code as best as I can, so it should be understandable once 
you get into the code.


The file "Load_Keno_Nums" uses beautiful soup to access the Ohio lottery website and scrapes the drawings from there.
The sets of "drawings" (20 elements of type int) get formatted based on year and other formatting techniques to create
a 20 element list of ints to process.

The "Predict_Keno_Nums" uses keras to create a sequential model with 3 layers.  I save the model but also generate a prediction. 
You can separate this into 2 files once you have trained the model to avoid the time of retraining. 
