# Perceptron_trick
Perciptron Trick is a simple mathamtical way to implement perceptron through it does not always gurrenty that it will work properly.
The algorithm is like:
    for i in 1000:
        selsect any rendom data from dataset
        W(i)=W(i-1)+li*(yi-yi_hat)*Xi
    here,
    W(i)=new coefficient 
    W(i-1)=old coefficient
    yi=output value for that data point
    yi_hat=predicted value for that data point
    Xi=data point for that data
