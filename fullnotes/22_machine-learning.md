# Machine Learning

## What is Machine Learning?

Machine learning is a branch of artificial intelligence that focuses on the creation of algorithms and models that enable computers to learn and make predictions without being explicitly programmed.

Machine learning is a subset branch of AI that focuses on creating algorithms and models to enable computers to learn and make predictions without being explicitly programmed. This is the reverse of traditional programming where you will have to code these methods and the process in which your system is able to make a decision.

In machine learning, you give data to an algorithm such that the system can learn how to make predictions without being explicitly programmed. Algorithms are created to learn from data and get better over time.

## Artificial Intelligence (AI)

AI is the development of computer systems or computers that can carry out tasks that traditionally require human intelligence.

### Examples of AI Systems:

- **Vision Systems**: The ability to develop a system that can see and identify objects (cats, dogs, cars)
- **Text-to-Speech Systems**: Systems that can convert text to speech and vice versa
- **Robotics Systems**: Systems or robots that can walk around and avoid obstacles, mimicking human capacity

## Examples of Machine Learning Solutions

### Classification Tasks
- Weather prediction models that can predict if it will rain tomorrow
- Regression tasks that predict temperature for tomorrow

### Core Components of Machine Learning Systems

Examples of AI solutions include:
- Vision systems that can see cats, dogs, and other objects
- Text and speech processing capabilities
- Robotics systems involving robots moving around and avoiding obstacles

## Data Requirements for Machine Learning

Machine learning needs data to function properly. In order for the machine to learn, you will need data.

Machine learning algorithms need data to help them fine-tune their parameters. Parameters in the model are fine-tuned such that those parameters enable the system to make predictions.

### Types of Data:

#### Structured Data
- Data from spreadsheets or Excel sheets
- Data organized in rows and columns
- Data that can be easily picked and selected

#### Unstructured Data
- Text from online resources
- Photos and images
- Data from sensors (IoT devices)
- Data for monitoring vitals and health metrics

### Data Quality and Quantity

The performance of machine learning models can be strongly impacted by the quality and quantity of data. You need to ensure your data is of high quality and sufficient quantity.

- **Quality**: If you have low-quality data with missing information, your model will not make good predictions
- **Quantity**: Instead of using 50 rows to train your model optimally, you might need 1000 or 2000 rows for better performance

For example, each row might contain a person's name, age, work experience, and loan-related data to predict if a person will be granted a loan or not. You need sufficient data for your model to make predictions accurately.

## Machine Learning Algorithms

The goal of algorithms is to discover patterns. You give your data to that algorithm, then your algorithm goes through the training process to learn patterns. This is the objective of your algorithm.

When you give your dataset to the algorithm, it uses that data to train itself. The parameters within the algorithm are updated and fine-tuned so that the algorithm can make accurate predictions.

## Types of Machine Learning Models

There are three main types of machine learning algorithms:

### 1. Supervised Learning

Supervised learning means you have data and you have labels. In this case, a typical example would be:

**Example: Student Admission Prediction**
- You want to create a classifier to predict if a candidate will pass admission to a computing course
- You look at exam scores (JAMB scores like 220, 100, 300)
- You also look at ICT scores at different levels
- You examine previous records of students who passed or failed
- The system trains based on this labeled data

**Training Process:**
- You pass your dataset and corresponding labels to the system
- The algorithm learns from the data and labels
- After training, the system can predict on datasets never seen before
- You evaluate the system on new data to test accuracy

**Evaluation Example:**
If you test the system with 4 cases and it correctly predicts 3 out of 4, the accuracy would be 75% (3/4 × 100).

### 2. Unsupervised Learning

This type of machine learning model doesn't go through the typical training process. It performs classification automatically without explicit training.

**Example: E-commerce Recommendation System**
- The system creates age brackets (10-20, 21-30, etc.)
- It identifies items bought by people within each age bracket
- When a 19-year-old buys a PS5, the system knows they belong to the 10-20 age bracket
- The system can then automatically recommend items or products purchased by others in that age bracket

This classification happens without traditional training - it classifies based on patterns and similarities.

### 3. Reinforcement Learning

This learns by trial and error and could involve an agent or robot in an environment.

**Example: Table Tennis Learning**
- A robot doesn't know how to play table tennis initially
- The system or agent learns from the environment how to play table tennis
- It takes actions and gets rewarded or penalized
- When it hits the ball correctly, it gets rewarded
- When it misses, it gets penalized
- Gradually it begins to improve and get more rewards
- This is like training with a reward system

You see this in games as well - an agent or player enters an environment knowing nothing about it, gradually begins to learn how to play, and improves over time through rewards and penalties.

## Training Process

The training process entails providing the algorithm with input data to create output, allowing the system to modify its internal parameters in response to given examples. The outputs might be labels too, so you give it data and labels so that it learns.

You have your data, you give it labels, and it uses that to update its parameters and internal parameters such that at the end it can predict on datasets never seen before. That's the supervised training you go through.

The system is also evaluated on datasets never seen before after the training is implemented, so you have your accuracy metrics for evaluation.

## Evaluation and Deployment

### Evaluation Phase
Once you're done with training, you give the system a dataset for evaluation. For example:
- Person X with JAMB score 260 and ICT exam score 60 over 100
- Person Y with scores 180, 45 in ICTY
- Person A with scores 220 and 50

The system should output predictions like "pass," "fail," "pass," "pass." You compare these with actual outcomes to calculate accuracy.

### Deployment Phase
Once you're satisfied with the evaluation phase, you can deploy. You can either:
- Deploy in the cloud
- Deploy in the client's environment

**Deployment Platforms:**
- Microsoft Azure
- Google Cloud Platform
- Amazon Web Services

## Real-World Applications

### E-commerce Integration
In a typical deployment scenario, you would have software (like an e-commerce application) with a machine learning model integrated in the backend. The unsupervised model recommends products based on items you picked earlier.

For example, if you buy toothpaste, it begins to recommend a toothbrush because the machine learning model makes that recommendation.

### Educational Institution Application
You could have software for a prospective student who gains admission into your institution. You want to find out if this person would pass or fail their introduction to computing course.

The system collects exam results, puts in the ICTY score, and passes it to the machine learning model. The model then comes up with an output signal predicting whether the student will pass or fail. If the prediction is failure, you might recommend preparatory courses before the main introduction course.
