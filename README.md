# Individual-Project-1-DATA1202
Linear regression on wine quality dataset for DATA1200 assignment

## Project Title:
Wine Quality Linear Regression

A neat little project where I mess around with linear regression to predict wine quality from a bunch of chemical measurements. It’s cool seeing how data can guess something like that!

## Short Description:
This repo’s got my Python code for running linear regression on the red wine quality dataset. The data includes stuff like acidity, alcohol, and sugar levels, and I use it to predict a quality score (from 3 to 8). I originally did this in Colab for an assignment, but I’ve turned it into a single Python file here. It loads the data, splits it, trains a model, and checks how good it is—simple, but it works!

## Getting Started:
Here’s what you need to know to get this running on your own.

## Prerequisites:
You’ll need:

Python 3 (I used 3.10, but any recent version should be fine)
A few libraries: pandas, numpy, scikit-learn, and matplotlib (for the plots)
You can install those libraries using your usual Python package manager—just make sure they’re there before you run the script.

## Installing:
To set it up:

Grab this repo from GitHub (download it or clone it—up to you).
Pop into the folder with the files.
You’ll need the dataset too—it’s called winequality-red.csv from the UCI Machine Learning Repository. I didn’t include it here because of file size, but you can download it from their site (link’s in the Acknowledgement section) and drop it in the same folder as the Python script.

## Running the Tests:
I didn’t build fancy automated tests since it’s a basic project, but you can see how the model performs by running the script. It’ll:

Load the data and check it (no missing values, which is ace).
Split it into 80% for training and 20% for testing.
Train a linear regression model.
Give you the Mean Squared Error (MSE) and R-squared (R²) scores to show how well it did.
When I ran it, I got an MSE of about 0.39 (so predictions are off by around 0.6 points on average) and an R² of 0.403 (meaning 40% of the quality changes are explained by the model). Not too shabby for something simple!

## Breakdown of Tests:
MSE (0.39): This tells me the average squared difference between my predictions and the real scores. Square root it, and I’m off by about 0.6 points—like guessing a 6 when it’s really 5.4 or 6.6.
R² (0.403): This says 40% of what affects wine quality is captured by my model. The other 60% could be stuff like taste or smell that’s not in the data. Decent start for a basic go!

## Deployment:
No big deployment plan here—it’s just a script! You can run it on your computer with Python. It’ll print out the results and pop up two plots: a histogram of quality scores and a scatter plot of alcohol vs. quality. If you’re on a machine without a screen (like a server), you might need to tweak the plotting part or save the figures instead.

## Author:
Sai Prakash Lopelli (Student ID: 101001356)

Just a student having a crack at data analysis for DATA1200!

## License:
I haven’t slapped a formal license on this—feel free to use it for learning or messing around. Just don’t come yelling at me if your wine predictions flop!

## Acknowledgement:
Big props to the UCI Machine Learning Repository for the Wine Quality Dataset—I got the winequality-red.csv from there. Also, cheers to my DATA1200: Introduction to Data Analysis course for kicking this off!
