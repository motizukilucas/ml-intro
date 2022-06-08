Ref: https://realpython.com/python-ai-neural-network/#neural-networks-main-concepts

# Neuto Networks
## Intro
A Neuro Network is a system that learns to make "predictions" using:
    1. input data
    2. making prediction and comparing it to desired output
    3. adjust and improve

## General
### Core Terms
    * vectors
    > data is stored as vectors (arrays). each layer transforms the data from previous one. Ex:
    input data > vector 1 > vector 2 > result
    * layers
    * linear regression
    
### Training
The training process of a neuro network is similar to trial and error, like in the intro it will make predictions trying to mtch the desired output and repeat this process to refine it's "algorithm". Steps of a "human" training:
    1. Throw dart at the target
    2. Observe where it landed
    3. Adjust hand position
    OBS: the adjustment is based on step 2 result, with neuro network it should be similar to this process

### Vectors
Neuro networks are operations with vectors, it's good because of **dot product** 
> it tells us how similar are two vectors scaled by their magnetude

The idea is that you want to know how similar is a input across it's previous ones, if similar it should generate an expected result/prediction

### Liner Regression Model
