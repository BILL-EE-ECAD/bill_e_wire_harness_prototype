# bill_e_wire_harness_prototype
Generate the wire harness for the Cal Poly Pomona Bronco Space Rover Team - BILL-E


# Description
The wire harness is the collection of wires, connectors, cables, sheaths, that connect all the different electronic componants in the rover. This repository contains the block diagrams, design files, wireViz soirce code and outputs. 

From this repository, one should be able to re-creaate the harness with help from the corresponding Notion page. 

# Block Diagram
The connections made in the prototype rover are blocked here. Creation of WireViz requires this image. 
![Wire_Harnesss_Photo]([http://url/to/img.png](https://github.com/BILL-EE-ECAD/bill_e_wire_harness_prototype/blob/main/docs/billie_rover_prototype_wire_harness_block_diagram_V0_2_1_2-power_wire_harness.drawio.png))

# Dependencies
This python app uses the following packages:
- [WireViz](https://github.com/formatc1702/WireViz)
- pandas ver?
-[Python 3.7](https://www.python.org/downloads/release/python-370/) or later
- [GraphViz](https://graphviz.org/download/) for "Your" operating System
# Installation
TBD
# Executing the Program
Open terminal program and type something like:
```$ wireviz ~/path/to/file/mywire.yml```

This will output the following files
```
mywire.gv         GraphViz output
mywire.svg        Wiring diagram as vector image
mywire.png        Wiring diagram as raster image
mywire.bom.tsv    BOM (bill of materials) as tab-separated text file
mywire.html       HTML page with wiring diagram and BOM embedded
```

# Help
If you want to contribute and improve this repository, create a fork and make your changes. Create a pull request when you have finished your new feature. Refer to the [Contributing on GitHub](https://gist.github.com/MarcDiethelm/7303312).
# Authors
Jovany Zepeda @ JovanyZepeda
# Acknowledgements and References
