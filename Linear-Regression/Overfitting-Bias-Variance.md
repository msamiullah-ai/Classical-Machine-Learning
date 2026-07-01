<img width="937" height="594" alt="image" src="https://github.com/user-attachments/assets/9fdc95f5-6ff3-4be3-ba90-f73954e20e93" />

<img width="928" height="537" alt="image" src="https://github.com/user-attachments/assets/14897b53-0aff-42db-b882-851f7f01121f" />

<img width="888" height="629" alt="image" src="https://github.com/user-attachments/assets/65c58b65-0d3f-425e-bf80-dc9f100e6e9f" />


Underfitting is called high bais relationship. training data error is also too high. unable to fit training data well

Overfitting makes training data error close to 0 but too high on test data sampled from tr data (kabhi achi kabhi buri) -- High variance

When a model is underfitting, it fails to capture the underlying patterns in the data because it is too simple or rigid. As a result, it will give a consistently high error on both the training data and the test data 

What is bias?

The error caused by making overly simple assumptions about the relationship between input (X) and output (y).
Think of bias as the model's built-in belief about how the world works.

It refuses (or is incapable of) learning anything more complex.
That strong incorrect assumption is called high bias.

Linear Relationship often have huge bias

For example, trying to predict a complex, curved relationship (like a stock market trend or a person's height-to-weight ratio) using a simple straight line (Linear Regression) introduces bias. The model assumes the relationship must be linear, ignoring any non-linear truth 

What is variance? 

How much the model changes its learned function when the training data changes slightly.
A high-variance model is too sensitive to the training data.
Instead of learning the general pattern, it starts learning every tiny detail—including random noise.

What is overfitting?

"Overfitting is much more likely to happen when you have a small amount of training data." 

Overfitting happens when the model
is too complex
memorizes the training data
even memorizes random errors (noise)
performs extremely well on training data
performs poorly on new, unseen data

Real-life analogy

Suppose you're learning to recognize cats.
Training images
white cat
black cat
orange cat
A good learner notices
whiskers
ears
tail
eyes
A high-variance learner notices
"This cat had a red carpet."
"This cat stood near a blue wall."
"This cat had sunlight from the left."
These details are irrelevant, but the model memorizes them.
When shown a new cat in a different room, it fails.


NOISE
Noise is the random, unpredictable part of the data that is not explained by the true underlying relationship between the inputs and the output 


STOP the training when model's bais and variance is nicely balanced
Means when we get low error on both training and test data

In machine learning, you are balancing the Bias-Variance Tradeoff. 
Overfitting = Low Bias + High Variance
Underfitting = High Bias + Low Variance

Bias → Is the model too simple? Does it make overly strong assumptions?
Variance → Is the model too sensitive to changes in the training data?

Low variance simply means the model is stable. That stability can belong to either a good model or an underfitting model. 



