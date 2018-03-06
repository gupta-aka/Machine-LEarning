# Machine Learning

The question arises -> Why Machine Learning?
Personally I believe Machine Learning is the one of the disciplines that allow you to explore different fields and learn vast new knowledge each time you do so.

As the name suggests, When the Machine [ROBOT] can learn autonomously.
Spam Filtering, E-Commerce, news feed in social apps etc.

They all are the examples of Mahcine Learning which are evolving daya by day as humans have evolved.

Now what I am more keen about is HOW?
HOW can we make our machines learn. How can we create algorithms for Machine Learning.

Lets start from the basics...
-> Supervised Learning [When both input and output are known.]
-> Unsupervised Learning [Only the input is known. (logic or depepndence in the input is to be found) Clustering is the example]
-> Reinforcement [acts in the environment on the basis of rewards it get. Training a dog is the instance that can be correleated.]

The building blocks of Machine Learinng can be categorised as:
- Representation -- It includes modelling of data 
- Evaluation -- It includes the function that needs to be evaludated on the basis of provided input and output.
- Optimisation -- It includes the algorithms that optimise the evaluated function.

Key Point: - Machine Learning is the model that gives a certain output for certain set inputs.
So Mathematically, We have input [x] and output [y] also. What we need to find is the function that gives correct output for set of some inputs.
i.e 			y = f(x)  where f() is the Machine learning algorithm which is trained.
				y = ax + b where a (coefficient) is known as Weight and b (constant) is known as bias [Linear Model]
Point to note:  number of weights depends on both input and output. i.e if there are m outputs and k inputs then weights are m*k [There is different for each input and each equation]
				number of bias is equal to number of outputs i.e if number of outputs is m then biases are also m.

Hence if there are n observations, then [n*m = n*k + m*k + m], Weight and Biases does not depend on number of observations.

Note: Training is done to make sense out of input data.
Four ingredients for training the ML Algorithm are:
-> Data [Mostly a historical data]
-> Model []
-> Objective Function [It estimates how the correct the model output are] => Comprises of LOSS Function (Mainly for Supervised Learning) or REWARD function (Reinforcement)
NOTE: Objective function is not related to model and is used for every type of algorithm irrespective of its linearity.
-> Optimisation Algorithm [It consist the mechnaics through which we vary the parameters[weights and biases, not the logic] of the model to optimize Objective function].

Machine Learning is an iterative process.
[Feed the data into model, compare it with objective function, vary it with optimisation function] This process repeats.

TRAINING the model is essentially a trial-and-error process, but each consequent trial is better than the previous one, as we have methods in place to give feedback to the algorithm.

*******************SUPERVISED LEARNING*************************
It can be categorised as:-
=>Classification -> provide ouputs which are categories [Objective function for this type of learning is called CROSS - ENTROPY]
=>Regression -> provide outputs which are numerical type i.e Continuous numbers[Objective function for this type of learning is called L2-norm - Least Square Error]

