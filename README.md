# LabViewPowerSupplyControl
Usage Notes and Instructions:

Requirements: dac-8u10e.dll ,  and all the subVI's   (must be in same folder as this VI) 


1. Ensure that the DAC and ADC driver is active (the  blue 12 icon should be shown in your system tray) and ensure that the DAC & ADC are connected to the correct USB/Com port and the DAC inputs are showing the correct data within the DAC_ADC user interface. Now you are ready to press Run!

2. To turn the Power Supply ON/or OFF, click on "Relays Control On", then choose "POWER ON/or POWER OFF" from the Measurement Contol box to your left, then click on "Relays Control Off" again. 

3.  Choose the voltage value (0- 50 V) for each of the channels in the "Voltage Input Interface", then DAC and the Voltage output values will be displayed automatically.

4. You can check for the current (nA) values for any of the 8Th channels, one at a time. Choose from the Measurement control box  (I1 - I8), then press on  "Relays Control On" to be displayed and press "Relays Control Off" to turn it off after you are done. All the current measurements will be displayed in Channels from 1- 8.

%. NOTE: Please make sure to de-energize the relays  (click on "Relays Control Off") after each time you use it before you go to the next selection.

% NOTE: Flip all 8 channels  and the main switch to the "REMOTE" position for computer control operation.

% NOTE: You can STOP the program at any time by pressing the STOP button.
