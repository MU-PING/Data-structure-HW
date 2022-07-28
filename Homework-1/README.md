# Homework-1
## Task 1
Please write a program to represent the input sparse matrix by using triplet form as mentioned in class. Then, transpose the matrix and print out the result as shown below. It should be noted that the input data will be integers. Therefore, you only need to check the input matix is consistent with the input size.(size fo input array will not bigger than 100x100. Use -1 as the end of input)

### Example:

![image](https://user-images.githubusercontent.com/93152909/181495694-b41a123e-bd93-45a8-9593-d5b1e582c044.png)

### Expected result
![image](https://user-images.githubusercontent.com/93152909/181497472-d75af1c0-cb50-4fb5-8871-30960cf9199a.png)

### Test data
(1) ---------------------------------------------------------------------
```
6 5
6 0 0 10 1 0
0 2 0 0 0
7 8 9 0 0
0 0 0 5 0
20 100 0 0 0
0 0 0 0 99
-1
6 0 0 10
0 2 0 0 0
7 8 9 0 0
0 0 0 5 0
20 100 0 0 0
0 0 0 0 99
-1
6 0 0 10 1
0 2 0 0 0
7 8 9 0 0
0 0 0 5 0
20 100 0 0 0
0 0 0 0 99
20 20 20 20 20
-1
6 0 0 10 1
0 2 0 0 0
7 8 9 0 0
0 0 0 5 0
20 100 0 0 0
0 0 0 0 99
-1
```

![image](https://user-images.githubusercontent.com/93152909/181517899-c50eae4a-9825-4696-b41d-439c77f1c12a.png)

(2) ---------------------------------------------------------------------
```
0 0
1 2 3
4 5 6
-1
-1
```
![image](https://user-images.githubusercontent.com/93152909/181518033-bea5ac19-98f4-481f-a126-c0212d555a19.png)

## Task 2
Please write a program to convert infix expressions to prefix expressions, and **calculate the values by prefix or postfix expressions**. All of the input data will be fully parenthesized infix expressions, integers are between 0 and 9, and all of the operators include “+”, “-”, “*”, “/”, “(”, and “)”. Your program has to read till the input row has only -1, and round the results to the nearest integer in the end. The program must be implemented by stack, or you will get zero points. [In our rule, -0.5≃-1]

### Example:

![image](https://user-images.githubusercontent.com/93152909/181497299-fb616d5c-43af-4d6d-8be9-005a769af892.png)

### Expected result
![image](https://user-images.githubusercontent.com/93152909/181497586-befb5e8a-67b8-45d0-967a-cac413a4a7d5.png)

> Note: In addition to the note stated above, you should add the functions: “toPreifx()”, “calPrefix()”.

### Test data
(1) ---------------------------------------------------------------------
```
((3*2)+(7/(5+3)))
((5+(((6/2)-3)*2))-(9/3))
((9-(2*3))-((1+8)*(9/5)))
(((2+6)/4)*2)
((((9/3)/2)*(4+5))-8)
((5*(6-3))/5)
-1
```
![image](https://user-images.githubusercontent.com/93152909/181520478-d97dfa93-7ee6-4976-ab3b-d98b8f273ab0.png)
