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
A) '32' because 3 is a char and + means to concactanate. Therefore we 
B) 1
C) 3 because null maps to 0 and 3 + 0 = 3
D) '3null' 
E) 4 because true maps to 1 and 1 + 3 = 4.
F) 0 because false maps to 0 and null maps to 0 so 0 + 0 = 0.
G) 3undefined 
H) NaN 