# Pytorch_Heisman_Prediction_Exploration_Model
Using online resources, datasets and leveraging AI in order to create a PyTorch Model that Predicts the Next Heisman's Winner's stats in CFB.
<img width="691" height="470" alt="image" src="https://github.com/user-attachments/assets/a49e8c40-b44e-4540-b6ce-5cd2fc8dd04b" />

Not AS accurate as I would like it to be, but after L2 Regulariation with weight decay + Early stopping, it'll have to do! There is a bit of noise on the training dataset side.

For this prpject we can say that this is the most optimal plot we have.

# Stat predictions (What does a Hiesman winner look like for 2026)

<img width="686" height="240" alt="image" src="https://github.com/user-attachments/assets/53e5002b-8a01-4f9e-93f8-ec791425faad" />



# Resources
https://docs.pytorch.org/docs/stable/generated/torch.nn.ReLU.html

https://docs.pytorch.org/docs/stable/index.html

https://www.geeksforgeeks.org/deep-learning/why-do-we-need-to-call-zerograd-in-pytorch/

https://www.geeksforgeeks.org/machine-learning/gradient-descent-in-linear-regression/ (understanding cost functions and how weights are adjusted with criterion measurement)

https://machinelearningmastery.com/making-predictions-with-multilinear-regression-in-pytorch/

https://medium.com/@frederik.vl/interpreting-training-validation-accuracy-and-loss-cf16f0d5329f

https://machinelearningmastery.com/using-dropout-regularization-in-pytorch-models/

https://machinelearningmastery.com/train-neural-networks-with-noise-to-reduce-overfitting/

https://www.geeksforgeeks.org/deep-learning/training-and-validation-loss-in-deep-learning/

https://www.geeksforgeeks.org/machine-learning/multi-dimensional-inputs-in-pytorch-linear-method-in-python/

https://medium.com/@sohineetitin/overfitting-and-underfitting-identify-and-resolve-part-2-48cbab897024

https://machinelearningmastery.com/learning-curves-for-diagnosing-machine-learning-model-performance/

https://www.linkedin.com/pulse/how-tame-noisy-training-loss-deep-learning-strategies-hallaj-zavareh-ayyqe/

https://www.geeksforgeeks.org/deep-learning/how-to-handle-overfitting-in-pytorch-models-using-early-stopping/

https://datascience.stackexchange.com/questions/52028/understanding-training-and-test-loss-plots

https://machinelearningmastery.com/learning-curves-for-diagnosing-machine-learning-model-performance/

https://www.kaggle.com/code/ryanholbrook/overfitting-and-underfitting

Use of Claude 4.5 for understanding PyTorch basics (Tensors (understanding the Data Structure), setting up Linear Reg dropout layers class, Data Cleaning, and general Debugging)

Note: I am still learning how to build some of these models, so please bear with me, as I used AI a bit more than I normally would for other projects, however I beleive, for my first exploration project, it went pretty well :). I will definetely revisit this as I gain more knowledge throughout my schooling/side projects.

HELPFUL YOUTUBE VIDEOS: 

https://youtu.be/tHL5STNJKag?si=1wzPBd-u-amZUhO6 (Rob Mulla's video on Building a classification PyTorch Model, super helpful)

https://youtu.be/r1bquDz5GGA?si=GxnOYrLa5hSFZ4p7 (PyTorch in 1 Hour by Zachary Huang, used this to understand the overview and loss.backward for Weights and Bias calculation (Partial Derivatives) and the math behind PyTorch Functions)
