1. It prints 3. As the variable i is declared using var, it is accesible outside the for loop. As the for loop ends after i reaches the length of price, which is 3, it maintains the value 3 until line 12.
2. It will print 150. As discountPrice is declared using var, it is accesible outside the loop. The last value that is assigned to it is a price of the 300 getting 50% discount, which equals 150.
3. It prints 150 as well. The last assignment on final price inside the loop was the rounded number of discount price divide by and multiplied by 100, which equals the discountedPrice value.
4. The array of discounted prices will be returned, which is [50,100,150]. Each price 100,200,300 will get 50% discout and rounded up, which will have an integer value of half the value.
5. It will cause an error saying the variable is not defined. The variable i is declared using let, thus it only survives in side the for loop
6.  It will cause an error saying the variable is not defined. The variable discountPrice is declared using let, thus it only survives in side the for loop
7.  It will print 150. As finalPrice is defined in the same scope as console.log, we can access its value. The last assignment was the discount value of 300, thus 150 is the output.
8.  It will return [50,100,150]. The variable discounted is accesible as it is defined in the same scope. It contains the discounted value of original price by mutliplying 0.5 and rounding it up to the integer. And it pushes each value inside the array, in order so the value is [50,100,150]
9.  It causes error saying i is not defined. As i is declared using let, it survives only in the for loop.
10. It prints out 3. The length is assigned in the same scope as the console.log, and it contains the number of elements in the array price, thus it has value 3.
11. It will return [50,100,150]. The variable discounted is accesible as it is defined in the same scope. It contains the discounted value of original price by mutliplying 0.5 and rounding it up to the integer. And it pushes each value inside the array, in order so the value is [50,100,150]
12.  a. student.name

b. student['Grad Year'] 
 
c. student.greeting()

d. student['Favorite Teacher'].name

e. student.courseLoad[0]

13.  A. '3'+2 = '32' as integer + string makes the two concatenate.
    
B. '3' - 2 = 1, as - converts string to number for subtraction

C. 3 + null = 3 as null is treated 0 for mathematical operation
 
D. '3' + null = '3null' as + concatentates the converted version of null. 

E. true + 3 = 4 as true is considered 1 in mathematical operation 

F. false + null = 0 as false equals 0 and null equals 0.

G. '3' + undefined = '3undefined' as + concatenates '3' with undefined converted to string 

H. '3' - undefined = NaN as - can only to the mathematical operation, and any mathematical operation with undefined equals NaN

14.   A. '2' > 1 = true. When we compare string with integer, string is converted to the integer, and as 2>1 is true, outcome is true.\\ B. '2' < '12' = false When both is string, we compare alphabetical order. As '2' has bigger value of first alphabet, '2' < '12' is false.\\ C. 2 == '2' equals true. When we compare string with int, we convert stirng to integer and compare\\ D. 2==='2' equals false, as it compares the value and the type.\\ E. true == 2 equals false. When comparing boolean with integer, the boolean value converts to 1 when true, and 0 when false. Here, 1 does not equal 2.\\ F. true === boolean(2) equals true. Here boolean of 2 equals true, thus value and type both equals to each other.\\
15.   == compares the value of both sides, while === compares value and the type.
18.  The outcome will be [2,4,6]. the name of the dosomthing function is passed to variable callback, and it is called to multiply each element in array [1,2,3] and pushes it into new array.
19.  The outcome is 1 4 3 2. This is because 3 waits till the non setTimeout operations are finished, and 2 waits 1 second after the 3 is executed.