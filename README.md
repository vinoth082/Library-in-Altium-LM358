# Library-in-Altium-LM358

# Experiment: Creation of LM358 Library in Altium Designer

## Aim

To create a **schematic symbol and PCB footprint library for the LM358 dual operational amplifier** using **Altium Designer**, and verify the created component library for use in PCB schematic and layout design.

## Apparatus / Software Required

* [1] Computer system with Windows OS
* [2] **Altium Designer** software
* [3] LM358 datasheet
* [4] Internet access, if required for reference
* [5] Basic knowledge of schematic capture and PCB design
* [6] Standard LM358 package information/datasheet

## Procedure

### Part A – Create a New Integrated Library Project

1. Open **Altium Designer**.
2. Create a new project using **File → New → Project → Integrated Library**.
3. Provide a suitable project name, such as **LM358_Library**.
4. Save the project in the desired working directory.
5. The project should contain the required **Schematic Library (.SchLib)** and **PCB Library (.PcbLib)** files.

### Part B – Create the LM358 Schematic Symbol

6. Open the newly created **Schematic Library**.
7. Select **Tools → New Component** to create a new schematic component.
8. Enter the component name as **LM358**.
9. Refer to the LM358 datasheet and identify the device pins.
10. Create the symbol for the dual operational amplifier. The LM358 contains:

* **Op-Amp A**
* **Op-Amp B**
* **Power pins: VCC and GND**

11. Place two triangular op-amp graphical elements in the schematic symbol editor.
12. Add the appropriate input and output pins for both operational amplifiers.
13. Assign suitable pin numbers according to the selected LM358 package/datasheet.
14. Add the power pins **VCC** and **GND**.
15. Configure the electrical type and orientation of each pin appropriately.
16. Add component properties such as:

* Designator: **U**
* Comment/Description: **LM358 Dual Operational Amplifier**
* Manufacturer information, if required.

17. Arrange the pins neatly and ensure that the symbol is electrically correct.
18. Save the schematic library.

### Part C – Create the PCB Footprint

19. Open the **PCB Library (.PcbLib)**.
20. Create a new PCB footprint named according to the selected LM358 package, for example:

* **LM358_DIP8** for an 8-pin DIP package.

21. Refer to the LM358 datasheet for the exact package dimensions and recommended land pattern.
22. Draw the required **eight pads** corresponding to the eight LM358 pins.
23. Assign the correct pad numbers from **1 to 8**.
24. Set the pad dimensions and spacing according to the manufacturer's recommended footprint.
25. Draw the component outline on the appropriate mechanical layer.
26. Mark **Pin 1** clearly using a suitable polarity/orientation indicator.
27. Add required reference or assembly markings.
28. Verify the footprint dimensions against the LM358 datasheet.
29. Save the PCB footprint library.

### Part D – Link Symbol and Footprint

30. Return to the LM358 schematic component in the schematic library.
31. Open the **Models** or **Footprint** section of the component properties.
32. Add the LM358 PCB footprint created in the PCB library.
33. Verify that the schematic symbol pin numbers correspond correctly with the PCB footprint pad numbers.
34. Save the component.

### Part E – Verify the Library

35. Compile the Integrated Library project.
36. Check for compilation errors and resolve any incorrect pin or footprint assignments.
37. Create a test schematic and place the newly created **LM358** component.
38. Verify the symbol appearance and pin numbering.
39. Assign the footprint to the component and verify the PCB footprint.
40. Transfer the design to the PCB editor using **Update PCB from Schematic**.
41. Confirm that the LM358 footprint appears correctly in the PCB layout.
42. Check the pad numbering, package orientation, dimensions, and connectivity.
43. Save the completed library for future PCB design projects.

## Precautions

1. Always refer to the **latest LM358 datasheet** before creating the symbol and footprint.
2. Verify the **package type** before designing the footprint.
3. Ensure that schematic pin numbers exactly match the PCB footprint pad numbers.
4. Check the **Pin 1 orientation** carefully to avoid incorrect component placement.
5. Verify pad dimensions, pitch, and package dimensions against the manufacturer's recommended land pattern.
6. Run the library/project compilation before using the component in an actual PCB design.
7. Perform a final **ERC/DRC check** after integrating the component into a PCB project.

## Screenshots


<img width="627" height="510" alt="image" src="https://github.com/user-attachments/assets/10d30916-2284-4ea6-b3bd-a1ed201914d2" />



<img width="1911" height="1198" alt="image" src="https://github.com/user-attachments/assets/8d82e970-3362-4f25-a4c9-18d441034ea0" />



<img width="846" height="840" alt="image" src="https://github.com/user-attachments/assets/f4ed880c-0209-45ad-b3de-86bf4ef18563" />



<img width="460" height="361" alt="image" src="https://github.com/user-attachments/assets/916c23a4-229b-42fa-b36e-94a319a505cf" />


## Result

The **LM358 schematic symbol and corresponding PCB footprint library were successfully created using Altium Designer**. The component was verified by placing it in a test schematic and transferring it to the PCB layout. The symbol-to-footprint pin mapping, pad numbering, package dimensions, and component orientation were checked and found to be correct.
