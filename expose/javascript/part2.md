1. Line 13 prints number 3 because i is accessible inside the function scope as it is defined as "var". The final value of i is equal to the prices.length, which is 3.
2. Line 13 prints number 150 because discountPrice is accessible inside the funticon scope as it is defined as "var". The final value of discountPrice=price[2]*(1-0.5)=300*0.5=150
3. Line 13 prints number 150 because finalPrice is accessible inside the function scope as it is defined as "var". The final value of finalPrice=Math.round(discountPrice*100)/100=Math.round(150*100)/100=150.
4. The function returns [50, 100, 150]. These numbers are the processed prices [100, 200, 300] after the discount 0f 0.5. 
5. An error occurs because i is defined in "let", so i is only accessible inside the for loop. Since line 13 is outline the for loop, so i is no longer accessible there. An error occurs.
6. An error occurs because discountedPrice is defined in "let", so discountedPrice is only accessible inside the for loop. Since line 13 is outline the for loop, so discountedPrice is no longer accessible there. An error occurs.
7. Line 14 will print 150 because the last finalPrice =Math.round(300*100)/100=150. As the finalPrice is defined in the function scope, so it is accessible on line 14, which is within the function.
8. The function will return an array of discounted price [50, 100, 150] since it discounted every final price after the discount for every price in prices in the for loop.
9. There will be an error because i is not defined in the function scope. i is defined as "let" inside the for loop, so it is not accessible outside the for loop/
10. Line 12 will print 3. As "length" is defined as "const" inside the function, it is accessible everywhere inside the function. Therefore, it is accessible on line 12. "length" counts the number of elements on prices, so it is 3.
11. The function will return an array of discounted price [50, 100, 150] since it discounted every final price after the discount for every price in prices in the for loop.
12. a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. A. '3'+2='32' since integers map to their exact string representation
    B. '3'-2=1 since '3' is converted into integer when meeting the substraction with number 2
    C. 3+null=3 since in the addition, null becomes 0
    D. '3'+null='3null' since null maps to their string representation
    E. true + 3 = 4 since true equals 1 in addition calculation
    F. false + null =0 since both false and null equals 0 in addition calculation
    G. '3' + undefined = '3undefined' since undefined maps to their string representation
    H. '3' - undefined = NaN since undefined converts to NaN in numeric context, and any arithmetic with NaN results in NaN。
14. A. '2'>1 =true because '2' is converted into 2   before comparison
    B. '2' < '12'= false because character '1' is smaller than '2'
    C. 2=='2'=true because '2' is converted into 2 before comparsion
    D. 2 === '2' =false because in absolute comparison, the type difference leads to false
    E. true == 2 =false because true=1
    F. true === Boolean(2)=true because Boolean(2) is evaluated to true
15. The difference between == and === operators is that == is non-strict check which allows type conversion before checking, but === is strict check which not allows type conversion before checking

17. The result will be [2, 4, 6]. When we call the modifyArray function, we go through the every element of the input array [1, 2, 3]. Then, we pass each value into the doSomething function, which is stored in the callback parameter. The doubled value is returned and then pushed into the returned array. 
 