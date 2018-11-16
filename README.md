# tvws_pcb_projects
Altium PCB projects contained in Ryan E. Guerra's PhD thesis:  "Large-Scale Software Defined Radio Systems: Design, Implementation, and Evaluation."

## agc_test_board

PCB Picture | 3D PCB Model
:-------------------------:|:-------------------------:
<img src="/agc_test_board/agc_calibration_board.jpg" width="300"> | <img src="/agc_test_board/agc_calibration_board_model.png" width="300">

## rf_protoboard

PCB Picture | 3D PCB Model
:-------------------------:|:-------------------------:
<img src="/rf_protoboard/rf_protoboard.jpg" width="300"> | <img src="/rf_protoboard/rf_protoboard_model.png" width="300">

## wab_1x1

PCB Picture | 3D PCB Model
:-------------------------:|:-------------------------:
<img src="/wab_1x1/WAB-1x1-C.jpg" width="300"> | <img src="/wab_1x1/WAB-1x1-C_model.PNG" width="300">

## wab_1x4

PCB Picture | 3D PCB Model
:-------------------------:|:-------------------------:
<img src="/wab_1x4/WAB-1x4-A.jpg" width="300"> | <img src="/wab_1x4/WAB-1x4-A_model.png" width="300">

## wurc

PCB Picture | 3D PCB Model
:-------------------------:|:-------------------------:
<img src="/wurc_d/WURC-D.png" width="300"> | <img src="/wurc_d/WURC-D_model.png" width="300">

# How to Use

All libraries were archived with Altium Designer 18.1.9, so each folder should be self-contained with complete parts libraries and Altium project. Each Altium project ends in `*.PrjPCB`, so this is where you should start.

Each project has a checked-in schematic and PCB image for quick review

Every PCB here has been manufactured and validated, however the prototype and test boards were definitely learning experiences and don't always exhibit best practices for PCB design and don't always leverage all of the DFM tools Altium has to offer. It is my sincere hope that these designs will be used as reference or for comparison, both for what was done well and what was done poorly. Some things to watch for:

1. Acid traps and acute angles -- many of the early prototype boards have these before we learned to avoid them.

1. Accurate 3D components and clearances -- we also learned to use the Altium 3D modeling tools through these designs, so you can see our parts library getting more advanced and accurate as time progresses. Take these models with a grain of salt, if they are even included.

1. Clean BOMs -- we were also unfamiliar with Altium's schematic capture and supplier link tools, and these features have evolved greatly over the years. I would not be surprised if we had broken links and obsolete parts left in these designs.

1. Signal integrity -- we've learned to follow good signal integrity and EMI-suppression practices over the years. Many of these designs do not follow best practices for continuous ground planes and return current paths, and we believe that WURC's clocking signals should be buried deep between power layers to avoid radiated emissions.

# License

I have decided to release these designs into the public domain so that they might be useful to any student, professional, or business that is interested in reviewing a series of manufacturable PCB designs related to RF and microwave circuits. If you can use these designs in whole or in part for any purpose, commercial or otherwise, then good luck and Godspeed.

I do not need attribution, though it's nice. As a business owner myself, I do not believe that copyleft licenses are useful in promoting the wide adoption and use of intellectual property released into the public domain. Companies rightly spend a lot of time and effort avoiding GNU-type source code creeping into their products. If the goal is to avoid wasting human effort re-inventing the wheel over and over again, then copyleft doesn't really do a great job of that.

## MIT Open-Source License

Copyright 2010-2018 Ryan E. Guerra

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Additional Disclaimer

THE HARDWARE DESIGN FILES ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE HARDWARE DESIGN OR THE USE OR OTHER DEALINGS IN THE HARDWARE DESIGN. THIS INCLUDES ANY DERIVATIVE PRODUCT MANUFACTURED BASED ON THESE DESIGN FILES.




