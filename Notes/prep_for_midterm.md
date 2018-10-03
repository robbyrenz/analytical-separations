# **Midterm Exam Review**
## Made by Robby Renz
--------------------------------------

# **Detectors**
- Know how they work
- It's features
- Advantages
- Disadvantages
- Know that the type of analyte impacts your choice of detector

## **GC Detectors**
1. FID (flame ionization detector; this is mass-sensitive)
2. TCD (thermal conductivity detector; this is a concentration-sensitive detector)
3. ECD (electron capture detector)
4. NPD (thermionic or nitrogen-phosphorous; this is mass-sensitive)
5. FPD (flame photometric; this is mass-sensitive)
6. AED (atomic emission; this is mass-sensitive)
7. IRD (infrared)
8. MSD (mass spectrometric)

## **How GC detectors work in general?**
- Detect changes in the composition of column effluent
- Convert that info into a signal

## **How to compare responses of different detectors?**
- By checking its characteristics, namely:
	- Sensitivity
	- Limit of detection (LOD)
	- (linear) dynamic range (LDR)
	- Selectivity (either universal or highly selective)

## ***FID (Flame Ionization Detector)***

### **How they work?**
- The column effluent is mixed with hydrogen and air
- This effluent is burned with the help of a flame tip (jet tip)
- This inert carrier gas produces very little ionization, so it has a small baseline signal
- Most organic compounds produce ions & electrons
- This conducts electricity through the flame with the help of chemionization (chemical ionization)
	- Note that the temperature of flame is too low for thermal ionization
	- Carbon atoms (except C double-bonded O & COO) produce reaction of HC radicals 
	- (reaction happens here which produces electrons)
	- Current is produced by applying voltage between the jet tip and the collector electrode (positive electrode)
	- So cations migrate to cathode to produce a signal
	- Signal is magnified to produce a peak


### **Features and Advantages**
- Wide linear dynamic range (~10^7)
- Very sensitive (~ng)
- Cheap
- Nearly nonselective & universal; this detector responds to most organic compounds (see disadvantage)
- Mass-sensitive detector (response depends on amount of analyte reaching detector)

### **Disadvantages**
- Universal response isn't always a good thing; how do you tell peaks apart with very complex samples?
- Doesn't respond to organic compounds that don't burn well (like many halogenated compounds)
- Doesn't respond to common carrier gas impurities like water, carbon dioxide, sulfur dioxide, NOx, etc.
- Destructive detector

### **Great detectors for?**
- Hydrocarbons, like PAHs

-----------------------------------------
## ***Thermal Conductivity Detector (TCD)***

### **How they work?**
- Heat is conducted away from a hot filament at a rate that depends on the thermal conductivity of the gas which is in contact with the filament
	- Filament is heated by applying an electric current
	- Temperature of the filament depends on the thermal conductivity of the surrounding gas
	- So a steady-state signal is obtained when the carrier gas flows continously
	- When the analyte enters the cell from the column, the gas composition changes, and the thermal conductivity (usually) decreases
	- Consequently, the temperature of the filament increases and the resistance decreases (I'm sure the resistance should increase with the increase in temperature, unless the filament is an insulator)
	- The resistance of the filament actually decreases as there are conductors that have their resistances decreased when the temperature increases (confirmed by Dr. Wong)
	- Change in voltage is detected and a peak is recorded as the analyte passes through the detector
- To increase the sensitivity of the TCD:
	- use a carrier gas of high thermal conductivity (this also lowers the detection limit)
	- increasing filament current
	- use a filament with a sensitive resistance to temperature (Pt, Au, W-Re alloy)
	- decreasing the flow rate (of the carrier gas, I think)
	- optimize differences in the thermal conductivity between the analyte & the carrier gas
	- introduce a make-up gas
- This is a concentration-sensitive detector, which means the response depends on the concentration of the analyte in the detector

### **Make-up gases for detectors**
- Using a low flow rate for the carrier gas may not be sufficient for optimal detector performance
- That's where make-up gases come in -> introduce another gas between the end of the column and the detector
- Can be of the same gas, but its always at a greater flow rate
- This way, both the detector & the column performance is optimized independently
- How the make-up gas works:
	- TODO: double check the two points below if they are correct
	- Gas switching device will alternatively pass column effluent and reference gas over filament (like every 200 ms)
	- Thermal conductivity differences are measured, correcting for factors that causes variation in thermal conductivity, other than the presence of solute gas

### **Features and Advantages**
- Has a linear dynamic range of ~10^5
- Universal detector, responding to any organic or inorganic compound when helium or hydrogen is the detector gas (but use make-up gas for capillary columns)
- Non-destructive

### **Disadvantages**
- Universal detector
- Poor sensitivity (micrograms to ng, not as good as FID)

### **Great detectors for?**
- I guess any organic & inorganic compounds

----------------------------------------------
## ***Electron Capture Detector (ECD)***

### **How they work?**

