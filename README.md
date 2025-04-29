# cse472-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE472 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cse472-in-this-assignment-you-will-have-to-implement-a-convolutional-neural-network-for-an-image-classification-task-there-will-be-six-basic-components-in-your-neural-network-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112868&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE472 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this assignment, you will have to implement a convolutional neural network for an image classification task. There will be six basic components in your neural network:

1. Convolution layer: there will be four (hyper)parameters: the number of output channels, filter dimension, stride, padding.

2. Activation layer: implement an element-wise ReLU.

3. Max-pooling layer: there will be two parameters: filter dimension, stride.

4. Fully-connected layer: a dense layer. There will be one parameter: output dimension.

5. Flattening layer: it will convert a (series of) convolutional filter maps to a column vector.

6. Softmax layer: it will convert final layer projections to normalized probabilities.

The model architecture will be given in a text file. A sample architecture is shown for your convenience.

Conv 6 5 1 2

ReLU

Pool 2 2

Conv 12 5 1 0

ReLU

Pool 2 2

Conv 100 5 1 0

ReLU

FC 10

Softmax

You will have to implement the backpropagation algorithm to train the model. The weights will be updated using batch gradient descent, where instead of optimizing with the loss calculated over all training samples, you will update gradients with a subset of the training set (ideally 32 samples) in each step.

You will work with two datasets: MNIST and CIFAR-10. Both datasets are openly available and have 50k-60k samples. Split the evaluation set into half so that you can use 5k samples for validation and 5k samples for test purposes. You will also be given a toy dataset to test whether or not your implementation of the backpropagation algorithm works correctly.

You have to report the validation loss, accuracy, and macro-f1 for each epoch (one pass over the full training set). You will train your model for 5-10 epochs (more if it is runnable in reasonable time). Make sure you tune the learning rate (start from 0.001). Select the best model using macro-f1 and report the above-mentioned scores.

No deep learning framework is allowed for your implementation. No hardware acceleration is required (but allowed if you want to). Since the architecture is not fixed, you have to modularize your code in such a way that it works for any architectures that use the six mentioned layers. To make your implementation efficient, try to pose each operation as matrix multiplication.
