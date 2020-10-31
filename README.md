# starbucks_capstone

## Project Description
Starbucks Offer Dataset is one of the datasets that students can choose from to complete their capstone project for Udacity’s Data Science Nanodegree. The dataset contains simulated data that mimics customers' behavior after they received Starbucks offers. The data is collected via Starbucks rewards mobile apps and the offers were sent out once every few days to the users of the mobile app.

The goal of this project was not defined by Udacity. Thus, it is open-ended. I decided to investigate in the situation where customers used an offer without viewing it. I wanted to understand who are these customers and how we can avoid or minimize the chance of this from happening. 

## Project Result
The first part of the question was addressed by in-depth data engineering and EDA. It turns out that all customers are equally likely to use an offer without viewing it. The demographics do not make a difference. However, the design of the offer makes a big difference, especially its promotion channel and the length of the offer.

I built a machine learning model using logistic regression to address the second part of the question. I hope by building a model that can predict if a customers will waste an offer or not, we can be giving offers with awearness and considerations. The model achived a 71% accuracy. It can definitly be further imporved.

I wrote a blog post to walk through the step I took to achieve the result. The medium blog post can be accessed [here](https://linnndachen.medium.com/starbucks-offer-dataset-udacity-capstone-7b562843ff47).

## Tech Stack
- **Python3** is the main language.
- **Numpy**, **Pandas**, **matplotlib**, **seaborn**, and **sklearn** are the main packages that were used.
- **Jupyter Notebook** is where the code is hosted.

## Author and Acknowledgement

- Linda Chen is the only author of this project.

- Starbucks provided this dataset.

- [Udacity](https://www.udacity.com/) provided this Data Science Nanodegree Program and the access to this dataset.
