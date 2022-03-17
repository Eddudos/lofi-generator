# CNN and RNN lofi generator
Neural Network for generation of lo-fi music for CS486. 
There is two separated sections for CNN and RNN generation methods.

Follow this steps to run the project:
1. In the .ipynb file run code by blocks.
2. Run "Processing the midi into a notes array" blocks. This only needs to be run once to store the notes as an array to the file. 
3. Run the "Processing the notes array into the numpy array format for the NN" block.
4. Run "Create the model and its layers" which will build the specified model (default one is the one tuned by us).
5. If you want to train the model and store weights from scratch load previously stored weights into the model, run "Generating model from previously trained weights" with your desired file path.
6. After training or loading weights into a model, run "Generate Music with Model" to produce some notes/chords and then run "Play the midi" to listen to the results.
