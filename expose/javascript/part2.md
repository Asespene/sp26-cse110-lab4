1. At Line 12, a 3 is printed since var i is function scoped and it increments until it equals price.length which is a 3 and then the loop terminates.
2. 150 is printed at Line 13 since var discountedPrice is function scoped and it retains the value from the final iteration of the loop (300 * .5)
3. At Line 14, 150 is printed since the var finalPrice is function scoped so it retains the value from the final iteration.
4. The function returns [50, 100, 150] since the loop successfully calculates the half-price of each item in the input array and pushes them to the discounted array.
5. A ReferenceError is returned at Line 12 since let i is block-scoped to the for loop and is inaccessible outside of it.
6. ReferenceError is returned at Line 13 because let discountPrice is a block-scoped to the for loop.
7. ReferenceError is returned at Line 14 since let finalPrice is block-scoped to the for loop.\
8. The function just returns [50, 100, 150] since the discounted array is successfully populated, and the return statement is in the same scope as the discounted array initialzation.
9. At Line 11, ReferenceError is returned since let i is block-scoped to the for loop.
10. 3 is printed at Line 12 since the const length is defined in the same block scope as the console.log statement.
11. [50, 100, 150] is returned from the function. Although discounted is declared as a const, pushing elements into the array is not affected since it's not the same as reassigning the variable itself.
12. A. student.name, B. student['Grad Year'], C. student.greeting(), D. student['Favorite Teacher'].name, E. student.courseLoad[0]
13. A. '32', B. 1, C. 3, D. '3null', E. 4, F. 0, G. '3undefined', H. NaN, 
14. A. true, B. false, C. true, D. false, E. false, F. true
15. The == operator actually allows type conversion before comparing values. On the other hand the === operator performs strict comparison checking that both values and data types are exactly identical.
17. The following result will be [2, 4, 6]. The modifyArray function loops through the input array [1, 2, 3] and then passes each element to the callback function doSomething. The callback would then multiply each number by 2 and then return it which is then pushed to newArr.
19. 1, 4, 3, 2. The sychronous console.log statement executes first (1,4). Then the setTimeout with 0ms delay executes (3). Finally the setTimeout with 1000ms delay (2). 