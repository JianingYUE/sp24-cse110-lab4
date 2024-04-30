1. it will return the value of log 'i'. 'var' doesn't adhere to block scope, 'i' is scpoed to the entire function. 
so this mean after the 'for' loop, 'i' is still accessible, so it will return the value.

2. it will return the value of log 'discountedPrice'. same as question 1. even it was declared inside the 'for' loop,
but 'var' scoped to the entire function. so 'discountedPrice' will also accessible.

3. it will return the value of log 'finalPrice'. it was declared outside the loop and used 'var'. so it scoped the entire function.
after the loop. it will returnthe last update during the loop.

4. it will return a array of price after the discount. discounted will initializes an empty array and finalPrice set to 0.
in the loop, after calculate the discount, it will push the finalPrice to the discounted which is an empty array. so after 
calculate all the input price, it will return the array.

5. error. variable 'i' was declared by 'let' in the scope of 'for' loop. so outside the 'for' loop, 'i' is not accessible. because 'i'
was not defined as a globle variable.

6. error. same as last question. 'discountedPrice' was declared by 'let' in the scope of 'for' loop. this was used 
outside the 'for' loop.

7. it will return the value of log 'finalPrice'. this variable was declared by 'let', so the scope is entire function, it is still accessible
after the loop.

8. same as 4. it will return the array with the same reason as 4.
   
9. same as 5

10. 'length' was declared with 'const' and outside the 'for' loop. so the scope is entire function, it is accessible. so it will return the
value of log 'length'

11. return the same thing as 4. and same reason with 4.
    
(2)
A. student.name
B. student['Grand Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]

(3)
A. '32' '+' used for string concatenation, since '3' is a string, 2 will change to string and they will concatenated.
B.  1  '-' is not for string concatenation, since 2 is a number, '3' will change to number and do the calculate.
C.  3  null will converted to 0 since '3' is a number then do the calculate.
D. '3null' since '3' is a string, null will chang eto string then do string concatenation.
E.  4  true will change to 1 since 3 is a number, then do the calculate.
F.  0  both of them will change to 0.
G. '3undefined' since '3' is a string, undefined will also change to a string and do string concatenation.
H.  NaN undefined will change to NaN, any arithmetic operation with NaN will return a NaN.

(4)
A. true  '2' will change to number 2, 2 > 1 so it will return true.
B. false it will compire the length of string since both of them are string.
C. true '2' will change to number 2, so it will return true.
D. false '===' does not perform type coercion, since 2 is a number and '2' is string, different variable, so it will return false.
E. false true will change to 1, and 1 not equal to 2, so it will return false.
F.  2 is a truthy value, Boolean(2) will return true, true === true, same variable type, so it will retuen true.

(5)
== will perform type coercion but === doesn't, so == can compire different data type, === can only compire same data type.

