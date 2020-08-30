simulinks files are serially numbered for demonstration. First demonstrate the individual part from no.1 to 5 then demonstrate the two part of project.
few modules of individual parts are removed for final simulation for reducing calculation complexity.dependent voltage source are used to isolate modules to reduce complexity. 
If you want to check how complex the calculations becomes then goto file 8.VPP_demo_DER2.slx then goto any Inverter block inside any DER block, remove the dependent sources and 
voltmeter connect the transformer output directly to the ports now simulate and see how far it go.

these files requires MATLAB2019b or higher to run or convert them to a downgrade version.

no preload or initialization function required. just open these files and run.


which files contains which modules:

f1_ac2dc- rectifier and buck converter 
f2_battery charing system - battery charging system using ac supply or solar panel
f3_inverter - a three phase inverter
f4_variable load - infinite bus system and dynamic load change
f5_VPP_controler_demo- Central controller module
f6_Central reservoir_demo - demonstrate the VPP system's central reservoir operation
f7_VPP_DER_demo - simulate the same setup for DERs and controllers without DERs
f8_VPP_demo_DER2 - demonstrate the VPP system with DERs and central controls 
