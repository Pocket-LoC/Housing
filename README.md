# Pocket-LoC
<img align = "right" src="https://user-images.githubusercontent.com/42568983/202521498-0bb95a05-1dd4-4db9-ad12-fc51b9aba1ed.jpg" width="40%" /> 
Lab-on-chip (LoC) technology is becoming increasingly relevant, especially in the field of medicine. However, often LoC setups rely on complex lab equipment for operation. The aim of this project is to create an affordable and portable LoC setup as a proof-of-concept for truly pocket-sized LoC - the Pocket LoC.

Pocket LoC can be assembled with standard equipment found in a typcial engineering lab (such as a maker space or FabLab). Once assembled, Pocket LoC is fully portable and only needs a PC to operate.

## Housing
This repository contains the design files and instructions for the Pocket LoC housing as well as the assembly instructions and parts lists required for the complete setup.

### 3D-printed parts
The housing is designed for 3D-printing. Although many different options for materials and printer settings are possible, I achieved best results using PETG with a layer height of 0.2mm on an 'Original Prusa i3 MK3S+'. Most standard 3D-printers and materials (e.g. PLA or ABS) should work, although some adjustments of part tolerances may be necessary.

The housing was designed in FreeCAD ([CAD folder](https://github.com/Pocket-LoC/Housing/tree/main/CAD)). Ready-to-print models (.stl) can also be found in the CAD folder. All parts can be printed without support structures.

### List of parts and tools
- 3D-printer
- dark, opaque printing filament (e.g. [black PETG](https://www.prusa3d.com/product/prusament-petg-jet-black-1kg/)) (approx. 30€)
- [Pocket LoC Sensor](https://github.com/Pocket-LoC/Sensor)
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
1.  Print the housing parts found in the CAD folder:
      - Base
      - Lid
      - Reservoir holder
      - Reservoir fixation block (4x)
      - Chip fixation block (2x)
      - Sensor cover
      
      <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/00%20all%20components.jpg" width="50%"/>
   
2. Fold the FFC as shown, about 25mm from one end and insert it into the connector on the LED PCB (part of the Pocket LoC sensor). Ensure the contacts of the FFC are facing outwards and the latch of the connector is properly fixed.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/10%20top%20components.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/11%20top%20assembly.jpg" width="22%" /> 
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/12%20top%20assembly.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/13%20top%20assembly.jpg" width="22%" />
      </p>

3. Place the LED PCB in the top, threading the FFC through the hole and underneath the two holding bars. Tweezers may help with the last section.
      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/14%20top%20assembly.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/15%20top%20assembly.jpg" width="22%" /> 
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/16%20top%20assembly.jpg" width="22%" />
      </p>

4. Fold over the contact section of the FFC end. Then add a second fold, producing a Z-shape, at approx. ?? mm. Fold the FFC over at a right angle directly next to the last fold. Finally, add a crease ?? mm from the outer edge of the angled fold. The folded FFC should look similar to the last picture.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/17%20top%20assembly.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/18%20top%20assembly.jpg" width="22%" /> 
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/19%20top%20assembly.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/19b%20top%20assembly.jpg" width="22%" />
      </p>

5. Connect the base and lid by inserting the rod into the hinge section. A vice may help to push the rod in carefully.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/20%20hinge%20components.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/21%20hinge%20assembly.jpg" width="22%" /> 
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/22%20hinge%20assembled.jpg" width="22%" />
      </p>

6. Connect the sensor PCB to the FFC, again ensuring the contacts are facing outwards and the connector is properly fixed. Put the sensor in the base section with the USB and FFC connectors facing downwards and add the cover. Depending on your print quality, you may have to use a needle or thin drill to ensure the holes in the cover are clear from residue.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/30%20sensor%20components.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/31%20sensor%20connect.jpg" width="22%" /> 
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/32%20sensor%20insert.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/33%20sensor%20assembled.jpg" width="22%" />
      </p>

5. Assemble the reservoir holder with four Luer adapters, some tubing, and the fixation blocks. First, connect the tubing to the Luer adapters, then place them in the reservoir holder and add the fixation blocks. The blocks should be flush with the surface of the reservoir holder.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/40%20reservoir%20components.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/41%20reservoir%20first%20insert.jpg" width="22%" /> 
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/42%20reservoir%20first%20holder.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/43%20reservoir%20assembled.jpg" width="22%" />
      </p>

6. Connect the reservoir holder to the base section, threading the tubes through the holes on the side.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/44%20reservoir%20connect.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/45%20reservoir%20connected.jpg" width="22%" /> 
      </p>

7. Assemble the pump driver section, ensuring that the marked "PIN1" on the driver section (Bartels Highdriver-4) is aligned with the USB connector of the pump controller. Then insert the micropumps (Bartels mp6-liq), ensuring that the arrows are facing away from the USB connector, and close the connectors by pushing them down. Tweezers may help if you have to open the connectors again to remove the pumps.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/50%20driver%20components.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/51%20controller%20assembly.jpg" width="22%" /> 
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/52%20first%20pump%20connected.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/53%20driver%20assembled.jpg" width="22%" />
      </p>
      
8. Insert the pump driver section into the base with the pump arrows facing the Pocket LoC logo. You will have to slightly bend the pump wires by pushing the pumps towards the controller. Connect the reservoir inlet and outlet tubing, which can be threaded through underneath the Pocket LoC logo. Again the tweezers may be useful here.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/54%20driver%20insert.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/55%20driver%20assembled.jpg" width="22%" /> 
      </p>

9. Insert the chip fixation blocks, used to align the microfluidic chip with the sensor aperatures. Depending on the size and layout of your microfluidic chip you may have to customise the blocks to fit your needs. The CAD folder contains samples for both a centered and one-sided chip placement.

      <p float="left">
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/60%20holder%20components.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/61%20holder%20assembled.jpg" width="22%" /> 
      </p>

10. Finally, insert one USB cable each for the sensor and pump controller, connect to a PC and start your experiments. Some sample code is provided for both the sensor and pump controller in their repositories to help you get started. Your reagents can simply be connected through the Luer adapters. We suggest the use of 3ml syringes. In some cases you may produce better results if you remove the plungers from the syringes.

      <img src="https://github.com/Pocket-LoC/Housing/blob/main/Photos/70%20usb%20connect.jpg" width="22%" />
     
