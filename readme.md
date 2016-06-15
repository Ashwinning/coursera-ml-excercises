# Notes

## From [ex1.pdf](https://github.com/Ashwinning/coursera-ml-excercises/blob/master/machine-learning-ex1/ex1.pdf)

### *2.2.3 Computing the cost J(θ)*

We need to calculate `J(θ)`

So the cost function looks like

![](https://i.gyazo.com/bd98376654f54d768873d0530fe35a16.png)

where the hypothesis is

![](https://i.gyazo.com/89d473a15cdebc60ca158cb80ca44cab.png)

So the code should look something like :

`J = 1 / (2*m) * sum((X * theta - y).^2);`
