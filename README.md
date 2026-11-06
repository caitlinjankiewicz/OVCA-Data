# OVCA-Data
Data for my Masters of Research thesis project, mathematical modelling of oncolytic virotherapy in ovarian cancer. One sample run for each trial (out of 10) is provided.  Due to limitations on the number of files that could be uploaded at one time, several sets are split up. 
"Pure immunotherapy": trial run to t=100, then delta_t, the rate of killing of tumour cells by immune cells is bumped from 0.02 to 500. this was trialed for several lower values as well, but this one was the largest possible within model constraints, and shows the most extreme effects
Set 1: baseline cancer growth at various times 
Set 1.5: baseline cancer growth to t=100, followed by chemotherapy until t=220. Trial ends here, with zero tumour cells, for the sake of data collection 
Set 2: baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and baseline OVT (no immune boosts) is activated. 
Set 3.1: baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and ovt with gk (memory response) is activated. 
Set 3.2: baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and  OVT with sigmaI (number of immune cells) is activated. 
Set 4: baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and OVT with both gK and sigmaI is activated. 
Set 5: baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and OVT with lambda is activated.
Set 6.1.1: baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and OVT with lambda, gK and sigmaI in random variations activated (first set). 
Set 6.1.2: baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and OVT with lambda, gK and sigmaI in random variations activated (second set). 
Set 6.2 (6.2.1-6.2.4) baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and OVT with lambda=0.5 and various gK and sigmaI
Set 6.3 (6.2.1-6.2.4) baseline cancer growth to t=100, followed by chemotherapy until t=220. At t=220, MRD is planted and OVT with lambda=0 and various gK and sigmaI
