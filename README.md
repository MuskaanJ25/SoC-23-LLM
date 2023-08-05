# SoC 2023 Learning the Latent Structures in LLMs

## FINAL REPORT

### Week 1-

#### Basics of deep learning, and neural networks. Some of the main concepts here were:
  
  - Negative Log Likelihood /n
  - Activation functions like Relu and Softmax
  - Gradient Descent algorithm
  
 #### Modelling data that humans can read into a form that our machine learning models can understand and process - Word Embeddings.

Represent words in numerical data as one hot vectors
Understand Distributional Semantics. Some ways of doing this using Count Based Methods:

  - Simple Co Occurence Counts
  - Positive Pointwise Mutual Information(PPMI)
  - Latent Semantic Analysis

### Week 2-

#### Basics of python libraries- pandas, pytorch, numpy and matplotlib

Learnt how neural networks can be made easiy using these libraries. 
- A large part of this week was spent in familiarising myself with Pytorch as it's my first time working with it
- A little brush up of np and matplotlib 

#### Partial Convolution Layer
- Understanding Partial Convolution Layer and coding it using pytorch
- It was originally proposed for image inpainting tasks because a corrupted image processed by a standard convolutional often leads to artifacts
- Partial Convolution performs the normalization of the output to adjust for the fraction of missing data. A partial convolution layer comprises masked and re-normalized convolution operation followed by a mask-update setup

### Week 3- 
Consists of a mini-hackathon, which I am yet to do.

### Hackathon 
Consisted of 2 tasks- first, to build a model that computes the probability of a passesnger's survival aboard the Titanic given multiple features, and second, come up with an improvisation in the modelling process given some more data.

#### Task-1
It was a basic problem on neural networks, the only challenge being to write it using pytorch. I took a fair bit of online help to write the code, but finally understood it's intricacies. 
- Learnt about Optimizers and nn.Module
- Learnt to handle and manipulate tensors and switch between np.array and tensors

#### Task-2
It was a simple, yet deep question. 

Overall, I really enjoyed the Hackathon :))

### Week 4-8:
Caught up on Week 3 and read the resources and watched videos shared. 
The final project was cancelled. 

#### Topics covered:
- Text pre-processing, including PoS tagging
- Text classification
- Using word embeddings
- Recurrent Neural Networks
- Coded up Andrej Karpathy's Micrograd to get a hang of making classes to use neural networks
- Went deeper with Makemore by Andrej Karpathy
- Watched Andrew Ng's course on RNNs
    - Various RNN architectures
    - Gated Recurrent Units (GRU)
    - Long Short Term Memory (LSTM)
    - Bidirectional RNNs
    - Deep RNNs
    - More on usage and understanding the rationale behind word embeddings

### More in the video: 
I go into the code for micrograd, and talk a little about RNNs and Word Embeddings
[Drive link for the video]()
