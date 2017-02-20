# NLOS-and-LOS-data
 On 9th December 2016, at Wilab.t in Zwijnaarde where 15 UWB Pozyx devices are deployed (12 fixed anchors and 3 mounted on mobile robots), multiple ranging measurements were performed. The UWB radio settings were the following: 
 Channel 2 
 Bitrate 6.81 Mbps 
 Preamble length 128 symbols 
 PRF 16 MHz 

The experiment consisted of two main phases: 
1. Discovery To individuate the available anchors 
2. Ranging 100 ranging measurements with each available anchor 

This has then been repeated moving the robot in 11 different positions around the testbed facility. 
Final collected data include: 
 Timestamp 
 Measured Distance 
 LDE max value of noise 
 Amplitude at floor (index FP) + 1 
 Standard deviation of noise 
 Amplitude at floor (index FP) + 2 
 Amplitude at floor (index FP) + 3 
 Channel Impulse Response max growth CIR 
 Count of preamble symbols accumulated 
 LDE First path index (given in DWT_TIME_UNITS) 
 LDE Index of the maximum signal (given in DWT_CIR_TIME_UNITS) 
 LDE max value of the received signal 
 rx_dbm 
 estimated signal power in the first path 
 CIR complex coefficients 

Moreover, the real (x,y,z) coordinates of both anchors and tag and a table to verify whether LOS conditions are verified or not, are also provided. 
To access the data (available in Bitbucket) please email Matteo Ridolfi: matteo.ridolfi@intec.ugent.be 
