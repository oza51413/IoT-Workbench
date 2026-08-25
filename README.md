# IoT-Workbench
My personal toolkit for exploring, analyzing, and hacking IoT devices.    

- Thinkpad x250  
- Digital Multimeter(DMM)    
- iFixit Essential Electronics Toolkit  $30
- Soldering Mat
- Dupont Wires  
- Jumper cables  
- Micro SD Card Reader  
- USB-UART adapter  
- Logic Analyzer  
- Flash Programmer  
- Pinecil v2 Soldering Iron  
- 3rd Hand  
- Large iFixit Tool Pouch



# Orange Pi Zero 2w Build    
- AI Augmented IoT Hacking with the OrangePi Zero 2w

- Usage: AI gets access to the pi through ssh
  - project folder for the AI to access
  - sub folders /Recon, /Foothold, /RevEng  
  - AI gets access to the hardware
 
  
1. Recon
  - images of the device  
  
2. Foothold
  - signal analysis/interposition
  - protos: uart,i2c,jtag

3. RevEng
  - tools: wairz, claude  
  
**Inspired by/Credit to Andrew Bellini, saw a build he made using the rpi on his defcon slide deck**  


1. Orange Pi Zero 2w
  - UART connected through pi's pins

2. USB Hat    
  - allows for usage of logic analyzer + flash programmer    
  - Alfa wifi card (packet injection)
  - Nordic NRF BLE Sniffer  

3. 5v Relay    
  - safety precaution, not trying to fry the pi
  - connects to pi's pins   

4. Mini Bread Board
  - used to mount all of the components
 



