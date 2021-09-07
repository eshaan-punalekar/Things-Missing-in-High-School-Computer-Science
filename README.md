# Things Missing in High School Computer Science

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

Cybersecurity is a term we hear a lot in the field of computer science. Its definition is often boiled down to talking about phishing scams and downloading viruses, but what exactly is cybersecurity?

According to the United States Cybersecurity and Infrastructure Security Agency (CISA), cybersecurity is the “art of protecting networks, devices, and data from unauthorized access or criminal use and the practice of ensuring confidentiality, integrity, and availability of information.” The importance of cybersecurity has skyrocketed in the past decade as the world now relies on computers and the internet in the form of communication (email, smartphones, tablets, etc.), entertainment (video games, social media, apps), transportation (navigation systems), e-commerce (online shopping, credit cards), medicine (medical equipment, medical records), and many more.

Cybersecurity is divided into 2 main categories. The first category includes everything to do with cyberattacks, and the second category includes everything to do with defending against those cyber attacks.

An article by Check Point says that a cyberattack is “an assault launched by cybercriminals using one or more computers against a single or multiple computers or networks. A cyber attack can maliciously disable computers, steal data, or use a breached computer as a launch point for other attacks.”

There are many ways in which a cybercriminal can gain unauthorized access to a computer, and is important to spread awareness of these different cyber attacks. The main cyber attacks are phishing, ransomware, and denial of service.

One of the oldest cyberattacks, dating back to the 1990s, phishing users disguised emails as a weapon. The attackers masquerade as a trusted entity of some kind, often a real or plausibly real person, or a company the victim might do business with. The email recipient is tricked into believing the email is legitimate and is prompted to click a link or download an attachment. Then, a virus is downloaded onto the user’s device which wreaks havoc in the user’s system, often stealing sensitive data.

You can read more about what phishing attacks are and the characteristics of a phishing attack here.

Here is a real-life example of a phishing attack where Facebook and Google saw the disappearance of $100 million. According to a Fortune article written by Jeff John Roberts, in 2013, a 40-something Lithuanian named Evaldas Rmasauskas allegedly hatched a scheme to defraud U.S. tech companies. According to the Justice Department, he forged email addresses, invoices, and corporate stamps to impersonate a large Asian-based manufacturer with whom the tech firms regularly did business. The point was to trick companies into paying for computer supplies. Surprisingly, the scheme worked. Over two years, the corporate imposter convinced accounting departments at the two tech companies to make transfers worth tens of millions of dollars.

Check out this YouTube video on how to do a phishing attack to gain a better understanding.

Next up, we have a ransomware attack. According to ProofPoint Ransomware is a “type of malicious software (malware) that threatens to publish or block access to data or a computer system, usually by encrypting it, until the victim pays a ransom fee to the attacker. In many cases, the ransom demand comes with a deadline. If the victim doesn’t pay in time, the data is gone forever.” In recent years, the frequency of ransomware attacks has skyrocketed with major companies in North America and Europe falling victim to the hands of many cybercriminals.

You can read more about ransomware attacks on the CISA website here.

A real-life example of a ransomware attack is the app CovidLock. This type of ransomware infects a victim’s via malicious files promising to offer more information about the disease. However, once installed, CovidLock encrypts data from Android devices and denies data access to victims, essentially locking the device. To be granted access to their devices, victims must pay a ransom of USD 100 per device. 

Check out this YouTube video to learn how ransomware attacks add more policy challenges to the US congress’ plates.

And last but not the least, we have denial of service attacks. According to PaloAlto Networks, a denial of service (DoS) attack is “an attack meant to shut down a machine or network, making it inaccessible to its intended users. DoS attacks accomplish this by flooding the target with traffic or sending it information that triggers a crash. In both instances, the DoS attack deprives legitimate users (i.e. employees, members, or account holders) of the service or resources they expected.” 

You can read more about DoS attacks here.

Now, a real-life example. According to A10 Networks, Amazon Web Services was hit by a huge DoS attack in February 2020. The attackers targeted an unidentified AWS customer using a technique called Connectionless Lightweight Directory Access Protocol (CLDAP) Reflection. This technique relies on vulnerable CLDAP servers and “amplifies the amount of data sent to the victim’s IP address by 56 to 70 times. The attack lasted for 3 days.

To learn more, check out this YouTube video on DoS attacks.

As you can see, cyberattacks are quite deadly and can cost users tons of money. However, it is important to recognize that most cyberattacks can be prevented.
There are numerous reports of companies that have been attacked by hackers/cybercriminals and lost significant revenue. While these threats look very complex and highly sophisticated to the inexperienced eye, most of them can be prevented by establishing the right security measures.

So, according to an article by leaf, here are 7 ways that you can protect your systems from cybercriminals.

1. Keep your software and systems fully up to date

Cyber-attacks often occur because many victims’ computer systems are not fully up to date, leaving weaknesses that hackers exploit and gaining access to your network. Once in your device, it is often too late to take preventative action. 
To counteract this, it’s smart to invest in a patch management system that will manage all your software and system updates, keeping your system resilient and up to date. Other mobile applications like McAfee continuously remind mobile and laptop users to update their software systems.
Check out McAfee here. McAfee also offers numerous other antivirus features, so you can explore their website to see how these work to gain a deeper understanding of cybersecurity.

2. Ensure Endpoint Protection

According to McAfee, “endpoint security is the practice of securing endpoints or entry points of end-user devices such as desktops, laptops. and mobile devices from being exploited by malicious actors and campaigns. Today’s endpoint protection systems are designed to quickly detect, analyze, block, and contain attacks in progress.”
Check out ESET endpoint protection here. Their website further explains how endpoint protection works and how it helps protect users and companies.

3. Install a Firewall

Based on a defined set of security rules, a firewall, which is a security network that monitors incoming and outgoing network traffic, decides whether to allow or block specific traffic. This way, a Firewall can protect your device from blocking any malware from entering your system.
Again, McAfee offers excellent Firewall protection. You can read more about how Firewalls work on their website.

4. Backup your data

In the event of a cyberattack, it is important to have your data backed up to avoid serious downtime, loss of data, and serious financial loss.
Different ways to backup your data are using a USB stick, an external hard drive, etc.
Control access to your systems
One entry into your computer systems could be physical. In a public workplace, someone could stick a USB stick into your computer port without your knowledge. This could download some malware or unwanted software.

5. Wifi security

Connecting your computer/electronic device to a secured Wifi network is very important because it prevents hackers from accessing your wireless network and stealing data using your Wifi.

6.Passwords

This one is quite obvious, but it’s important to change around passwords with different accounts to prevent a hacker from accessing all accounts at once.

Now, this is just the tip of the iceberg. There are so many topics under cybersecurity that I haven’t covered in this section of the guide, however, I will be providing you with resources to help you discover (if you have one) your path in cybersecurity.

Check out this free cybersecurity course for beginners offered by IBM on Coursera.

You can also check out this free cybersecurity fundamentals course offered by the Rochester Institute of Technology on edX.
Onto the more specific courses.

Here is a free online course offered by UC Irvine on Coursera. In the course, students are introduced to the field of cybersecurity with a focus on the domain of security and risk management. Topics include the fundamentals concepts and goals of cybersecurity (the CIA triad), security governance design, the NIST cybersecurity framework, relevant laws and regulations, and the roles of policies, strategies, and procedures in cybersecurity governance.

You can find another free course offered by Saint Petersburg State University on Coursera here. This is a great course that gives you an all-around understanding of cybersecurity, social media, big data, and how all are used and manipulated by governments and other groups to influence population groups.

Next, we have a free online course offered by the Rochester Institute of Technology on edX. The course is about digital forensics, which involves the investigation of computer-related crimes to obtain evidence to be presented in a court of law. In the course, you will learn the principles and techniques for digital forensics investigation and about core forensics procedures to ensure court admissibility of evidence. You will learn how to perform a forensic investigation and will be guided through forensic procedures and review and analyze forensic reports. 

You can find a free online course offered by MIT on edX here. This course will prepare anyone who wants to work with agencies that are worried about their vulnerability to cyberattacks. Through a series of lectures, case studies, simulations, debriefings, and short assigned readings, you will learn what cities can and should do to reduce their vulnerabilities. The course also includes checklists of various kidneys that cybersecurity vulnerability assessors need to ask and answer.

The next free online course, offered by the Rochester Institute of Technology on edX, can be found here. In this course, you will examine the various areas of network security including intrusion detection, evidence collection, and defense against cyber attacks. The issues and facilities available to both the intruder and data network administrator will also be examined to illustrate their effect. You will learn the principles and concepts of wired and wireless data network security and will be guided through a series of labs and experiments to explore various mechanisms for securing data networks including physical layer mechanisms, filters, applications, and encryption. You will also analyze attack/defend scenarios and determine the effectiveness of particular defense deployments against attacks.

Here is a free online course offered by the Rochester Institute of Technology on edX. This course will learn the key principles of risk analysis, risk assessment, and risk mitigation for information security using qualitative and quantitative methodologies.

And finally, check out this short, 40 minute YouTube tutorial that covers coding for cybersecurity. It covers cybersecurity projects and stresses the importance of python in cybersecurity. You can skip the first half of the tutorial if you wish because it covers the fundamentals of cybersecurity which you have already covered.

Finally, we have reached the end of our cybersecurity unit. Once again, I hope the resources I have provided you with are helpful enough for you to begin your high school cybersecurity experience, and hopefully help you discover whether cybersecurity is a topic worth pursuing in college.


## Web Development/Design ##
## Software/App Development ##
## Real-World Application ##
## Conclusion ##




















