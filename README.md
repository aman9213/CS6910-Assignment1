# CS6910-Assignment1

The Assignment code is in the assignment1_final.ipynb file. This file contains all the code that is required for Assignmnet 1 of Deeplearning.  
    
By changing the sweep configuration user can select the different hyperparametrs.   
   
Below are the important functions used in the code:  
   
**Function name : feed_forward**   
**Arguments :** x (Input features0, theta(dictinary of weight and bias) , activation.   
**Returns :** y_hat (predicted output), H (output of every layer), A(weighted sum of input)  
**Description :** this function is responsible for performing the feed forward propagation  
  
  
**Function name : back_prop**  
**Arguments :** y_hat, y, H, A ,layers (no.of layers) ,theta , activation, batch_size, l2  
**Returns :** grads (gradients)  
**Description :** this function is responsible for performing the Back propagation  

  
**Function name : gradient_descent**   
**Arguments :** typee (optimizor type example: adam), batch_size,epoch, lr (learning rate), theta, activation, l2,update,e   
**Returns :** theta   
**Description :** this function is responsible for performing the all gradient descent algorithm.   
     
     
**Function name :tune**
**Arguments :** None
**Returns :** None
**Description :** this function is responsible for performing the wandb sweep.
     
    
**Function name : tune_best_test**    
**Arguments :** None   
**Returns :** theta    
**Description :** this function is responsible for training the model with best hyper-parameter configuration.    
