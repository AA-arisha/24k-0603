# 24k-0603
## PSEUDOCODE
**Q1. Find the maximum number in any of three variables.**/
START  
INPUT num1 , num2 , num3  
IF (num1 == num2 ) THEN  
   IF (num2 == num3) THEN  
     PRINT "All three numbers are equal"  
   else
    IF (num2 > num3)  
      PRINT "num2 and num1 are greatest"
    else 
      PRINT "num3 is greatest"
    ENDIF
  ENDIF  
else
   IF(num2 == num3) THEN
      IF(num2 > num1) THEN
         PRINT "num2 and num3 are greatest"
      else
         PRINT "num1 is greatest"
      ENDIF
else
   IF(num1 == num3) THEN
      IF (num1 > num2) THEN
         PRINT "num1 and num3 are greatest"
      else
         PRINT "num2 is greatest"
      ENDIF
else
   IF (num1 > num2) THEN
      IF (num1 > num3) THEN
         PRINT "num1 is greatest"
      else
         PRINT "num3 is greatest"
   else 
      IF (num2 > num3) THEN
         IF (num1 > num2) THEN
            PRINT "num1 is greatest"
         else 
            PRINT "num 2 is greatest"
      else
         PRINT "NUM3 IS greateat"
END
         
         
   
  
  
   
  


