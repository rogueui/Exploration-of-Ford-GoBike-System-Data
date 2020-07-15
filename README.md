# Exploration of Ford GoBike System Data

## Project details
This project is divided into two major parts. In the first part, you will conduct an  **exploratory**  data analysis on a dataset of your choosing. You will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships.

In the second part, I have my main findings from your exploration and convey them to others through an  **explanatory**  analysis. To this end, I have created a slide deck that shows the explanatory visualizations to communicate your results.

## About Dataset

Dataset Options

[Ford GoBike System Data](https://s3.amazonaws.com/baywheels-data/202003-baywheels-tripdata.csv.zip)

* Either You can download from the link or just run the program (i.e exploration_template.ipynb).
* Click the [link](https://s3.amazonaws.com/baywheels-data/index.html) to download dataset of other month/year.

## Exploration of Data

Exploring the data and document the findings in a report and the report is briefly introduce the dataset, then systematically walk through the points of exploration that I have conducted. In thhis project I have used a lot of Visualizations and appropriate plot types and encodings so that accurate conclusions can be drawn, and comments and labeling are a lot so that you can quickly grasp your analysis from any step.

I have used Jupyter Notebook for this step of the project.

File Name: exploration_template.ipynb.

## Document My Story

At the end of your exploration,I have discovered a bunch of things. Now it’s time to organize my findings and select a story that will convey a message.

File Name: slide_deck_template.ipynb.

## Slide Deck

Creating a Slide Deck is one of the important aspects of explanatory analysis as it conveys a message between the Finding and Visualization through a Story.

**Note: Please ensure that ouput_toggle.tpl file is in the same directory.**

Following steps are used for Creation of Slide Deck:

* Open the Anaconda Prompt or Command Prompt.
* Change Directory to the project folder (i.e cd "folder name").
* Type: jupyter nbconvert file_name.ipynb --to slides --post serve --template output_toggle
