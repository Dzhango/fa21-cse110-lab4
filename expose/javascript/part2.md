1. 3, var is function scoped, and gets updated in the for-loop
2. 150, discountedPrice is function scoped, and get's halved for every value in prices array.
3. 150, finalPrice does not change after it gets rounded.
4. returns an array of discounted prices [50, 100, 150]. Push method adds the elements to the end of the array.
5. error, let i is block scoped.
6. error, let discountedPrice is block scoped.
7. 150, finalPrice is in the same scope.
8. returns an array of discounted prices [50, 100, 150]. Discounted is in the same scope.
9. error, i is block scoped.
10. 3, length is in the same scope
11. [50, 100, 150], array of discounted prices. discountedPrice gets redeclared for every iteration, so it doesn't create an error.
12. 
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]
13. 
A. 32, number maps to its string representation
B. ‘3’ - 2 = 1, 3 gets converted to number
C. 3 + null = 3, null is 0
D. ‘3’ + null = 3null, null is converted to string
E. 4, true is converted to 1
F. 0, false is converted to 0
G. 3undefined, converted to string
H. NaN, minus operator does not recgonize a number so it returns NaN
14.  
A. true, string is converted to number
B. false, (alphabetically) 1 is less than 2.
C. true, string coverted to number
D. false, different types
E. false, true is converted to 1.
F. true, boolean(2) is true because >0
15. == converts to the same type before checking, === only returns true if the values are the same type
16. attached
17. modifyArray function would return [2, 4, 6]. The callback is passed as a parameter, therefore we can use it withing the modifyArray function, pushing doubled elements into new array.
18. attached
19. 1,4, undefined, 3,2.