     Ex no. :
   Date    :
                                 STUDENT GRADE ANALYSIS


AIM : 
        To draw flowchart and write algorithm for the following problem.

ALGORITHM:
         Step 1 : start
           Step 2 : Get the marks m1 , m2 ,m3
           Step 3 : Calculate total 
           Step 4 : Calculate average
           Step 5 : Check for condition avg.>=30 and avg <50
                  5.1: If condition is True display the message “ Your grade is C “
           Step 6 : Check for condition avg>50 and avg<80
                  6.1 : If condition is True display the message “ Your grade is B”
          Step 7 : Check for the condition avg>80 and avg<=100
                 7.1 : If condition is True display the message “ Your grade is A”
            Step 8 : Check for condition avg <30
                  8.1 : If condition is True display the message “ Your grade is D”
           Step 9 : Stop.
             
 
FLOWCHART:

 
     RESULT :
               Thus the algorithm and flowchart is written for the given problem.
Ex no. :
Date    :
                WEIGHT OF THE STEEL ROD

AIM :
        To draw flowchart and write algorithm for the following problem .

ALGORITHM :
       Step 1 : Start
         Step 2 : Get the number of steel rods required as n
         Step 3 : Initialize I = 0 and total = 0
         Step 4 : Check if the value of I is less than n
               4.1 : If the condition is true , get the diameter of the rod D
             4.1.1 : Calculate unit weight using formula D**2/162
             4.1.2 : Get number of rods with diameter D
             4.1.3 : Calculate weight of rod using formula No. of rod *D* unit weight
             4.1.4 : Add this weight to total
             4.1.5 : Increment value of I by 1
                4.2 : If condition is false , Display total as total weight of rod
          Step 5 : Stop. 
FLOWCHART :

 
RESULT :
          Thus the algorithm and flowchart is written for the given problem.
EX NO. :
DATE    :
           CALCULATE ELECTRIC CURRENT IS 3 PHASE AC CIRCUTE


AIM :
       To draw flowchart and write algorithm for the following.

ALGORITHM :
      Step 1 : start
        Step 2 : Read the value of pf , I and V
        Step 3 : Calculate P using the formula P = root of 3 * pf * I*V
        Step 4 : Display “ the result is P “
        Step 5 : Stop . 










FLOWCHART :




 
RESULT :
       Thus the algorithm and flowchart is written for the given problem.
 

EX NO. :
DATE    :

                                 RETAIL SHOP BILLING

AIM : 
        To draw flowchart and write algorithm for the following . 

ALGORITHM :
        Step 1 : Start 
         Step 2 : Read the value bill number and bill date 
         Step 3 : Get details of customers : Name , address and mobile 
         Step 4 : Get the number of items purchased as n
         Step 5 : Initialize i = 0 , total = 0
         Step 6 : Check condition i<=n :
              6.1 : If true get items details like Name , price , count and discount
           i) calculate subtotal = count * price – Disc./100
          ii) Add the value of subtotal to the total
         iii) Increment the value of I by 1
           6.2 : If condition is false , get the value of GST
           i) calculate total Bill = total + GST / 100
          ii) Display Total_Bill
      Step 7 : Stop
FLOWCHART :
 
RESULT :
       Thus the algorithm and flowchart is written for the given problem.
 
EX NO. :
DATE    :

                                              SINE SERIES
AIM :
         To draw flowchart and write algorithm for the following .

ALGORITHM :
Step 1 : Start 
Step 2 : Get the value of X
Step 3 : Initialize the value of i = 1 , sine = 0 and import math
Step 4 : Get the value of N
Step 5 : Check the value of i is less than N :
5.1 : If the condition is T ,  convert x to radian and adding it to y.
5.1.1 : Let the value of S be -1 to the power i
5.1.2 : Now calculate sine series using formula
Sine = sine + [y*2*i+1] / math. Factorial ( 2*i+1)*s
5.1.3 : Increment value of i by 1
5.2 : If condition is false , display sine
Step 6 : Stop.
 
FLOWCHART :
 

RESULT :
          Thus the algorithm and flowchart is written for the given problem.


EX NO. :
DATE    :

                             WEIGHT OF MOTOR BIKE

AIM : 
        To draw flowchart and write algorithm for the following problem . 

ALGORITHM :
   Step 1 : start 
   Step 2 : Get the gross vehicle weight rating of the particular vehicle in a variable “ GVWR “
   Step 3 : Get the dry weight in a variable “ DW “
   Step 4 : Get the fuel weight in a variable “ FW “
   Step 5 : Get the rider weight in a variable “ RW “
   Step 6 : Get the passenger weight in a variable “ PW “
   Step 7 : calculate the total weight of the variable by adding DW , FW , RW AND PW.
   Step 8 : Get the load weight in a variable load 
   Step 9 : calculate the load weight of the vehicle by adding the total weight with the load .
   Step 10 : Now calculate the safe weight for the ride by subtracting the total vehicle weight from the GVWR.
   Step 11 : Check the condition if the safe weight is greater than or equal to zero.
   11.1 : If the message is true , the display the message “ You are appreciated for safe and happy journey “ .
   11.2 : If the condition is false then ask the rider to reduce  the load by generating the message “ For safe journey reduce the weight for better suspension “ .
   Step 12 : Stop.



















FLOWCHART :
 

RESULT :
        Thus the algorithm and flowchart is written for the given problem.

       
EX NO. :
DATE   :

                                     ELECTRIC BILLING

AIM : 
        To draw flowchart and write algorithm for the following problem .

ALGORITHM :
   Step 1 : start 
   Step 2 : Get number of unit consumed as N
   Step 3 : check condition if n<=100
     3.1 : if the condition is true , display no. current charge else go to step 4
   Step 4 : check condition is n<=200
      4.1 : if the condition is true , for 100 units no charge and to calculate energy charge for remaining units use formula 1.5*(N-100)
      4.2 : The total charge is calculated by adding energy charge , duty charge and fixed charge
     4.3 : Display current bill
   Step 5 : Check condition if n <= 500
     5.1 : If condition is true , for 100 units no charge 
     5.2 : For units 101 to 500 energy charge is calculated in step 2
      5.2.1: for 101 – 200 units , energy charge 1 = 100*2 = 200
      5.2.2: for remaining units calculate energy charge 2 for remaining units will be (N – 200)*3
     5.3 : Total energy charge is calculated by adding 5.2.1 and 5.2.1
     5.4 : The total charge is calculated by adding energy charge , duty charge and fixed charge
     5.5 : Display current bill for the month in step 5.4.
Step 6 : check condition if n >500
      6.1 : If condition is true , for 100 units no charge
      6.2 : For units 101 , energy charge is calculate in 3 steps
      6.2.1 : for 101 – 200 units energy charge 1 = 100*3 , 5=350
      6.2.2 : for 201 – 500 units energy charge 1 = 300*4 , 6
      6.2.3 : For remaining units calculate energy charge 2 for remaining units will be (N-500)*6,6
        6.3 : Total energy charge is calculated by adding 6.2.1 , 6.2.2 , 6.2.3
       6.4 : The total charge is calculated by adding energy charge , duty charge and fixed charge .
       6.5 : Display current bill for the month in step 4.
Step 7 : Stop.
 
FLOWCHART :
 

RESULT :
            Thus the algorithm and flowchart is written for the given problem.    



