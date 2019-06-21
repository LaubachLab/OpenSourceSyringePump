# Open Source Syringe Pump

*Developed by Linda Amarante, Jonathan Newport, Megan Mitchell, Joshua Wilson, and Mark Laubach in the Center for Behavioral Neuroscience, Departments of Biology and Physics, and Design and Build Lab at American University.*

The neural basis of reward processing is a major topic in neuroscience. Many studies examine reward coding by varying the amount of fluid given to experimental animals as they perform a behavioral task. Most devices used in these studies are not capable of delivering different volumes over a common period of time. As such, reward coding is confounded by temporal information. To resolve this issue, we developed a syringe pump controller that is capable of delivering different fluid volumes, in the range used in behavioral studies, over common periods of time. Here, we report the designs of all components of the pump and the protocols needed to create and use it.

There are two parts of this project:

1. Syringe Holder: To house the syringe, we modified a 3D printed syringe pump design ([Wijnen et al., 2014](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0107216)) and some modifications described [HERE](https://www.appropedia.org/Lynch_open_source_syringe_pump_modifications). This part is not essential for the project, as any syringe holder that can fit a 60 mL syringe will do. We made additional modifications to accommodate a NEMA-17 integrated stepper motor, and for the pump holder to fit either a 30 or 60 mL syringe. We also adjusted the end pieces to have a more stable base for the holder. stl files for the 3D printed parts for a 60 mL syringe are available in this repository.
2. Control Board: The main innovation of the project is the syringe pump controller and programming library. The schematic, printed circuit board (PCB), and manufacturing files are available in this repository. PCBs were designed using AutoCAD Eagle (Autodesk) software. Boards are also available directly from various PCB manufacturing houses, including OSH Park: [Open Source Syringe Pump PCB](https://oshpark.com/shared_projects/VtseE2Ia))

The Bill of Materials for this device are provided in [OpenSourceSyringePumpBOM.xlsx](https://github.com/LaubachLab/OpenSourceSyringePump/blob/master/OpenSourceSyringePumpBOM.xlsx).

Build instructions are provided in provided in [OpenSourceSyringePumpBuildInstructions.pdf](https://github.com/LaubachLab/OpenSourceSyringePump/blob/master/OpenSourceSyringePumpBuildInstructions.pdf).

The mathematical basis for how the device works to deliver dissimilar volumes of fluid in equal time intervals is described in [t_min and velocity formulas.pdf](https://github.com/LaubachLab/OpenSourceSyringePump/blob/master/t_min%20and%20velocity%20formulas.pdf).

Images of the control board and [teensy](https://www.pjrc.com/teensy/) controller are provided below:

![Syringe Board Pinout](Syringe_Board_Pinout.png)

![Teensy Pinout](Syringe_Teensy_Pinout.png)