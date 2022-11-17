# Pocket-LoC
Lab-on-chip (LoC) technology is becoming increasingly relevant, especially in the field of medicine. However, often LoC setups rely on complex lab equipment for operation. The aim of this project is to create an affordable and portable LoC setup as a proof-of-concept for truly pocket-sized LoC - the Pocket LoC.

Pocket LoC can be assembled with standard equipment found in a typcial engineering lab (such as a maker space or FabLab). Once assembled, Pocket LoC is fully portable and only needs a PC to operate.

## Housing
This repository contains the design files and instructions for the Pocket LoC housing as well as the assembly instructions and parts lists required for the complete setup.

### 3D-printed parts
The housing is designed for 3D-printing. Although many different options for materials and printer settings are possible, I achieved best results using PETG with a layer height of 0.2mm on an 'Original Prusa i3 MK3S+'. Most standard 3D-printers and materials (e.g. PLA or ABS) should work, although some adjustments of part tolerances may be necessary.

The housing was designed in FreeCAD (see .. for files). Ready-to-print models (.stl) can be found in the STL folder. All parts can be printed without support structures.

### List of parts and tools
- 3D-printer
- dark, opaque printing filament (e.g. [black PETG](https://www.prusa3d.com/product/prusament-petg-jet-black-1kg/)) (approx. 30€)
- Pocket LoC Sensor incl. FFC -> Link
- Pocket LoC Pump Controller -> Link
- Metal rod or nail (approx. 1.7mm diameter) for the hinge
- 4x [Bartels mp6-liq Micropumps](https://darwin-microfluidics.com/collections/piezo-pumps/products/bartels-mp6-micropump) (128€)
- [Bartels Pump Driver](https://darwin-microfluidics.com/collections/piezo-pumps/products/mp-highdriver4-pump-driver) (159€)
- [Tubing](https://darwin-microfluidics.com/collections/silicone-tygon-tubing/products/mp-t-1-3-mm-tygon-tubing-for-bartels-micropumps) (9.50€)
- 4x [Luer Adapters](https://darwin-microfluidics.com/collections/luer-fittings/products/barbed-to-female-luer-adapter-for-1-16-1-8-and-3-32-id-soft-walled-tubing-pack-of-10?variant=32430390018184) (11.40€ for 10)
- 4x 3ml Syringes as reservoir (approx. 10€ for 100)
- Microfluidic Chip -> Link
- Tweezers

### Assembly
1.  Print the housing parts found in the STL folder:
      - Base
      - Lid
      - Reservoir holder
      - Reservoir fixation block (4x)
      - Chip fixation block (2x)
      - Sensor cover
      
<img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/00%20all%20components.jpg" width="50%"/>
   
2. Connect the FFC to the LED board and insert it in the lid.

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/10%20top%20components.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/11%20top%20assembly.jpg" width="22%" /> 
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/12%20top%20assembly.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/13%20top%20assembly.jpg" width="22%" />
</p>

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/14%20top%20assembly.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/15%20top%20assembly.jpg" width="22%" /> 
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/16%20top%20assembly.jpg" width="22%" />
</p>

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/17%20top%20assembly.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/18%20top%20assembly.jpg" width="22%" /> 
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/19%20top%20assembly.jpg" width="22%" />
</p>


3. Thread the FFC through the holders in the lid.
4. Connect the base and lid by inserting the rod into the hinge section. A vice may help to push the rod in carefully.

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/20%20hinge%20components.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/21%20hinge%20assembly.jpg" width="22%" /> 
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/22%20hinge%20assembled.jpg" width="22%" />
</p>

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/30%20sensor%20components.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/31%20sensor%20connect.jpg" width="22%" /> 
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/32%20sensor%20insert.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/33%20sensor%20assembled.jpg" width="22%" />
</p>


5. Assemble the reservoir holder with four Luer adapters, some tubing, and the fixation blocks. 

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/40%20reservoir%20components.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/41%20reservoir%20first%20insert.jpg" width="22%" /> 
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/42%20reservoir%20first%20holder.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/43%20reservoir%20assembled.jpg" width="22%" />
</p>

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/44%20reservoir%20connect.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/45%20reservoir%20connected.jpg" width="22%" /> 
</p>

driver assembly

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/50%20driver%20components.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/51%20controller%20assembly.jpg" width="22%" /> 
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/52%20first%20pump%20connected.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/53%20driver%20assembled.jpg" width="22%" />
</p>

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/54%20driver%20insert.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/55%20driver%20assembled.jpg" width="22%" /> 
</p>

holder assembly

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/60%20holder%20components.jpg" width="22%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/61%20holder%20assembled.jpg" width="22%" /> 
</p>

<img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/70%20usb%20connect.jpg" width="22%" />

complete

<p float="left">
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/80%20complete%20setup.jpg" width="40%" />
  <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/81%20inserted%20chip.jpg" width="40%" /> 
</p>
