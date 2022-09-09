# EXPERIMENT--01-ALP-FOR-8086
Name : S Dhanush Praboo
Roll no : 212221230019
Date of experiment : 9/9/2022

## Addition  of 8 bit ALP 
~~~
name "ADDITION"
org 200h
MOV AX,05H;
MOV BX,02H;
ADD AX,BX;
MOV CX,AX;
MOV AX,00H;
HLT;
~~~
## Output  
![image](1.png)
![image](2.png)
![image](3.png)
![image](4.png)
![image](5.png)
![image](6.png)
![image](7.png)
![image](8.png)

## Subtraction   of 8 bit numbers  ALP 
~~~
name "SUBTRACTION"
org 200h
MOV AX,06H;
MOV BX,04H;
SUB AX,BX;
MOV CX,AX;
MOV AH,00H;
HLT;
~~~

## Output  
![image](9.png)
![image](10.png)
![image](11.png)
![image](12.png)
![image](13.png)
![image](14.png)
![image](15.png)
![image](16.png)
## Multiplication alp 
~~~
name "MULTIPLICATION"
org 200h
MOV AL,02H;
MOV BL,03H;
MUL BL;
MOV CL,AL;
MOV AL,00H;
HLT;
~~~
 ## Output  
 ![image](17.png)
 ![image](18.png)
 ![image](19.png)
 ![image](20.png)
 ![image](21.png)
 ![image](22.png)
 ![image](23.png)
 ![image](24.png)


## Division alp 

~~~
name "DIVIDION"
org 100h
MOV AL,20H;
MOV BL,10H;
DIV BL;
MOV CL,AL;
MOV AL,00H;
HLT;
~~~
## Output  
 ![image](25.png)
  ![image](26.png)
  ![image](27.png)
   ![image](28.png)
   ![image](29.png)
   ![image](30.png)
    ![image](31.png)
     ![image](32.png)


## Result :
ALP on fundamental arithmetic and logical operations for 8086 is written and executed.







