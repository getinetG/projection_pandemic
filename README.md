# projection_pandemic
How fast is an epidemic expanded?
# SIR Model for Spread of Disease
 Epidemics can be modeled mathematically in order to study the severity and prevention mechanism. This model (SIR) is used in epidemiology to compute the number of susceptible (S), infected (I), and recovered (R) people
in a population at any time. 

###  $$ S --> I --> R$$
The underlying assumption is that a person who recovered from the disease develops immunity. Please read the follwing link for further detail about this model. 
https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology
## The governing differential equation
The simple SIR model has the following system of nonlinear ordinary differential equations.
$\frac{dS}{dt} = -bS(t)I(t)$
$$\frac{dI}{dt} = bS(t)I(t) - kI(t)$$
$$\frac{dR}{dt} = kI(t)$$
Where b is the number of contact and k is the recovery time.
The nonlinearity of the above equations makes it hard to find the explicity analytical solution.
<img src="https://latex.codecogs.com/svg.latex?\Large&space;x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" title="\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" />
