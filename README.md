# Pytorch_Heisman_Prediction_Exploration_Model
Using online resources, datasets, and leveraging AI to create a PyTorch Model that predicts the Next Heisman Winner's stats in CFB.
<img width="1260" height="452" alt="image" src="https://github.com/user-attachments/assets/3c081fcb-963a-41ad-8754-62b023e6df27" />
<img width="691" height="470" alt="image" src="https://github.com/user-attachments/assets/b516d945-237c-4fd2-97ee-c7d50db77c9b" />


Not AS accurate as I would like it to be, but after L2 Regulariation with weight decay + Early stopping, it'll have to do! There is a bit of noise on the training dataset side.

For this project, we can say that this is the most optimal plot.

UPDATE: increased NN layers and dropout, got a better idea of a more "accurate result" for the model (You can compare both sets of code).

# Stat predictions (What does a Hiesman winner look like for 2026)

<img width="735" height="151" alt="image" src="https://github.com/user-attachments/assets/9b19df7b-d448-4404-aec4-c616da9a338b" />


Taking a look at the specified stats, we would like to see a ballpark range for a WR winning a Heisman Trophy around these stats.

UPDATE: These stats, after adjusting the model, seem to be more accurate. Predictions still stand.



# notes

The model can be improved with more data. But for my first attempt, it seems good enough. Still learning here.
In the future, more data is needed with a more specific question for prediction.


# Resources
https://docs.pytorch.org/docs/stable/generated/torch.nn.ReLU.html

https://docs.pytorch.org/docs/stable/index.html

https://www.geeksforgeeks.org/deep-learning/why-do-we-need-to-call-zerograd-in-pytorch/

https://www.geeksforgeeks.org/machine-learning/gradient-descent-in-linear-regression/ (understanding cost functions and how weights are adjusted with the criterion measurement)

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

https://discuss.pytorch.org/t/how-to-determine-overfitting-underfitting-and-best-fit-in-deep-learning-what-about-this-graph/62401

https://pyimagesearch.com/2019/10/14/why-is-my-validation-loss-lower-than-my-training-loss/ (Great article explaining training loss and why fluctuations occur)

Use of Claude 4.5 for understanding PyTorch basics (Tensors (understanding the Data Structure), setting up Linear Reg dropout layers class, Data Cleaning, and general Debugging)

Note: I am still learning how to build some of these models, so please bear with me, as I used AI a bit more than I normally would for other projects; however, I believe, for my first exploration project, it went pretty well :). I will definitely revisit this as I gain more knowledge throughout my schooling/side projects.

HELPFUL YOUTUBE VIDEOS: 

https://youtu.be/tHL5STNJKag?si=1wzPBd-u-amZUhO6 (Rob Mulla's video on Building a classification PyTorch Model, super helpful)

https://youtu.be/r1bquDz5GGA?si=GxnOYrLa5hSFZ4p7 (PyTorch in 1 Hour by Zachary Huang, used this to understand the overview and loss.backward for Weights and Bias calculation (Partial Derivatives) and the math behind PyTorch Functions)
