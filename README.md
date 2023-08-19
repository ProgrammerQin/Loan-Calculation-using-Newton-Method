# Loan-Calculation-using-Newton-Method
Challenge 1: If the amount a is borrowed at an interest rate of r for n years, then the total amount
 to be repaid is given by
𝑋= 𝑎(1+𝑟)! (1)
Yearly payments of p each would reduce this amount by
𝑌 = 𝑝 [($%&)!($] (2)
&
The loan will be repaid when these two quantities (equations 1 and 2) are equal, i.e., when X-Y = 0. (Hint: This is the equation you are finding the roots of).
Now, for a loan of a = $100,000 and a yearly payment of p = $10,000, how long will it take to pay off the loan if the interest rate is 6 percent, i.e., r = 0.06?
You can use Newton’s method developed in the assignment for finding n. You should use an initial guess of n = 10 years. Define Newton’s method in the main program but use functions to determine the derivative and the function. For the purpose of this problem, we will treat n as a continuous variable (i.e., n can have fractional values). Use 1e-6 for convergence criterion.
Your program must print a table containing the values of n and the remaining amount, i.e, X-Y. The program must also let us know the number of years it will be needed to repay the loan.
