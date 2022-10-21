1. print 3. Because var i is function scoped, so we can still access it after the for loop, and the
for loop ends at i=3.
2. print 150. Same as question 1
3. print 150. finalPrice store the last value assigned to it, which is 150.
4. it returns discounted which is an array of discounted prices [50, 100, 150], because this 
is what it suppose to do I guess?
5. error, because 'let' i is only accessible within the block of the for loop.
6. error, because line 13 is out of the block where discountedPrice is declared.
7. 150, because line 14 is still in the block where finalPrice is declared.
8. returns an array [ 50, 100, 150 ], becuase the return is still in the block 
where discounted is declared.
9. error, i only accessible within the block of the for loop.
10. 3 , line 12 within the block scope of length
11. returns a constant array [ 50, 100, 150 ], same as q4.
12. A. student.name;
    B. student["Grad Year"];
    C. student.greeting(); 
    D. student["Favorite Teacher"].name;
    E. student.courseLoad[0];
13. A. "32" , converted 2 to a string 
    B. 1    , converted 3 to a int
    C. 3    , converted null to 0
    D. "3null" , converted null to "null"
    E. 4 , converted true to 1
    F. 0 , converted both to 0
    G. "3undefine" , converted undefined to string
    H. NaN , can't convert to proper type, undefined behavior

14. A. true , '2' got converted to 2 and decided that 2>1 is true.
    B. false, both got converted to int and 2 is not < 12.
    C. true , '2' got converted to 2 and 2==2
    D. false, because === checks for data type, but they have different data types
    E. false, true = 1 not equal to 2
    D. true , Boolean(2) = true, they have same value and data type.

15. difference is == will do type conversion and then do the comparison,
    but === will check if both the value and data type matches.

16. checkout [part2-question16.js](part2-question16.js)
17. result is an array [2, 4, 6]. we passed in doSomthing as a callback function to modifyArray()
each iteration in the for loop will pass array[i] to doSomthing(), doSomthing will return this
number times 2, and pushed in to newArr. So the final result will be the double of the original array:
[1,2,3] -> [2,4,6]

18. checkout [part2-question18.js](part2-question18.js)
19. prints 1 4 3 2, because 1 and 4 has no delay, 3 have 0 delay, 2 has 1000 delay.
     