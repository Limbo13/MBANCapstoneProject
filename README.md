# MBANCapstoneProject
This is the ML portion of my capstone project for the Iowa State University MBAN degree

For the ML part of this project, we trying to predict whether a Kickstarter project will be successful, and how much money we expect the project to earn. We tackle both of these questions before and after the launch of the project. This results in four different possible types of predictions. The end user is provided with a tool (utilizing the tkinter package) where they can input certain values depending on whether they are trying to perform a prediction pre or post launch.

This project consists of several files (not all of which are uploaded/complete as of right now):

-PrepareDataset: This file takes multiple csv files and converts them into one file with the attributes we are interested in. The raw files were taken from https://webrobots.io/kickstarter-datasets/

-TrainModels: This file reads in the dataset and creates models based off of the predictions we are trying to make. There are 156 combinations of primary and sub-categories; the TrainModels program uses these combinations to filter the original dataset so only records that belong to that combination are then used for training a model. As a result, 624 different models are produced.

-Prediction tool (still in production): Utilizing tkinter, the user will be provided with a GUI interface where they can input values for the variables we believe to be important for making the most accurate predictions possible. 


Not included in this repository:

-Original dataset

-Model files produced
