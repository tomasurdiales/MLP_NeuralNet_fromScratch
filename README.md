### 6. Open Question (40 points)
In this exercise, you are asked to implement a Multi Layer Perceptron (MLP) network from scratch. In the assignment .zip file, you can find a small two-classes dataset divided into two .csv files: _data/train data.csv_ and _data/validate data.csv_. Each row represents a data point. The first two columns (x1, x2) represent the two input features. The third column (y) represents the class label (0 or 1). We would like to fit this data using the MLP network. The network consists of 2 hidden layers. Each layer consists of 10 neurons. The network should be trained using Backpropagation (see also the JupyterBook for further details about the Backpropagation algorithm) and mini-batches Stochastic Gradient Descent (SGD) as explained in the lecture. To this end:

**(a)** Import the data in Python and explore it a bit.\
**(b)** (5 points) Perform data normalization. Choose one of the data normalization methods discussed in the lecture (e.g. Zero-mean-unit-variance, Min-Max normalization, etc.) and apply it on the data. Report the formula that you used in the report and discuss your choice. Include in your report the first 4 samples of the training data after transformation.\
**(c)** (1 points) Determine the size of the input and output layers. Report your answer by drawing the MLP model’s structure.\
**(d)** (2 points) Choose a suitable loss function and activation function for the first and second hidden layers ϕ1, ϕ2. Report and justify your choice.\
**(e)** (2 points) Choose an initialization of the parameter values. Report and discuss your choice.\
**(f)** (10 points) Implement the MLP network from scratch with the specification stated above and the Backpropagation algorithm to train the network. We will run and check the uploaded Python code. To obtain the points for this subproblem: i) the Python code has to run with no errors and ii) the MLP model and the Backpropagation algorithm have to be implemented completely from scratch. Note that you are not allowed to use any library which implements MLP models, but you are allowed to use auxiliary libraries (e.g. Numpy, Matplotlib, Pandas).\
**(g)** (10 points) Tune the hyperparameters: learning rate, batch size, number of epochs. Try to achieve the best validation accuracy you can. In this subproblem, part of your grade depends on how well your model performs. You should at least get 70% on the validation set to obtain points greater than 0. You can get the full points when you are close to the maximal performance, ∼ 97%, on the validation set (i.e. ≥ 90% should be fine to obtain the full points). Report the best values for each hyperparameter.\
**(h)** (5 points) Plot the loss computed over the training set and over the validation set. In addition, plot the classification accuracy computed over the two sets. Choose a stopping criteria for your training. State and justify your stopping criteria. Include your answer and the plots in your report.\
**(i)** (5 points) Report the final accuracy.

---

![alt text](https://github.com/tomasurdiales/MLP_NeuralNet_fromScratch/blob/main/figures/diagram.png?raw=true)

### Result:

![alt text](https://github.com/tomasurdiales/MLP_NeuralNet_fromScratch/blob/main/figures/pic3_front.png?raw=true)

![alt text](https://github.com/tomasurdiales/MLP_NeuralNet_fromScratch/blob/main/figures/pic4_front.png?raw=true)
