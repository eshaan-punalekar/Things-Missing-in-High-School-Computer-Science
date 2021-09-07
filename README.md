# Things Missing in High School Computer Science

_Eshaan Punalekar_

## Introduction ##

Being a high schooler myself on the computer science path, I often find myself searching for different topics in the field that lie past the scope of generic high school courses (AP Computer Science Principles, AP Computer Science Applications, and any other basic courses your high school offers). However, I firmly believe that these high school courses are much needed to grasp the intricacies of complex computer science topics. Consequently, I have decided to create a comprehensive guide that thoroughly explores topics that I believe every high school student looking to leave college with a CS degree should know of. Throughout this guide, I will be providing links to research papers, courses, blogs, and other websites that will provide you with extra information on the topics covered.

Before we start, let’s go over the basics. According to an [article](https://www.britannica.com/science/computer-science) by Britannica, computer science is defined as “the study of computers and computing as well as their theoretical and practical applications. Computer science applies the principles of mathematics, engineering, and logic to a plethora of functions, including algorithm formulation, software, and hardware development, and artificial intelligence.” Average high school computer science courses thoroughly explore computer functionality (parts of a computer etc.), offer a light exposure to ordinary coding languages (Python, Java), and hardly encourage application-level software development. This guide dives into the worlds of artificial intelligence and machine learning, cybersecurity, web development, web design, software development, and app development. 

Throughout this guide, you will come across courses and projects that require coding. Knowing Python and Java are a must! If needed, you can check out a full Python tutorial on YouTube [here](https://www.youtube.com/watch?v=rfscVS0vtbw&ab_channel=freeCodeCamp.org). You can also check out a full Java tutorial on YouTube [here](https://www.youtube.com/watch?v=Qgl81fPcLc8&ab_channel=Amigoscode). In addition, here are a few IDEs that, in my opinion, are among the best: [PyCharm Community Version](https://www.jetbrains.com/pycharm/download/#section=mac) (Python), [IntelliJ IDEA](https://www.jetbrains.com/idea/) (Java), [Sublime Text](https://www.sublimetext.com/) (HTML, Javascript, other), [XCode](https://developer.apple.com/xcode/) (Mac users), [Android Studio](https://developer.android.com/studio).

So, let’s dive right in.

## Artificial Intelligence ##

Artificial intelligence is often linked to humanoids, robots, and the concept of how machines will eventually overpower humans. However, artificial intelligence is nothing more than tons and tons of complex algorithms comprising a bunch of clever math and long equations. It is a simulation of human intelligence processes performed by machines and computer systems. An artificial intelligence model aims to closely replicate a human brain’s decision-making abilities, and tries to maximize efficiency and accuracy and minimize the loss function (errors). 

First off, here is a [free course](https://www.coursera.org/learn/ai-for-everyone) on Coursera that explains the principles of AI in simple terms, taught by the ‘Father of AI,’ Andrew Ng. This four-week course walks you through important AI terminology, machine learning and deep learning, the workflow of a machine learning project, integrating AI in a company, case studies, AI bias and its role in society, how AI can help develop economies, and so much more.

Now, let’s talk about the AI-driven workflow.

For a complete AI-driven workflow we should consider 4 important steps: data preparation, AI modeling, simulation, and testing, and deployment.

Data preparation, arguably one of the most important steps in the AI workflow, includes data cleansing and preparation, human insight, and simulation-generated data. To train an AI model, you should begin with clean, labeled data. It is imperative that you recognize the importance of input data, because wrong, unlabeled data, can lead to significant errors in the AI model. The image below shows clean, labeled data that will be fed into the machine learning model.

You can read more about data preparation [here](https://machinelearningmastery.com/what-is-data-preparation-in-machine-learning/).

In the AI modeling stage, the AI model learns from the input data. The goal of this stage is to produce a robust model that makes intelligent, human-like, decisions based on the training data given. Here, you would expect to see the inclusion of machine learning and deep learning, which I will be talking about later. At this stage, it’s important to have direct access to many algorithms used for AI workflows, such as classification, prediction, and regression. 

You can read about AI modeling [here](https://towardsdatascience.com/workflow-of-a-machine-learning-project-ec1dba419b94).

In the next stage, you test your model. In this stage, it is very important to repeatedly test your AI model to make sure it is fail-proof. The AI model must have an extremely high accuracy rate in a variety of cases. Simulation and testing for accuracy are crucial to validating that the AI model is working properly, and everything works well together with other systems, before deploying a model into the real world. Let’s assume we have an AI model that detects whether a car is present in an image or not. It is important to make sure that the model is tested with numerous different cases: images with a car, images without a car, images with a blurry car, images with half a car being cut off, etc. Only once the model is tested repeatedly will you know its areas of improvement.

You can read more about testing an AI model [here](https://www.forbes.com/sites/cognitiveworld/2020/01/03/how-do-you-test-ai-systems/?sh=123eeaa5afd5).

The final step in the AI workflow is deployment. In this stage, you must prepare the model in the final language in which it will be implemented. In this stage, the AI model must be fit into a designated hardware environment for final use. Below are some ways in which you can deploy a fully functioning AI model.

You can read more about deployment [here](https://towardsdatascience.com/10-ways-to-deploy-and-serve-ai-models-to-make-predictions-336527ef00b2).

As I mentioned before, machine learning plays a very important role in the field of artificial intelligence. According to an article by expert.ai, machine learning is "an application of AI that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it to learn for themselves.”

Check out [this](https://www.coursera.org/learn/machine-learning) free course on Coursera by Andrew NG which explains everything you need to know about machine learning.

Now, on to neural networks.

Neural networks are a set of algorithms that have been modeled loosely after the neurons in the human brain. Neural networks, designed to recognize patterns, interpret sensory data through a kind of raw input. The patterns that they recognize are numerical, contained in vectors, into which all real-world data, be it images, sound, text, or time series must be translated. This assortment of algorithms is used in machine learning for data modeling using graphs of neurons.

According to an [article](https://www.upgrad.com/blog/neural-network-tutorial-step-by-step-guide-for-beginners/) by upGrad, here is how neural networks work, in simple terms.

1. Information is fed to the input layer is transferred to the hidden layer
2. The interconnections between the two layers assign weights to each input randomly
3. A bias is added to every input after weights are multiplied with them individually
4. The weighted sum is transferred to the activation function
5. The activation function determines which nodes it should fire for feature extraction
6. The model applies an application function to the output layer to deliver the output
7. The weights are adjusted, and the output is back-propagated to minimize error
8. The model uses a cost function to reduce the error rate. You will have to change the weights with different training models.
9. The model compares the output with the original result
10. It repeats the process to improve accuracy
11. The model adjusts the weights in every iteration to enhance the accuracy of the output.

You can read a somewhat more in-depth explanation of how neural networks work [here](https://techandsomemore.wordpress.com/2021/04/10/how-do-neural-networks-work/).

To have a more math-based understanding of neural networks, check out [this](http://neuralnetworksanddeeplearning.com/) free online book by Michael Nielsen. The book teaches you about neural networks and deep learning while providing you with numerous real-world examples.

You can also check out [this](https://github.com/kjaisingh/high-school-guide-to-machine-learning/blob/master/README.md) guide by Karan Jaisingh, which provides high schoolers with the steps and resources to start an in-depth journey into AI and machine learning.

You can also use Google’s [Teachable Machine](https://teachablemachine.withgoogle.com/) to create a basic AI model without coding anything. Teachable Machine is a web-based tool that makes creating machine learning models fast, easy, and accessible to everyone. If you find difficulty in using Teachable Machine, check out [this](https://www.youtube.com/watch?v=kwcillcWOg0&t=508s&ab_channel=TheCodingTrain) helpful tutorial. You can learn more about training the AI model to recognize images [here](https://medium.com/@warronbebster/teachable-machine-tutorial-bananameter-4bfffa765866), training the AI model to recognize sounds [here](https://medium.com/@warronbebster/teachable-machine-tutorial-snap-clap-whistle-4212fd7f3555), and training the AI model to recognize poses [here](https://medium.com/@warronbebster/teachable-machine-tutorial-head-tilt-f4f6116f491).

And that brings us to the end of the artificial intelligence unit. Hopefully, with the resources and explanations I have provided, you can begin your high school AI experience and eventually learn to develop application-level AI models.

## Cybersecurity ##
## Web Development/Design ##
## Software/App Development ##
## Real-World Application ##
## Conclusion ##




















