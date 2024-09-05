Check out the [Preconfigured 3mf Files](Preconfigured%203mf%20Files/) directory for slicer files that contain all required parts with support and other print settings preconfigured. Just delete the rings that don't apply to your build, select your filament and send the job to your printer. EZ


## Printing:
The entire project is intended for:  
  - 0.4mm nozzle (Wider should not cause problems)
  - 0.2mm layer height (Necessary for some built-in helper features)
  - Standard strength (5 wall) profile
  - 15% gyroid or crosshatch infill
    - Higher infill optional

All parts tested in PLA and PETG  

Supports required for:
  - PitClamp Mini - Common - Handle
  - PitClamp Mini - Base - Standard - Lower
  - PitClamp Mini - Common - Upper
  - PitClamp Mini - Ring - 57AIM
  - PitClamp Mini - Ring - iHSV57

![](../Images/Print/PitClamp%20Mini.png)  
![](../Images/Print/PitClamp%20Mini%20-%20Rings.png)  

Optional accent color for logo.  
Requires AMS, just paint bucket the flush lettering faces:
![](../Images/Print/PitClamp%20Mini%20Branding.png)  


## Rings
### Ring Offsets:
- **5mm/6mm offsets** provide clearance for 4040 extrusion. Fine for 3030 setups as well.
    - These are the recommended ring offsets for all setups.
- **0mm/1mm offsets** are designed to sit close to 3030 extrusion. 
    - Only use this offset if you _really_ need things to be compact on 3030 setups. Can have clearance issues if your setup isn't absolutely perfect.


### 42AIM
    For 42AIM motors
      Centered motor mounting for just_b's Universal Head
      Off-center motor mounting for SpockAroundTheClock's Compact Head

### 57AIM
    For 57AIM "Gold" motors

### iHSV57
    For iHSV57 motors.  
    
    This ring is two parts but by using some design trickery it prints as one with minimal supports.  
    
    Ring snaps into two pieces after removing from printer.  
    
    Clasp each half around the motor.

### Extrusion Rings (Experimental)

    Connects to 3030/4040 extrusion to then use in a PitClamp mini.  

    This allows you to make a quick-disconnect motor arm that attaches to a base of your choice.
    Opens up modular stand possibilities.  
    
    Intended to be used with Quick Clamp Ratchet base, but be creative!
