# Hand-Tear
If you also have trouble with hand-tearing code, We can provide you with some simple hand-tearing code cases, and hope it can help you! 👻
Welcome to submit PR to enrich thir repo~

### 1. ScaledDotProductAttention fuction [SDPA_I.py](https://github.com/cool-chicken/Hand-Tear-ML-Code/blob/main/SDPA_I.py)

- We abbreviate the fuction by calling it SDPA

$$ Attention(Q,K,V) = softmax( \frac{QK^{T}}{\sqrt{d_{k}}}) $$

### 2.MultiHeadAttention fuction [MHA.py](https://github.com/cool-chicken/Hand-Tear-ML-Code/blob/main/MHA_I.py)
- We abbreviate the fuction by calling it MHA
- firstly, change the single head into multihead
- secondly, focus on output as a single head
- thirdly,the final output is obtained by affine transformation

### 3.stochastic gradient descent[SGD_I.py](https://github.com/cool-chicken/Hand-Tear-ML-Code/blob/main/SGD_I.py)
- We abbreviate the fuction by calling it SGD

### 4.backward propagation[BP_I.py](https://github.com/cool-chicken/Hand-Tear-ML-Code/blob/main/BP_I.py)
- We abbreviate the fuction by calling it BP
- Using gradient descent, to update the weight of all, so in the forward propagation its output is more specific

### 5.k-means example[k-means.py](https://github.com/cool-chicken/Hand-Tear-ML-Code/blob/main/k-means.py)

### 6.RNN example[RNN.py](https://github.com/cool-chicken/Hand-Tear-ML-Code/blob/main/RNN.py)
- We abbreviate the fuction by calling it RNN
- Defines an RNN model, contains an RNN layer and one output layer. 
- generate_data function: Generate random data and simulate training data. 
- train function: 
  - The loss values were collected for each epoch. 
  - List training model and return loss value.