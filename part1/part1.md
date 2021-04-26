Part 1A:
<hr>
1. values added: 20

2. final result: 20

3. values added: 20

4. the code returns an error because result is declared in the "if" block, so using let when in the if block it only exists in that block. When prining the final result, it gives an error because its outside of the scope.

5. the code returns an error because result was declared as a const, and constants can't be reassigned.

6. the code returns an error because result is declared in the "if" block and it doesn't exist outside of the "if" block.

<br>

Part 1B:
<hr>
1. 3 gets printed out because in the loop, i loops 3 times.

2. 150 gets printed out because the last value in the price 300, so 300*(1-0.5) = 150.

3. 150 gets printed out because discountedPrice is 150 and doing the math of finalPrice, it would be (150*100)/100, which is just 150 after being rounded.

4. This function just returns an array of numbers. It does this because it uses the discount value from the value parameter to show the numbers with diiscoutned prices in the array.

5. An error occurs because i is not defined in the block but declared in the for loop.
6. An error occurs because discountedPrice is declared in the loop and is not in the block because it is created using "let" in the for loop.

7. 150 is printed becaue finalPrice is created and is in the scope for the entire discountedPrices function. finalPrice is the (discountedPrice * 100)/100 and it is viewable in the block.

8. This function just returns an array of numbers. It does this because it uses the discount value from the value parameter to show the numbers with diiscoutned prices in the array. 

9.  An error orrcues because i is not defined in the block but declared in the for loop.

10. 3 gets printed because the length of price is passed into the array. It is able to be seen in the scope as well because it was declared 
in the entire discountedPrices function.

11. This function just returns an array of numbers. It does this because it uses the discount value from the value parameter to show the numbers with diiscoutned prices in the array.

12: 
    ```
    A. student.name

    B. student['Grad Year']

    C. student.greeting()

    D. student['Favorite Teacher'].name

    E. student.courseLoad[0] ```

13.
    ``` 
    A. '3' + 2 would print 32 because since 3 is a string, it would concatenate 2 to 3.
    
    B. '3' - 2 would print 1 because even if 3 is a string, the subtraction sign would change it to be a int, recognizing this as a math function to be 3-2 = 1.
    
    C. 3 + null would print 3 beacuse the "+" sign would make it a math function, so since 3 is an int, and null would then be 0, so 3+0 is 3.
    
    D. '3' + null would print 3null because here '3' is a string, so similar to A, it would concatenate null to 3.
    
    E. true + 3 would print 4 because the "+" sign would recognize it as a math function and true has the value of one, so 3+1 = 4.
    
    F. false + null would print 0 because the "+" sign would recognize it as a math function and false and null have the value of 0, so 0+0 = 0.
    
    G. '3' + undefined would print 3undefined because '3' would be recognized as a string, and the + sign would concatenate undefined to 3 to have it print 3undefined.
    
    H. '3' - undefined would print out NaN because the "-" would make this line be a math function, so 3 - undefined would be NaN because 3-NaN = NaN. ```

14:
  ```
    A. '2' > 1 would print true because > is a comparison, so 2 > 1.
   
    B. '2' < '12' would print false because it is comparing chars, so the 2 char is greater than 12.
   
    C. 2 == '2' would print true because '2' is converted to be 2
   
    D. 2 === '2' would print false because '2' and 2 are different types. == checks conversions and === doesn't, so since it didnt check conversion it wouldn't be true.
    
    E. true == 2 would print false because true's value is 1, so 1 wouldn't equal to 2.
    
    F true === Boolean(2) would print true because Boolean(2) is the same as true. ```

1.  The difference between == and === operators are that == checks for type conversion and === doesn't.

2.  coded in part1b-question16.

3.  The function returns an array with numbers that are double the value of the first array. modifyArray goes through the value of the original and sends it to doSomething so that doSomething can multiply it by two then return the new numbers into the array.

4.  coded in part1b-question18

5.  the ouput is:
    1
    4
    3
    2
    