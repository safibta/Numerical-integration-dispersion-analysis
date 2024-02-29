THe program considers the composite form of a numerical integration method for solving differential equations and constructs its linear multistep form.

A set of tasks is performed concerning the dispersion analysis of the numerical method in a 1D context. Dispersion analysis is used to assess how well a numerical method replicates the propagation of waves compared to the exact solution.

1. **Obtaining Linear Multistep Form**:  
   First, the linear multistep form of the method is obtained. This form is used to calculate future states in a numerical simulation using several previous states.

2. **Plotting Dispersion Curves**:  
   Next, dispersion curves have been plotted. These curves show how the numerical wave speed differs from the true wave speed against a normalized wave number. This helps in visualizing the accuracy of the numerical method for wave propagation.

3. **Calculating Normalized Wave Numbers**:  
   Then, certain values of the normalized wave number for given ratios of time step to wave period (\( \Delta t / T \)) and for different Courant-Friedrichs-Lewy (CFL) numbers are calculated under a specified condition for \( \beta \) parameters.

4. **Optimizing CFL Values**:  
   Finally, CFL values that optimize the numerical method performance for various \( \beta_1 \) values have been obtained. The optimal values ensure that the dispersion (difference between numerical and exact wave propagation) is minimized.
