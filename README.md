# HaasCMM
Python program takes digitized data from Haas CMM wireless probe and creates a report.

Haas machines are great CNC machining centers.  After machining a part, with tool vibration 
or tool wear, the part is never the EXACT dimension.  We engineers understand this an assign tolerances to the part.
So, after machining it is a standard practice to measure the part.  This always involves removing the part
and adding an extra step of manually measuring the part or using another machine, called a 
CMM (coordinate measuring machine) that does the measurement. 

The thought process on this program was ... what if we just had the Haas machine itself, 
after machining a step, have it grab the wireless probe from the tool changer and then 
go forward and take measurements and record them.  Thus, the QC measurement just becomes 
part of the machining process and is handled automatically thru the use of the tool changer
and the data file creation.

True, this procedure will not catch wear on the machine such as lead screw wear, but it does allow
for multiple un-attended measurements.  A few quick manual measurements on the parts or the machine
every so often to very that there is no machine wear makes this a pretty reliable process.

