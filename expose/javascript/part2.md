1. It will print 3 because to exit the for loop i must be >= to prices.length which is 3. so by line 12 i=3 so thats what it will print
2. 150 will be printed because the last loop when discountedPrice is redefined it is set equal to half of prices[2] which is in fact 150.
3. 150 will be printed because the equation on line 8 does not make any significant changes to discountedPrice value (which is 150) when redefining finalPrice variable.
4. It will return the array [ 50, 100, 150 ] which contains each of the discounted Prices in the order they were calculated.
5. ERROR! because line 12 is out of the scope of i because i is declared let which has only a block scope
6. ERROR! for same reason as 5 but this time for discountedPrice's let declaration
7. 150 will be printed like question 3 because the block scope of let finalPrice does include line 14.
8. It will return the array [ 50, 100, 150 ] because discounted's block scope includes the return on line 19.
9. ERROR! for the same reason as question 5
10. 3 will be printed for the length of the array that is given.
11. It will return the array [ 50, 100, 150 ] the scopes of the variables do not affect the function's accuracy
12. -
    1.  A: student.name
    2.  B: student['Grad Year']
    3.  C: student.greeting()
    4.  D: student['Favorite Teacher'].name
    5.  E: student.courseLoad[0]
13. -
    1.  A: 32 because it add the 2 to the end of the '3' string
    2.  B: 1 it maps the 3 string to an int and performs subtraction
    3.  C: 3 because null is mapped to 0 and addition yield 3
    4.  D: 3null because null is mapped to the string 'null' and they are merged together
    5.  E: 4 because true maps to 1
    6.  F: 0 because both false and null map to 0
    7.  G: 3undefined because undefined maps to a string
    8.  H: NaN because string subtraction returns NaN.
14. -
    1.  A: true because '2' maps to 2
    2.  B: false because with two strings it sees if '2' is lexicographically smaller than '12'
    3.  C: true because type difference does not matter for ==
    4.  D: false because type difference does matter for ===
    5.  E: false because true maps to 1
    6.  F: true because Boolean(2) returns true because it is non-zero
15. type difference does not matter for == but for === it does
16. in part2-question16.js
17. The result is that the array is modified by multiplying each value by 2 and replacing it. I came to this conclusion because the for loop goes through each element in the array and runs the doSomething function that doubles it. The function call at the bottom returns [ 2, 4, 6 ]
18. in part2-question18.js
19. -
```
1
4
3
2
```