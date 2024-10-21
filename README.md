# MODIS Global Evapotranspiration Project (MOD16)

Gregory H. Halverson (they/them)<br>
[gregory.h.halverson@jpl.nasa.gov](mailto:gregory.h.halverson@jpl.nasa.gov)<br>
NASA Jet Propulsion Laboratory 329G

Kanishka Mallick (he/him)<br>
[kaniska.mallick@gmail.com](mailto:kaniska.mallick@gmail.com)<br>
Luxembourg Institute of Science and Technology

Claire Villanueva-Weeks (she/her)<br>
[claire.s.villanueva-weeks@jpl.nasa.gov](mailto:claire.s.villanueva-weeks@jpl.nasa.gov)<br>
NASA Jet Propulsion Laboratory 329G

### Abstract
The MODIS Global Evapotranspiration Project (MOD16) is a software package developed by a team of researchers from NASA Jet Propulsion Laboratory and the University of Montana. This software is a Python implementation of the MOD16 evapotranspiration algorithm, designed to process high-resolution instantaneous remote sensing imagery.

Unique features of the software include the ability to process remote sensing data with the MOD16 model and partition latent heat flux into canopy transpiration, interception, and soil evaporation. The MOD16 algorithm has been re-implemented to run on instantaneous high spatial resolution remote sensing imagery instead of 8-day MODIS imagery, making the model more accessible for remote sensing researchers.

The software is written entirely in Python and is intended to be distributed using the pip package manager.

The software was developed as part of a research grant by the NASA Research Opportunities in Space and Earth Sciences (ROSES) program. It was designed for use by the Ecosystem Spaceborne Thermal Radiometer Experiment on Space Station (ECOSTRESS) mission as a precursor for the Surface Biology and Geology (SBG) mission. However, it may also be useful for general remote sensing and GIS projects in Python. This package can be utilized for remote sensing research in Jupyter notebooks and deployed for operations in data processing pipelines. 

The software is being released according to the SPD-41 open-science requirements of NASA-funded ROSES projects.

### This software accomplishes the following:

This software package is the python implementation of the MOD16 evapotranspiration algorithm for high resolution instantaneous remote sensing imagery. 

### What are the unique features of the software?

- processing remote sensing data with the MOD16 model
- ability to partition latent heat flux into canopy transpiration, interception, and soil evaporation

### What improvements have been made over existing similar software application?

The MOD16 algorithm was re-implemented to run on instantaneous high spatial resolution remote sensing imagery instead of 8-day MODIS imagery.

### What problems are you trying to solve in the software?

This software makes the MOD16 evapotranspiration model accessible for remote sensing researchers.

### Does your work relate to current or future NASA (include reimbursable) work that has value to the conduct of aeronautical and space activities?  If so, please explain:

This software package was developed as part of a research grant by the NASA Research Opportunities in Space and Earth Sciences (ROSES) program. This software was designed for use by the Ecosystem Spaceborne Thermal Radiometer Experiment on Space Station (ECOSTRESS) mission as a precursor for the Surface Biology and Geology (SBG) mission, but it may be useful generally for remote sensing and GIS projects in python.

### What advantages does this software have over existing software?

This software can be utilized for remote sensing research in Jupyter notebooks and deployed for operations in data processing pipelines.

### Are there any known commercial applications? What are they? What else is currently on the market that is similar?

This software is useful for both remote sensing data analysis and building remote sensing data pipelines.

### Is anyone interested in the software? Who? Please list organization names and contact information.

- NASA ROSES
- ECOSTRESS
- SBG
- LIST

### What are the current hardware and operating system requirements to run the software? (Platform, RAM requirement, special equipment, etc.) 

This software is written entirely in python and intended to be distributed using the pip package manager.

### How has the software performed in tests? Describe further testing if planned. 

This software has been deployed for ECOSTRESS and ET-Toolbox.

### Please identify the customer(s) and sponsors(s) outside of your section that requested and are using your software. 

This package is being released according to the SPD-41 open-science requirements of NASA-funded ROSES projects.

## macOS

On Apple Silicon, the `pykdtree` package needs to be compiled from source to avoid conflict with `OpenMP`.

```
pip install --no-binary pykdtree pykdtree
pip install .[macos]
```

## Other Platforms
```
pip install .
```


