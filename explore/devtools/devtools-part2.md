# Answers to Explore - DevTools - Debugging
Q1) The bug was the data type of the input as num1 and num2 were stored as strings in the explore.js file so when we did the + operation the strings would get concatenated.
Q2) To fix this bug, I type cast num1 and num2 using Number() and then typecasted it again in the calculateSum function to ensure num1 and num2 were numbers. 