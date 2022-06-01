# DSA-BOOTCAMP-JAVA

Static vs Dynamic Languages:

**Static Languages**
-> Perform Type Checking at compile time
-> Errors will show at compile time
-> Declare datatype before you use it
-> More Control

**Dynamic Language**
-> Perform type checking at runtime
-> Error might not show till program is run
-> No need to declare datatypes of variables
->Saves time in writing code but might give runtime error

**Memory Management**
->Stack Memory and Heap Memory
a = 10
a-- ref variable
10 -- object

a-- stored in stack
10-- stored in heap

a is pointing towards address of 10
**a=10**
![Screenshot (2)](https://user-images.githubusercontent.com/106425794/171350413-94915995-9e04-4e86-8800-b53ccb48978a.png)

![Screenshot (4)](https://user-images.githubusercontent.com/106425794/171351457-3080f479-180d-4384-87d0-8f7c3b48d37f.png)

-> **More than 1 reference variable can point to one object**
-> **If any one of these variables change the object original object will be changed and it is going to be changed for all**

**No Reference Variable to the object**
-> Object Hits Garbage collection

----------------------------------------------------------------------------**TASKS**--------------------------------------------------------------------------------------
Input a number and print whether its prime or not
We will not check for 1 because 1 is neither prime nor composite

Prime No Requirements : Ignore 1 and no itself and start checking for divisibility  from 2 until number-1th number

**Input: Counter=2 number=16**
**Output : Prime or Composite**
**Algorithm :**
1) Initialise counter and input number
2) Check if counter is less than number
    a) Y
    b) N
    If Yes: then goto step 3
    If No: Output : Prime
3) Check if number is divisible(number%counter==0) by counter
    a) Y
    b) N
  If Yes: then Output : {number} is composite 
4) If No then increment counter by 1 then goto and repeat process from step 2 untill counter is equal to number
5)  If counter is equal then Output : Prime
6) End 
----------------------------------------------------------------------------**FLOWCHART**------------------------------------------------------------------------------
![Screenshot (5)](https://user-images.githubusercontent.com/106425794/171360465-e8a047ec-6a45-4d04-a5ff-fed485062e07.png)
----------------------------------------------------------------------------**PSEUDOCODE**-----------------------------------------------------------------------------
1) Pseudocode for Prime no
Start
input num
c=2
while c < num:
     if(num%c)==0:
            output "Composite"
       c=c+1
end while
Output "Prime"
Exit
        
2) Pseudocode for Salary Greater than 10000 add bonus of 2k otherwise add bonus ok 1k
   start
   input salary
   if Salary > 10000:
        Salary=bonus+2000
        
   else:
        Salary=bonus+1000
  Output Salary
   end
 
 -------------------------------------**HOW JAVA CODE EXECUTES**-----------------------------
 ![Screenshot (6)](https://user-images.githubusercontent.com/106425794/171374166-3eb7526e-8ef6-4de1-bc12-6b5b0ecccfc9.png)
