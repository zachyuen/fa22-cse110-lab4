1. Line 12 will print 3 because var provides its variable with function scope so the variable i can be accessed on line 12 since it's inside the function and i is 3 since line 12 comes after the for loop above it which iterates i from 0 to 3.
2. Line 13 will print 150 because var provides discountedPrice with function scope and line 13 is inside the function so it can access discountedPrice which is 150 since the last time the loop updates the variable occurs when i = 2 so discountedPrices = prices[2] * (1 - 0.5) = 300 * (0.5) = 150.
3. 
