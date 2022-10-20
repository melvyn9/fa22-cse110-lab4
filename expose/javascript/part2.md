Q1) It will console log 3 because we are initializing i as a var and hence it will exist outside of the scope of the for loop since it has no block scope. Since the length of the prices array is 3, i starts at 0 and iterates 3 times and hence i is equal to 3.

Q2) It will console log 150 because we are initializing discountedPrice as a var. Although we are initializing it in the for loop, var has no block scope and hence will exist outside of the scope. It is given the values 50 on the first iteration, 100 on the second iteration and finally 150.

Q3) It will console log 150 because we are initializing finalPrice as a var and assigning it the value 0 at first. The price changes to 50 on the first iteration, 100 on the second iteration and 150 on the third iteration.

Q4) This function will return [50, 100, 150]. It returns this because each time we are calculating the new finalPrice, we are pushing it to the discounted array which will be returned at the end of the function. We also declared discounted as a var so it has no block scope.

Q5) There will be an error because i is declared using let that is inside the scope of the for loop. Since we want to console log it outside the for loop, it will cause an error.

Q6) There will be an error because discountedPrice is declared using let that is inside the scope of the for loop. Since we want to console log it outside the for loop, it will cause an error.

Q7) It will console log 150 because finalPrice is declared using let that is in the scope of the function. Since we are calling console log in the function, it will log the value of finalPrice since it exists in the scope of the function.

Q8) It will return [50, 100, 150] because discounted is declared using let and is in the scope of the function. We are also returning in the scope of the function hence there will be no error.

Q9) There will be an error, this is similar reasoning to Q5 because i is declared using let in the scope of the for loop and we are calling console log i outside of the for loop. Hence, i does not exist.

Q10) It will console log 3 because although we declared length as a constant, the value is never changed throughout the function call and therefore does not output an error.

Q11) It will return [50, 100, 150] because although discounted is declared as a constant, we are never changing what discounted is. We are only changing the contents inside of the array which is allowed since we are not changing discounted to be something else. Therefore, there will be no errors.

Q12) 
A) student.name;
B) student['Grad Year'];
C) student.greeting();
D) student['Favorite Teacher'].name;
E) student.courseLoad[0];

Q13)
A) '32' because JavaScript does not know how to add a string with a number. Therefore, it treats 2 as a string and concactanates '3' and '2' to get 32.
B) 1 because JavaScript does not know how to subtract an integer from a string, the string '3' is converted to an integer 3 and then performs a subtraction of 2 from it to obtain 1.
C) 3 because null maps to 0 and 3 + 0 = 3
D) '3null' because '3' is a string and since there is a +, it concactanates 3 with null to form '3null'.
E) 4 because true maps to 1 and 1 + 3 = 4.
F) 0 because false maps to 0 and null maps to 0 so 0 + 0 = 0.
G) 3undefined because '3' is a string and since there is a +, ut concactanates 3 with undefined to form '3undefined'.
H) NaN because JavaScript does not know how to subtract NaN from a string. Therefore, it converts '3' to an integer and tries to subtract NaN from it. However, this is not possible since NaN does not represent a real number and hence just returns NaN.

Q14)
A) true because the string '2' will be converted to an integer and 2 is more than 1.
B) false because JavaScript compares the first letters where 2 is more than 1. Therefore, it returns false.
C) true because '2' becomes an integer and 2 is equal to 2.
D) false because === checks if the types are the same. Since 2 is an integer and '2' is a string, it returns false.
E) false because true has the value of 1. Therefore 1 is not equal to 2.
F) true because Boolean(2) is true since any value more than 0 is true. Since === checks for type, true on the left side is boolean and Boolean(2) is true in boolean too. Therefore, they are equal.

Q15) The == operator is a regular equality check with type conversion. For example, 2 == '2' will be true because it will convert the string '2' into an integer and hence 2 is equal to 2. The === operator is a equality check without type conversion. For example, 3 === '3' will return false because it will not convert the type of the string '3' to an integer. It returns false because we are checking if an integer is the same as a string which is false.

Q17) The result is [2, 4, 6]. The for loop will iterate 3 times since that is the length of the array [1, 2, 3]. In the first iteration, the callback function is called on the first element in array which is 1. In the callback function, it multiplies 1 by 2 and returns 2. 2 is then pushed into newArr. In the second iteration, callback is called on the next elemetn which is 2, it multiplies it by 2 and then returns it. It is then pushed onto newArr. In the final iteration, the callback function is called on 3 and is then multiplied by 2 and returns 6. 6 is then pushed into newArr. The for loop is over and newArr is returned which has the contents of [2, 4, 6].

Q19) 1 4 3 2