# ARM-Single-Cycle-CPU

Implemented in Logisim: http://www.cburch.com/logisim/

For the following piece of code:

	AREA PROJECT, CODE  
LOOP	 		       
	 SUBS R6, R0, #4        
	 BEQ FINISH           
	 LDR R1, [R5]           
	 ADD R1, R1, #8        
	 STR R1, [R5]         
	 ADD R5, R5, #4       
	 ADD R0, R0, #1       
	 B LOOP               
FINISH                
stop B stop           
	END            
  

