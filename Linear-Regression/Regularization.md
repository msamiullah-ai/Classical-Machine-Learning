<img width="881" height="542" alt="image" src="https://github.com/user-attachments/assets/91c555fe-5169-4a6f-8662-2bd798074e91" />

Large coefficients make the model very sensitive.
That sensitivity often leads to overfitting.

λθ_1^2​
where λ\lambdaλ (lambda) is the regularization parameter that controls how strong the penalty is.

+1000*θ_1^2​
does not directly reduce the prediction error. Instead, it charges the model a "complexity tax" for using large weights. During optimization, the model must decide whether reducing the prediction error is worth paying that tax. This trade-off discourages unnecessarily complex models, helping to prevent overfitting.

If the weights (θ) become very large, the regularization term becomes very large, which increases the cost function. Therefore, during optimization, the model is encouraged to keep the weights as small as possible without sacrificing too much prediction accuracy. 

HUM YA CHAHTE HAI COST FUNC MA WEIGHTS KI VALUE HIGH NA HO. TO IS SA BACHNE K LYE HIGH WEIGHTS K BADLE SAZA DAI GA. IN FORM OF MULTIPLYING BIG NUMBER WITH THAT WEIGHT TO INCRZ COST

Regularization is done to reduce loss on validation set of data

https://chatgpt.com/s/t_6a409e984af081919cf9addb084530f5

Ridge Regression 

Ridge Regression is ordinary linear regression plus a penalty on large weights. During training, the optimizer minimizes both the prediction error and the penalty, so it prefers a model that fits the data well without using unnecessarily large coefficients. 
https://chatgpt.com/s/t_6a40a3021b2c8191b30480784b216b67


Lasso Regression 

Makes them 0 instead of ~~ or making too small like ridge

https://chatgpt.com/s/t_6a40a357b904819188508360db751d11

DIFFERENCES BW RIDGE AND LASSO ⭐⭐⭐

https://chatgpt.com/s/t_6a40a3fad44c8191868d00f9cb60fe33
