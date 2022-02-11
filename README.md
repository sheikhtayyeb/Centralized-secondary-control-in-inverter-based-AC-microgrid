# Centralized-secondary-control-in-inverter-based-AC-microgrid
[![View Centralized secondary control in inverter based AC microgrid on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://in.mathworks.com/matlabcentral/fileexchange/106355-centralized-secondary-control-in-inverter-based-ac-microgrid)
Since the primary control is local and does not have intercommunications with other units, in order to achieve global controllability of the Micro Grid, secondary control is often used. A secondary control, which measures from a remote sensing block a number of parameters to be sent back to the controller by means of a low bandwidth communication system. Hence, those variables are compared with the references in order to be compensated by the secondary control, which will send the output signal through the communications channel to each unit primary control.
Secondary controllers for large power systems are based on frequency restoration, since the frequency of the generator-dominated grids is highly dependent on the active power. This fact is an advantage since frequency is a control variable that provides information related to the consumption/generation balance of the grid.
Such a characteristic can be artificially created for electronically interfaced inverter-based AC microgrid. In droop control, the relationships between real power and frequency and reactive power and voltage are as follows: 

                                                𝜔𝑟𝑒𝑓= 𝜔𝑛𝑜𝑚𝑖𝑛𝑎𝑙−𝑚𝑝∗𝑃+Δ𝜔 
                                                
                                                V𝑟𝑒𝑓= 𝑣𝑛𝑜𝑚𝑖𝑛𝑎𝑙−𝑛𝑞∗𝑄+Δ𝑣
                                                
Δ𝜔 and Δ𝑣 are provided by the central control.
