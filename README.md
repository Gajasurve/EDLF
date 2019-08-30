# EDLF
Find Most Repeated Instruction and loop conditions 

This uses DynamicRIO , an dynamic instrumentation toolkit very similar to Intel Pin , to generate the data. Printed Address are to be fed in python script to construct output which can be pasted directly in IDA batch Command windows (Shift + f2)

Run as : C:\dynamorio\bin32>drrun.exe -c C:\Users\Administrator\Desktop\findLoop.dll -- C:\Users\Administrator\Desktop\Malware.exe
