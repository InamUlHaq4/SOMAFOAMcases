This is 7c_4processors case copy (i.e. case name: sinusoidal_7c_TryParallel4ProcessorsTest_endTime150MicroSec_ProfAdvisedParameters_20thNov). 

This case is being ran using 2 cores only, rest of everything is kept same as before i.e. as in reference case.

THe aims are to:

1. Check if the simulation completes any further than 76 micro sec as in the previous case ?
2. Check if the simulation produces any different are same profile ?

So basically it is repeatability as well as stability test simlation ?

18th Dec 2023: Only 16.3 μs are simulated (approx 3 days i.e. simulating approx 5+ μs per day) 
19th Dec 2023: Only 22.2 μs are simulated (approx 4 days i.e. simulating approx 5+ μs per day)

3rd Jan, 2024: It was after 5 holidays. Simulation was already complete to endTime of 150 microSec. When did the simulation completed exactly, no idea ?

Since steady state was not achieved yet, attempt was made to rerun the simulation from the latestTime in paralle, however the simulation immediately crashed with "floating point exception errors".
