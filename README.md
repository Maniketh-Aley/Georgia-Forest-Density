# Calculating Density of Georgia Forest (Deep Learning/Neural Networks)

Managing forests is an important task because over 800 million acres of the United States contain various forest environments. **A key factor in managing these forests is knowing their tree density**. This metric can help predict whether a forest should be thinned or is remaining healthy. Additionally, knowing the tree density in a forest can help to predict how climate change is affecting the environment. The two reasons why we believe this is a good problem for machine learning to solve are that populations of trees are slower to change than populations of other living things, and there are many variables at play that can be missed by human computation. 

Our main sources of data are the US Forest Service’s Inventory and Analysis Program and the Climate Research United Gridded Time Series data set. Our approach is different from other experiments because we use factors outside of the knowledge about the trees themselves, such as temperature and precipitation data. 

## Dataset
_US Forest Service’s Inventory and Analysis Program_

## Libraries and Frameworks:
Pandas, Numpy, Matplotlib.Pyplot, Statistics, TensorFlow, Keras, Scikit-learn, Machine Learning, Deep Learning (Neural Networks)

## Models Used:
1. Deep NN
2. Simple RNN
3. LSTM RNN
4. GRU RNN (LayerNormalization)
5. GRU RNN (Dropout)
6. LSTM Bidirectional RNN (Fold Validation)

   Throughout this experiment, we developed several high-performing deep learning models using recurrent neural networks to address this task. Between the six models that were tested, the GRU RNN model with dropout layers achieved the best performance with an average MAE of 0.02540 and MAPE of 31.98 on our test dataset (averaged over training 10 models).

## Results 
   Results of each model were listed in "_**Data Results**_" Folder
