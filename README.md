# 4-bit-flash-ADC-Design


-	4 Bit Flash ADC is designed using a resistor ladder in parallel with each other connecting to the comparator. 
- To receive the output, the priority encoder is designed.
- Comparator : 
        The hysteresis of 10-20 mV is achieved by providing internal positive feedback.
        Delay of comparator measured is less than 12ns.
- The propagation delay achieved is less than 30ns for overall system.
- Gain error and offset error measured is 0.05mV and 17.25mV respectively. 
- Power consumption is below 150µW. The design was analyzed for different Monte Carlo corners.
- Maximum DNL observed is 0.056 LSB and INL is -0.041 LSB
- Area estimation : 180 µm×100 µm

#### Software Used: Cadence Virtuoso
#### Time Frame: Mar 2019
#### Course : Mixed Signal IC Design ( EE726 )
