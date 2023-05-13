# Observational-Fairness-and-the-COMPAS-dataset
ECE324 Miniproject

Project instructions were created by Professor Michael Guerzhoy. 

The aim of this mini-project is to replicate and expand upon the results from two scientific papers analyzing the COMPAS dataset. This involves creating and training models, computing quantities such as false-positive rates, and presenting your results and analysis.

## Part 1
In this part, my partner built a logistic regression model to predict two-year recidivism. The model's calibration and false-positive parity was be evaluated, and adjustments have been made to achieve a balance between these properties.

## Part 2
Part 2 focuses on training a difficult-to-train system using insights from the [Deep Learning Training Playbook](https://github.com/google-research/tuning_playbook). I have implemented a machine learning architecture in Adel et al.'s study: [“One-network adversarial fairness”](https://ojs.aaai.org/index.php/AAAI/article/download/4085/3963) and tested it using the COMPAS dataset. Here, I have chosen to implement three strategies from the playbook to optimize the model and explained my choice in the Jupyter Notebook file. 
