# differential-equations
The differential equation of motion for a planet around the Sun, assuming purely circular orbit, has the following form:


$$\frac{d^2 \vec{r}}{dt^2} = - G\frac{M}{r^2} \vec{u_r}$$


Let's define the gravitational constant and the mass of the Sun.

## Abstract
In this assignment, I have solved the differential equation of motion for a planet around the Sun, assuming purely circular orbit using two numerical methods, Euler's method and Runge-Kutta's method. The initial conditions for the position and velocity of the planet Mercury have been defined, and the trajectory of the planet has been plotted for 180 days and 1 year for both methods. Furthermore, the relative error has been calculated for both methods and compared to determine the accuracy of the numerical solutions.

## Introduction
The motion of a planet around the Sun can be described by a differential equation that relates the acceleration of the planet to the gravitational force exerted by the Sun. The objective is to determine the accuracy of the numerical solutions and compare the results obtained from the two methods. I chose the planet Mercury as an example and defined the initial conditions for its position and velocity. The trajectory of the planet was plotted for 180 days and 1 year for both methods, and the relative error was calculated to determine the accuracy of the numerical solutions.

## Methods
First I separate differential equations for x and y. Then I define euler function and rk4 function, which were bases on the Euler's and Runge-Kutta's methods.

![image](https://github.com/leilaakisheva/differential-equations/assets/128895782/f1cbd7e6-883d-4547-863c-2145c1540030)

![image](https://github.com/leilaakisheva/differential-equations/assets/128895782/9e1bd6ed-b33a-4b57-b308-d43dbcbb7bb5)

## Results
It can be seen that as the number of iterations increases the Euler's method is less accurate and the relative error increases. This can be also seen in the plot: the calculated trajectory of the Mercury using Euler method has a very big deviation.

## Conclusion
In conclusion, the ODE was successfully solved using Euler's method and Runge-Kutta's method. The accuracy of the numerical solutions was determined by calculating the relative error, and it was found that Runge-Kutta's method produced more accurate results.
