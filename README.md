# VLSI-LAB-EXP-6

# AIM:

To create,simulate the design of CMOS inverter,NAND,NOR from schematic using cadence.

# APPARATUS REQUIRED:

cadence

# PROCEDURE:

**Commands to get into Cadence**

Right Click and open the terminal window
Type the following commands as follows and press enter. i) tcsh ii) source /home/install/cshrc iii) virtuoso

**Procedure for Schematic simulation using Cadence**

Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
Close the 2nd window
Use 1st window i.e virtuoso window(CIW) for further processing. i) Create a New Library ii) Create Schematic Cell view. iii) Create the Symbol for schematic Cell view. iv) Create the test Cell view. v) Analog simulation by spectre

**Procedure for Creating New Library.**

a) File –New – Library b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK c) Attach the library to the technology library gpdk045.Click OK

**Create Schematic Cell view.**
a) Go to 1st window i.e virtuoso(CIW) b) File-New-Cell view c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic d) Type: Schematic press OK e) Add the required components from the libraries and make the connections. f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin h) Make the connections by using fixed narrow wire key i) Click Check and Save button

**Creating the Symbol for schematic Cell view**

a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok b. Now Symbol generation form appears. Click Ok If No changes required c. A new window with with default symbol is created. d. Edit the symbol if you want to give actual symbol shape else continue. i. Execute Create-Cell view-from cell view ii. Library Name and Cell Name must be same which you have used for schematic. Press OK iii. Check for the position of pin side.Prss OK iv. Edit for the shape by Create-Shape-Choose required options to edit.

**Creating the new test cell view**

a) Go to CIW window, Execute File-New-Cell view b) Setup the new file form Library: Select the one you a created. Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test View: Schematic Type: Schematic press OK

**Analog simulation by SPECTRE.**

a. In test cell view window i. Launch – ADE L(Analog Design Environment) b. Execute Setup—Simulation/directory/Host A new window opens c. Set the simulation window to spectre and click ok d. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK. e. Execute Analysis – Choose. A window opens. f. Select the type and set the specifications and press OK g. Execute Output s—to be plotted – Select on Schematic h. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse i. Execute Simulation -- Net list and Run

# INVERTER SCHEMATIC:

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/30a4b7b8-ae3b-44c2-b441-eda48c7a027c)

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/e76a0703-7925-4953-96c3-622aebb80d8f)

**Specifications:** Vpulse

V1 = 0	       

V2 = 1

td = 0,tr=tf=1 n, ton= 100n ,T=200n

Vdc = 1

Simulation Settings

Setup for transient analysis:

Stop time =400n

Setup for D.C analysis

Component to be selected in schematic is for d.c analysis

Start = -1 Stop = 1 resp.

Expected Waveform:

**Transient Analysis:**

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/b668a40a-28ac-4083-928d-4225a40c816a

**DC Analysis:**

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/d9a97d70-b9be-4360-a7a3-2bb7164a9ca1)+

**NAND SCHEMATIC :**

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/a65932b1-1183-49d0-88c9-d6304a71bdd5)

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/da4a3b14-2525-4d70-b39b-8241adc70100)

**Specifications:**

Vpulse

Va1 = 0 Va2 = 1 tr=tf=50ps, period=20ns pulse width = 10ns

Vb1 = 0 Vb2 = 1 tr=tf=50ps, period=40ns pulse width = 20ns

Vdc = 1

**Expected Waveform:**

**Transient Analysis:**

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/1d959486-ac4b-4dd2-ab15-3531a0ee8c9a)

**NOR SCHEMATIC:**

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/648f465b-0228-4947-90df-5f6bd45e5a44)

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/44d0ea21-9d76-4bcb-b46f-ded6bc2d14aa)

**Specifications:**

Vpulse

Va1 = 0 Va2 = 1 tr=tf=50ps, period=20ns pulse width = 10ns

Vb1 = 0 Vb2 = 1 tr=tf=50ps, period=40ns pulse width = 20ns

Vdc = 1

Expected Waveform:

**Transient Analysis:**

![image](https://github.com/priyangi123/VLSI-LAB-EXP-6/assets/165141104/6c04fec6-88ab-45db-b1cf-7c81b7ddd77b)

# RESULT:

Thus, the design,simulation and verification of the CMOS inverter,NAND,NOR from schematic using cadence was successfully completed.



