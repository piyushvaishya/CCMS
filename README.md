# CCMS
A solution to  EESL challenge Centralised Control &amp; Monitoring System(CCMS).
A repo that is the solution to the challenge by EESL.
Here are the two challenges:

CHALLENGE 1–

HOW TO DETECT/IDENTIFY THE DEFECTIVE/NON-FUNCTIONAL
LIGHTS, NUMBER OF LIGHTS CONNECTED TO A PARTICULAR CCMS
THAT ARE NOT FUNCTIONING AND THE WATTAGE OF THESE FAULTY
LIGHTS.
EXTRAPOLATE THE DATA AVAILABLE IN THE CCMS TO FIND OUT THE
NON – FUNCTIONAL STREET LIGHT(S) CONNECTED TO A PARTICULAR
CCMS.

CHALLENGE 2 –

COMPLAINT HANDLING SYSTEM (CHS) – THE PRESENT CONSUMER
COMPLAINT DATA TO BE ANALYSED FOR PREDICTIVE ANALYSIS OF
THE FAULTS AND UNDERSTANDING SO THAT EESL COULD TAKE PRE-
EMPTIVE MEASURES AND ADDRESS THE COMPLAINTS BEFORE THEY
EVEN OCCUR.(SUGGEST WAYS TO REDUCE FAULT RATE.)

SOLUTION 1 -
First of all  we have to create the fault at each instance of transmission line and collect the sample data for all the cases.
After that we have extracted  post fault data and create the  input file and according to  the input file we have to assign the  target value and feed both file to the ANN(Artificial Neural Network).

Solution 2 -
We have CHS data we grouped the complaint data according to the address and also according to complaint type. 
This will give us insight about the cause of fault in particular area as well as more frequent flaut prone area.
