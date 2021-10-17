1) Outputs 3, which is the end of the for loop, and what i is, which stops the for loop because of as less than prices.length which is 3.
2) Outputs 150, which is the variable that takes in prices[2] and multiplies 300 by (1-0.5) which is a half = 150.
3) Similar to 2, finalPrice just takes in discountedPrice and rounds it to a whole number if necessary. Giving 150. Since it is the last number to have computation on from the end of the for loop.
4) The function will return the discounted variable which is an array, after the for loop completes computations on whatever was input to it. There is not visible output since there is no console.log
5) There will be no output because i is not a variable that is accessible outside of the for loop, if the output.log was inside the forloop it would be able to output something, but since it is not, it cannot.
6) Like 5), since the discountedPrice variable is being called out of the scope with its declaration of let, it will throw an error because console.log cannot access that variable. 
7) finalPrice will output the last iteration of the for loop which will be 150, just fine because they are within the same scope.
8) This function will return the input array that was computed through the for loop properly. As [50,100,150]
9) Throws an error, will not be able to output i, as it's a let declaration which means only within the scope can it be output. 
10) Will output the length of the array that was put into the function. Works because length is not attempted to be changed after it is assigned the length of the input array which has a size of 3.
11) returns the array filled with the computations of the array that's input. 
12) 
- A) student.name
- B) student.major[1]
- C) student.greeting[0]
- D) student.greeting[1].name
- E) student.courseLoad[0]

## Arithmetic 
13) 
- A) 32, appends 2, to the char
- B) 1, thinks of 3 as a number due to the minus operator
- C) 3, add null is essentially nothing
- D) 3null, appends the word null to 3 char
- E) 4, true is treated as 1, and arithmetic of adding 3.
- F) 0, false is treated as 0, null has no value. 
- G) 3undefined, appends undefined as a word to the char 3. 
- H) NaN, can't remove any value with undefined keyword, so 3 is not treated as number. 

## Comparison
14) 
- A) true, treats 2 as a number, and compares to 1.
- B) false, stays false until true, and comparison between two strings, not numbers.
- C) true, '2' is treated as a number from the string and compares 
- D) false, '2' is not the same type as 2
- E) false, 2 does not equal true. 
- F) true, they are the same types and boolean(2) is not 0 which is false. 
15) == checks if values are the same and === checks if they are the same type incl. value (no conversion).

## Loops
16) file

## Functions
17) The result is [2,4,6] because the function takes in an array and callback is the function doSomething, the modifyArray takes in the array and uses a forloop to push in new computated values using doSomething into the const of newArr. 

## setInterval(), setTimeout(), clearTimeout()
18) file

19) 
- 1
- 4
- 3
- 2