## assignment

## AIM

TO DESIGN AND STIMULATE THE LOGIC DIAGRAM USING VERILOG

## EQUIMENTS REQUIRED

HARDWARE-PCs,CYCLONE II,USB FLASHER
SOFTWARE-QUARTUS PRIME

##PROCEDURE

CREATE A PROJECT WITH REQUIRED ENTITIES
CREATE A MODULE WITH RESPECTIVE FILE NAME
RUN THE RESPECTIVE PROGRAMS 
RUN THE MODULE AND GET THE RESPECTIVE RTL OUTPUTS
CREATE UNIVERSITY PROGRAMS FOR GETTING TIMING DIAGRAM
GIVE THE INPUTS AND OBTAIN THE RESULTS

##THEORY

LOGIC GATES ARE THE BASIC BUILDING BLOCKS OF ANY DIGITAL SYSTEM.LOGIC GATES
ARE ELECTRONICS CIRCUIT HAVING ONE OR MORE THAN ONE INPUT AND ONLY ONE OUTPUT .
 THE RELATIONSHIP BETWEEN THE INPUT AND THE OUTPUT IS BASED ON A CERTAIN LOGIC 
 IN THIS LOGIC DIAGRAM NOR GATE AND NOT GATE IS USED
 
## PROGRAM

module exam(x,y,z,f,g);

input x,y,z;

output f,g;

wire a,b,c,d;

not (c,x);

not (d,y);

nor (a,x,y,z);

nor (b,c,d,z);

nor (g,a,b);

nor (f,g,g);

endmodule

##RTL DIAGRAM

![image](https://user-images.githubusercontent.com/123304969/215804898-388f0c7d-02e2-45bc-b17d-d9774ff162eb.png)


## TIMING DIAGRAM

![image](https://user-images.githubusercontent.com/123304969/215805107-b5133764-22df-4e2b-937c-a1c6fd7c8caa.png)

##RESULT
THUS THE LOGIC DIAGRAM IS DESIGNED AND STIMULATED USING VERILOG.
