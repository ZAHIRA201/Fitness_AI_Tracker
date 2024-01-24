# Hi GYM Buddies and all the network out there!!
## Driven Reasons of WHY ?
Under the driving factors for this project, As a Gym & Fitness passionate, I was compelled by the lack of attention to strength training programs in current literature and the inadequate support from existing activity trackers. Particularly striking was the prevalent emphasis on tracking blood, heart, or respiratory activities, highlighting a gap that our project aims to address.
So, This project aims to create Python scripts to process, visualize, and model sensory data from accelerometers and gyroscopes.
## Ultimate Objective
The ultimate goal is to develop a machine learning model capable of classifying exercises(five types, look the figure bellow) in the gym and counting repetitions of each one.
## Book Inspiration
I was inspired by this incredible book -The Quantified Self-
https://link.springer.com/book/10.1007/978-3-319-66308-1
## Gym Exercices that have been cooked
![Screenshot 2024-01-24 012648](https://github.com/ZAHIRA201/GYM_AI_Tracker/assets/120922044/7c8239fe-c753-410b-9035-c3731f8de25d)
## Project Workflow
![Workflow_ML](https://github.com/ZAHIRA201/GYM_AI_Tracker/assets/120922044/f76e3e44-b76b-495c-80d7-f4dc1a77d5a3)
## Road Map of the project repo
### first look with the dataset :
/data/raw/data/data
### rearranging the raw data: 
/src/data/make_dataset.ipynb
### Data Visualisation: 
\src\visualization\visualize.ipynb
### Outliers Detection: 
\src\features\remove_outliers.ipynb
### Feature Engineering(LowPassFilter&Fourier Transformation&ACP&Clustering): 
\src\features\build_features.ipynb
### Trainig modeles: 
\src\models\train_model.ipynb
### Counting Repetions: 
\src\models\count_repetitions.ipynb
