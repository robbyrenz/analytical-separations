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
3. ECD (electron capture detector; this is a concentration-sensitive detector)
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

-------------------------------------------------------------------

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
- Also, I think they are universal detectors, so great all-rounder

----------------------------------------------
## ***Electron Capture Detector (ECD)***

### **How they work?**
- The carrier or makeup gas is either Nitrogen or 5% methane in Argon
- Gas entering the detector is ionized by high-energy electrons/beta-rays, producing low-energy thermal electrons
- Beta rays are emitted from a foil containing radioactive 63Ni
- Electrons formed in the plasma are attracted to the anode
- This produces a small current
- This current is maintained at a constant level by variable frequency pulses which is applied between the cathode & the anode
- When analytes with high electron affinity enter the detector, they capture some electrons & decrease the conducivity of the plasma, thus decreasing the current
- The detector responds by varying the frequency of the voltage pulses in order to maintain the constant current
- This frequency of pulses is the detector signal
- These pulses are related to the concentration of the electron-capturing analytes in the cell
- Detector gases require high purity 7 high flow rate through detector as sensitivity depends on gas flow rate
- Concentration-sensitive detector

### **Features and Advantages**
- Highly selective with electronegative functional groups & halides
- Highly sensitive for compounds to which it responds (halogenated chemicals): pg to fg
- Non-destructive

### **Disadvantages**
- Moisture decreases the sensitivity
- Narrow linear dynamic range (~10^3), so careful calibration is required
- Less sensitive (in general) to N, O, P, or aromatic rings; & also to saturated hydrocarbons, alcohols & amines
- Response factors are complicated (different analytes with same number of halogens can have very different responses)

### **Great detectors for?**
- For organics with electronegative functional groups (nitriles, nitro compounds), halogen-containing molecules, conjugated carbonyls & organometallic compounds
- Note: not good for saturated hydrocarbons, alcohols & ketones
-----------------------------------------------------------------

# **Inlets**
- Differences between the main inlet types
- Its features, advantages & disadvantages

## **3 main inlet types**
- Split
- Splitless
- On-column

## **3 major types of capillary GC inlet system for liquid samples (injection into open tubular columns)**
*In a nutshell:*
- ***Split:*** routine for introducing sample volume into open tubular column
- ***Splitless:*** best for trace levels of high-boilling solutes in low-boiling solvents
- ***On-Column:*** best for thermally unstable solutes & high high-boiling solvents; best for quantitative analysis

---------------------------------------------------
## ***Split Injection***
- Used for major component analysis or for analysis of concentrated samples
- Technique in which only a small portion of injected sample enters the column via injection through septum

### **Features and Advantages**
-

### **Disadvantages**
- 


---------------------------------------------------
## ***Splitless Injection***
- For trace analysis requiring as much of sample as possible

### **Features and Advantages**
-

### **Disadvantages**
- 


---------------------------------------------------
## ***On-Column Injection***
- Used for samples that decompose above their boiling points
- Preferred for quantitative analysis
- Initial column temperature is low enough to condense solutes in a narrow zone
- Warming the column initiates chromatography by vaporizing the analytes

### **Features and Advantages**
- Great for thermally unstable compounds
- Little loss of any solute occurs
- Ideal for quantitative analysis

### **Disadvantages**
- Requires a smaller column (diameter-wise) if one wants a better resolution
- Requires special syringe with thin silica needles for the smaller columns
