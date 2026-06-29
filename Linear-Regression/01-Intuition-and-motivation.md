Motivation for linearity 

they always assume the relationship bw input and output is linear
single neuron uses logistic regression in ANN
slope = y2-y1/x2-x1

slope intercept form: y = mx+b
ax + by + c = 0 --> standard form of line

when dot product is 0 and (a,b) not equals (0,0) then two vectors must be perpendicular

HYPERPLANE

A hyperplane is a decision boundary whose dimension is one less than the dimension of the surrounding space. In two dimensions it is a line, and in three dimensions it is a plane. Its equation is typically written as w⋅x=b, and it divides the space into two half-spaces. In machine learning, points on one side of the hyperplane are assigned to one class and points on the other side are assigned to another class, making the hyperplane the fundamental decision boundary used by many classifiers. 

For classification, we use it to answer:
"Which side of the boundary does this point belong to?"

If data has:
n dimensionsn
then the hyperplane has:
n−1 dimensionsn-1 

w⋅x=b 

The hyperplane divides space into two regions.
Side 1
w⋅x<b
Side 2
w⋅x≥b

DISTANCE BW HYPERPLANE AND A POINT

https://chatgpt.com/s/t_6a3ca7ff12988191afb52b0be717eb21


SUMMARY OF WHOLE THINGS: https://chatgpt.com/s/t_6a3cae13d644819186de8901026a8325


Intuition

<img width="960" height="607" alt="image" src="https://github.com/user-attachments/assets/f54d6421-c08e-4ee7-acc9-a3091a108b93" />


Instead of just trying to get many points close to the line, linear regression fits a line by minimizing the total distance of all points from the line simultaneously

it minimizes the vertical distance (parallel to the y-axis) between the points and the line. 

Entire LR & MSE Intiuition

https://chatgpt.com/s/t_6a3cb2becf6c819180441fca5f9d41e8

h(x) - y ~~ 0 

Predicted output=intercept+slope×x 

θ₀ (intercept)
Moves the whole line up or down.
θ₁ (slope)
Changes the tilt.
generally represented by m

So learning means:
Finding the best θ₀ and θ₁

COST FUNCTION

A cost function is a mathematical function that measures how wrong a model's predictions are compared to the actual values. In linear regression, it is usually the Mean Squared Error (MSE), which calculates the average of the squared differences between predicted and actual outputs. The cost function is used because the model needs a numerical way to judge its performance—smaller cost means better predictions. During training, the model repeatedly adjusts its parameters (theta_0) and (theta_1)) to reduce the cost, typically using gradient descent. As the cost decreases, the prediction errors become smaller, resulting in a line that fits the training data more accurately and generalizes better to unseen data.

OUR GOAL IS MINIMIZING COST FUNCTION


