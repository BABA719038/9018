# 9018
TITLE: An Ultra High Gain Switched-Capacitor Boost DC-DC converter with Reduced Ripple Current
Authors: 
M F Baba  , A V Giridhar  , Senior Member, IEEE , B L Narasimharaju  , Senior Member, IEEE and Harish S. Krishnamoorthy   , Senior Member, IEEE
simulation files
DESIGN SPECIFICATIONS
Specification	Rating	Simulation Details 
Input voltage	20 V	PSIM Plat Form
Time Step 10-7 sec
Output Voltage	400 V	
Power	200 W	
Inductors	L1=130 μH, L2=700 μH	
Capacitors	C0=100 μF, C1-C3=22 μF	
Diodes	D0, D2, D3 (STPSC10H065)	
	D1, (MBR10100)
	
Switches	S1  (FDPF3860T)
	
	        S2  (STW28N65M2)

  For the successful simulation keep the time step as 10E-7 and run the simulation for 1 to 2 sec depending on the memory size. If the memory is low on the PSIM directory go for 1 sec simulation.

The following are the schematic representation of the scope waveforms
VG=GATE PULSE
V0=OUTPUT VOLTAGE
VC1-3=CAPACITOR C1-C3 VOLTAGES
VD0-VD3=DIODE D1-D3 VOLTAGES
VS1-2= SWITCH 1 & 2 VOLTAGES
I(D0)-I(D3)=DIODE CURRENTS
I(S1)-I(S2)= SWITCH CURRENTS
I(C0), I(RC1)-I(RC3)=CAPACITOR CURRENTS
I(RL1)-I(RL2)=INDUCTOR CURRENTS
I(R1)=LOAD CURRENT

