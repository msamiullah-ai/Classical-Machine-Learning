<img width="948" height="580" alt="image" src="https://github.com/user-attachments/assets/1f7f83de-3d4d-47a5-b45f-958547304e36" />

<img width="905" height="624" alt="image" src="https://github.com/user-attachments/assets/5a9c7715-62e4-480e-bdd5-581aa6046901" />

<img width="918" height="756" alt="image" src="https://github.com/user-attachments/assets/ac243fef-85c2-4a70-9e6c-69588a0506ab" />

<img width="963" height="639" alt="image" src="https://github.com/user-attachments/assets/3ed952f8-9a28-4491-a5f8-2d5bec71561e" />

Gradient Descent

we can perform well without global minimum becz if we keep finding that we possibly end up overfitting on training data

derrivative --> rate of change means where ground is heading

Gradient Descent is an optimization algorithm used to minimize the cost function. It works by repeatedly adjusting the model parameters theta_0, theta_1  in the direction that causes the greatest decrease in cost. At each step, it calculates the gradient (slope) of the cost function and moves in the opposite direction of that slope because that is the direction of steepest descent. The size of each move is controlled by the learning rate α. By continuously taking these steps, gradient descent gradually reduces the cost function until it reaches (or gets very close to) the minimum cost, resulting in the best parameter values and the most accurate model predictions. 

Imagine standing somewhere on a hill in thick fog. You cannot see the bottom, but you can feel the slope beneath your feet. If the ground slopes downward to your left, you take a step left. After every step, you again check the slope and move in the steepest downhill direction. Repeating this process eventually brings you to the bottom of the valley. In Linear Regression, the hill is the cost function J(θ_0,θ_1) and the bottom of the valley is the minimum cost, which corresponds to the best-fitting line 


derrivative = inst slope

min k paas = chota qadam and vice versa

Problem of local optima - GD

Perform simultaneous updation of all parameters after calc perform GD iteration

