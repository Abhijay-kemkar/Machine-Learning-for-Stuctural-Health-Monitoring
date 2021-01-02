# Machine Learning for SHM

## SSI-DATA
- First we need to run the SSI-Data Code. 
- We need to run this code with inputs as Y matrix, i which is the number of Henkel Blocks required and modal number n.
- We will get outputs as the matrices A(state space matrix) and C(output matrix).

## SSI-COV
- We need to pass Y (time series vibrations) and time step dt to the code.
- The output we will get is varagout.

## ANN 
- The input we need to be last column as ground truth and earlier columns as state space outputs from either SSI-data or SSI-COV. 
- Then we need to adjust the number of neurons in the input layer, first hidden layer and output layer. 
- Then run the code.
- We will get the predicted vibrations/accelearations as the output matrix
