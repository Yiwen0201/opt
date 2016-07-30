# opt

This is to solve a quadratic programming problem. The code comtains a linear solver, a stepsize search routine, and a related norm calculator. It brings out several newton steps for each initial guess, and uses the solution from previous steps as initial guess for next newton iterations. And the loop ends when the norm of difference between initial guess and solution is less than the tolerance.
