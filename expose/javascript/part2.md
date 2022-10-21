1. 3 will be printed. Declaration of var can be asccessed anywhere inside the function. i will be increment 3 times until it equals to the length of prices and the for loop stop. So i will be . 
   
2. 150 will be printed out. Declaration of var can be asccessed anywhere inside the function. discountedPrice will be initialized 3 times until the for loop stop. So discountedPrice will be 0.5 multiplies the last price 300 in the Prices. 
   
3. 150 will be printed out. finalPrice will be updated 3 times until the for loop stop. So discountedPrice will be 0.5 multiplies the last price 300 in the Prices array. 
   
4. It will return [50, 100, 150]. At each iteration of the for loop, finalPrice will be added to the end of the discounted array which is initialized before the execution of the for loop. And finalPrice will be 50, 100, 150 for the 3 iterations. So the discounted array [50, 100, 150] will be returned.
   
5. There will be an error of i is not defined. Because i is initialized by let at the intialization of the for loop. It cannot be accessed outside the for loop.
   
6. There will be an error of discountedPrice is not defined. Because discountedPrice is initialized inside the for loop. It cannot be accessed outside the for loop.
   
7. 150 will be printed out. finalPrice will be updated 3 times until the for loop stop. So discountedPrice will be 0.5 multiplies the last price 300 in the Prices array. 
   
8. It will return [50, 100, 150]. At each iteration of the for loop, finalPrice will be added to the end of the discounted array which is initialized before the execution of the for loop. And finalPrice will be 50, 100, 150 for the 3 iterations. So the discounted array [50, 100, 150] will be returned.
   
9.  There will be an error of i is not defined. Because i is initialized by let at the intialization of the for loop. It cannot be accessed outside the for loop.
    
10. 3 will be printed out. const variable length stores length of the prices array which is 3.
    
11. It will return [50, 100, 150]. Even though discounted is declared as a constant variable of array. As long as we are not reassign it to other thing, it will be fine. So it means we are able to add elements to this array. At each iteration of the for loop, finalPrice will be added to the end of the discounted array which is initialized before the execution of the for loop. And finalPrice will be 50, 100, 150 for the 3 iterations. So the discounted array [50, 100, 150] will be returned.


12.  
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E.student.courseLoad[0]

13.   
    A. '32'
    B. 1
    C. 3
    D. '3null'
    E. 4
    F. 0
    G. '3undefined'
    H. NaN

14.  
    A. true
    B. false
    C. true
    D. false
    E. false
    F. true

15. == is regular equality check. It will typecasting operands of different types to numbers and then compare. === is strict equality check. It check without type casting.

17. [1,2,3] will be passed into modifyArray as array and doSomething function will be passed as callback. Inside the modifyArray function, newArr is initialized. Then we will go through the for loop 3 times, because for loop executes for i initiliazed to be 0 and will stop when i = array.length which is 3. For each iteration, array[i] will be passed in callback and the return value is pushed to the newArr. So when i = 0, 1, 2, the corresponding element of index i inside array [1,2,3] will be passed into doSomething. doSomething will return double the input value. So 2,4,6 will be returned and stored into the newArr. Finally the newArr[2,4,6] is returned. 

19. 1 will be printed out instantly. After a second, 1000 will be printed out because the setTimeout function will set a timer of 1000 miliseconds and the code console.log(2) will be executed after that. Then 3 will be printed out right after 2 is printed out because the timer is 0 miliseconds for this code. Then 4 will be printed out instantly after 3 is printed out.