good job!

to check if we are receiving an empty array, we can write this in the first line of any function expecting an array and the function will also be protected against null values:

if (!array || !array.length) return null;
