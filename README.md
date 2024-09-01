# ECE2112-PA-2
- Robie Galang
- Septembeer 1, 2024
- PA #2 Submission
# Documentation
- Firstly, don't forget to import the NumPy library as the problems will require us to code with functions built within the NumPy library.
- For the first question, I find it fairly simple thanks to the functions that the NumPy provides.
- Setting up the equation was very easy thanks to the np.mean() and np.std() as I was able to directly get the mean and standard deviation of the array with these function.
- For the second question, I used the np.arange() function to generate an array filled with the integers from 1 to 100. Then I just reshaped it into a 10 x 10
- Determining the integers divisible by 3 is quite tricy for me. For that, I used something that is called 'Boolean Indexing'.
- I setup a logic using the modulo operator where integers that would be able to satisfy the cnditioon, are included into the final output array, otherwise excluded. I found out that numpy can easily select those elements with a value of True and exclude those with False in the final output array.
