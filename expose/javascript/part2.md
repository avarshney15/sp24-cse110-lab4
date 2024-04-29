# Answers to Part 2
Q1) Line 12 returns "3", because i is a "var" so it is preserved outside the block. The variable , i, has been used a loop counter to loop through the prices list. 
Q2) Line 13 returns "150" because it returns the value of the last time discountedPrice was set in the for loop and since  discountedPrice was a "var" it can still be called outside the for loop
Q3) Line 14 returns "150" because it returns the value of the last time FinalPrice was set in the for loop and since  FinalPrice was a "var" it can still be called outside the for loop
Q4)*the code prints nothing* This function prints nothing as it ran normally and there were no commands which would print a value to the console

Q5) When I run this code I get "ReferenceError: i is not defined" as i has been defined as a let variable thus it can only be accessed inside the for loop block in which it is called. 
Q6) When I run this code I get "ReferenceError: discountedPrice is not defined" as discountedPrice has been defined as a let variable thus it can only be accessed inside the for loop block in which it is called. 
Q7) The code prints 150 because finalPrice was declared as a let variable outside of the for loop in the function block, so it can still be accessed after the for loop. 
Q8) *the code prints nothing* This function prints nothing as it ran normally and there were no commands which would print a value to the console

Q9) When I run this code I get "ReferenceError: i is not defined" as i has been defined as a let variable thus it can only be accessed inside the for loop block in which it is called. 
Q10) When I run this code it returns 3, as the length variable is assigned as a const variable in the beginning of the function so it can be called inside of the function. 
Q11) *the code prints nothing* This function prints nothing as it ran normally and there were no commands which would print a value to the console

Q12) A) student.name
     B) student['Grad Year']
     C) student.greeting()
     D) student['Favorite Teacher'].name
     E) student.courseload[0]

Q13) A) '32' since integers map to their exact string representation
     B) 1 since the string '3' is converted to an integer 3 and then 2 is subtracted from 3
     C) 3 since null is interpreted as 0 and 3+0 = 3
     D) '3null' since javascript converts null to 'null' as '3' is a string and then performs string concatenation to get '3null'
     E) 4 since true maps to 1, so 1+3=4
     F) 0 since false maps to 0 and null maps to 0
     G) '3undefined' as undefined is converted to a string as '3' is a string and then string concatenation is performed to get '3null'
     H) NaN as javascript tries to convert both operands to numbers however, undefined is a special character in javascript and cannot be converted into a number, giving us NaN instead

Q14) A) true as '2' is a string which can be converted to an integer, 2, and then 2 can be compared with 1
     B) false as javascript performs lexicographical comparisions between the two strings and only compares the first character in each string based on its unicode value, and '2' comes after '1' in the unicode character set so the expression returns false
     C) true as == is an equality operator that checks equality with type conversion therefore '2' is converted to 2 and then the operands are checked for equality
     D) false as === is an equality operator that checks equality without type conversion therefore '2' is compared with 2 and they are different therefore we get false as our output 
     E) false as == is an equality operator that checks equality with type conversion therefore true is mapped to 1 and then the operands are checked for equality
     F) true as boolean(2) will be mapped to true as any non-zero number is converted to true by Boolean(), and true is equal to true

Q15) "==" is an equality operator that can convert the type of both of the operands to ensure that they are the same type before comparing the two whereas "===" is a strict equality operator and does not perform any type conversion. "===" checks if both operands are the same including their types. 

Q16) refer to the javascript file

Q17) The modifyArray function creates a new array and then uses a for loop to give each number of the original array to doSomething which doubles the number and returns it. Then each number gets added to the new array and that gets returned. 

Q18) refer to the javascript file

Q19) 1
     4
     3
     2


