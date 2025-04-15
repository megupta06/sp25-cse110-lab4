1. The line will print out value of i after the loop has finished executing. After the loop finishes, i will be equal to number of elements in prices array so it will print out 3.
2. It will print last value of discountedPrice from the loop that is 150. discountedPrice = 300*(1- 0.5)= 150.
3. It will print last value of finalPrice from the loop that is 150. finalPrice = Math.round(150*100)/100 = 150. As for the last i, discounted price is 150. So, finalPrice calculates to 150 for the last loop.
4. The function returns [50,100,150] as the function applies discount of 50% to each price in prices ans stores them in discounted.
5. It will give Reference Error because i is declared using let, which is a block scope and hence cannot be accessed outside the for loop.
6. It will give Reference Error because discountedPrice is declared using let, which is a block scope and hence cannot be accessed outside the for loop.
7. It will print last value of finalPrice from the loop that is 150. It happens because we can access finalPrice and it is not decalred using let like others.
8.  The function returns [50,100,150] as the function applies discount of 50% to each price in prices ans stores them in discounted.
9.  It will give Reference Error because i is declared using let, which is a block scope and hence cannot be accessed outside the for loop.
10.  It will output 3 because length is just length of prices and it is declared using const.
11.  The function returns [50,100,150] as the function applies discount of 50% to each price in prices ans stores them in discounted.
12.  A. student.name
    
     B. student["Grad Year"]
     
     C. student.greeting()
     
     D. student["Favorite Teacher"].name
     
     E. student.courseLoad[0]
     
13.  A. '32' because + operator with a string causes string concatenation.
    
     B. 1 because - operator uses numeric coercion.
     
     C. 3 because null maps to 0.
     
     D. '3null' because + operator with a string causes string concatenation.
     
     E. 4 because true maps to 1.
     
     F. 0 because false and null both map to 0.
     
     G. '3undefined' because + operator with a string causes string concatenation.
     
     H. NaN because - operator uses numeric coercion, '3' becomes 3 and undefined is not converted to number.
     
14.  A. true. '2' is coerced to the number 2, and 2 > 1 is true.
    
     B. false. This is a string comparison, and '2' is greater than '1' so false.
     
     C. true. The == operator performs type coercion, converting '2' to 2, so 2 == 2.
     
     D. false. === checks for strict equality, so it does not coerce types. 2 is not equal to '2' 
     
     E. false.  true maps to 1, so the comparison becomes 1 == 2, which is false.
     
     F. true. Boolean(2) returns true, and both sides are already booleans and equal, so the strict comparison is true.
     
15.  The == operator compares values after converting them to a common type, so it allows type coercion. The === operator compares both value and type without converting, making it stricter and more predictable.
    
17.  The result will be [2, 4, 6]. The modifyArray function loops through [1, 2, 3], applying the doSomething callback (which multiplies each number by 2). So, it returns a new array with doubled values: [2, 4, 6]
    
19.  Output:
     1
     
     4
     
     3
     
     2
    

