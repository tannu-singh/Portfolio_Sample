### Tannu Singh

### Contact

[LinkedIn](https://www.linkedin.com/in/tannu-singh/)        
[Github](https://github.com/tannu-singh/)
e-mail: singhtannu2@gmail.com  
Phone: (704)9046021
F1 - OPT, United States 



### Projects

#### Semeval2019 Emocontext


The task of this challenge was to classify a series of dialogues between human and robot into four sentiments: happy, angry, sad, others. We extented the model from the paper [DialogueRNN: An Attentive RNN for Emotion Detection in Conversations](https://arxiv.org/pdf/1811.00405.pdf). Using Bi-LSTM we suceesfully implemented the task of multiclass sentiment prediction.

#### [Hotel Recommendation System using Pyspark](https://webpages.uncc.edu/stiwari8/)


The project aims to provide recommendations of the hotels to a particular user based on the past history of his/her reviews and past data of other reviews.
The goal of the project is to implement collaborative filtering and content based filtering algorithm with the help of Pyspark to build a recommendation system.

![](https://github.com/tannu-singh/Hotel-Recommendation-System-/blob/master/Rating_Count.jpg)

#### Fundraising Forecast 

Developed a model to predict whether a donor will donate next month, next quarter, or next year. The dataset which I used was collected over last 13 years and I derived features from the dataset.

The features extracted from raw data were:

Average donation
Frequency of donation
Avg difference of donation
Time since first donation
Time since last donation
With these features I implemented keras model to predict whether a donor will donate next month, quarter, or year. This model gave the accuracy of 92.7% when the data was balanced.

#### SIR Model

The SIR models the flows of people between three states: susceptible (S), infected (I), and Recovered (R). Each of those variables represents the number of people in those groups. The parameters alpha and beta partially control how fast people move from being susceptible to infected (alpha), and from infected to resistant (beta).

The system dynamics model presented here includes different stocks and flows. There are three main stocks which has inflows and outflows. The model is generated by the use of SD library developed by professor Dimitris Papanikolaou.

![](https://github.com/tannu-singh/SIRmodel/blob/master/Model.png)

![](https://github.com/tannu-singh/SIRmodel/blob/master/Graph.png)



#### Radar Detection

In this project I have tried to implement a simple agent based model of radar and objects. For this project I have used simple 2D svg shapes as an objects. There are four objects (I named it as Pillars) and one robot which act as the radar object detector.
- When the robot moves around the area or box it is continously emitting radar signals.
- When any object comes in the way of radar signal and extreme end of the wall then the color of the signal changes to red from green.
- The surface area covered from the radar signal is displayed in the canvas window next to the simulation.

#### Calculator

Created a web app using Javascript which logs calculations as they happen and shares those calculations with everyone connected to the website. For example, user A and user B go to your site at the same time. User A calculates "5 + 5", which equals "10". This is logged below the calculator as "5 + 5 = 10". User B is updated about this calculation right after user A posts it. Now, user B calculates "3 x 4".This calculates to “12” and displays "3 x 4=12" right below the prior calculation. User A sees this update immediately after user B posts it.

The following test cases were covered during the development of calculator website app.

This calculator website app does the mathemactical calculation BODMAS.
A test case was developed to make sure that no two consecutive operators are added in an equation. I have added four major operators in this calculator (+, -, /, x)
A test case was also developed to ensure that in a real number there is only one point and not multiple points to represent a decimal number.
A test case was developed to make sure that an equation does not start from +, /, or x except -.
10 logs are shown.
Results remain the same even when the link is refreshed.

![](https://github.com/tannu-singh/Calculator/blob/master/Snapshot.png) 


