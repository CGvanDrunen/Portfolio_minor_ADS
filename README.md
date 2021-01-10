# Portfolio_minor_ADS
Name: Niels van Drunen
Student number: 18062814
## Index
1) Datacamp Courses
2) Research Project
3) Domain Knowledge
4) Predictive Models
5) Data Preperation
6) Data Visualisation
7) Data Collection 
8) Evaluation
9) Diagnostics of the Learning Process
10) Communication

### 1. Datacamp Courses
Below is a screenshot of the mandatory courses I had to follow for this
minor, as you can see almost all of them I completed after the due date
was met. I usually completed them in the week after the due date. This was
probably caused by delay I received in the first week of the minor, hence
the 1 week divergency. Obviously this is not the right way to deal with
delay, but due to the work pressure of the minor besides the Datacamp
courses it ended up being this way.
![Datacamp](Datacamp.PNG)
On the side I also did the first 2 chapters of the course Introduction to
Deep Learning with Pytorch, which is a course that was advised by one of
our teachers to help getting familiar with Neural Networks. 

![Datacamp_Extra](Datacamp_Extra.PNG)

### 2. Research Project
In this chapter the main goal and findings of the project I contributed to
will shortly be discussed. For the planning of the project however I would
like to refer to the chapter ‘Planning & Deadlines’ in Appendix I.
The problem the team has to solve is offered by the company Factory Zero,
delivered to us by the problem owner Salcedo Rahola Baldiri and resulted in
the following research question:

*What is a suitable machine learning model to predict energy use &
production of a “zero at the meter” residential house, one day in advance
with (if possible) hourly resolution?*

The team then went on to find literature (Appendix III) on the topic of
predicting residential energy consumption & production to find suitable
models to try out. The following models were implemented: MVLR (Multi Variate
Linear Regression), SVR (Support Vector Regression), LSTM (Long Short-Term
Memory) and MLP (Multi-Layer Perceptron).
The conclusion of the project is that out of the 4 models LSTM the best
predictions makes for both energy production & consumption. More on the
exact performances of the models in chapter 4 Predictive Models. However
there are still a couple of things left to experiment with, for example
using a simple classification model to classify peaks in the consumption
data and then feeding the non-peak data and peak data to 2 separate models
to make a better prediction.
