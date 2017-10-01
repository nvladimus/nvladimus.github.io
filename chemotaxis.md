# Bacterial chemotaxis and the first smart microscope
Chemotaxis in bacteria is a molecular mechanism by which they sense chemicals and change their behavior accordingly.
It has been studied extensively since late 60-s and became a triumph of quantitative system biology, 
thanks to giants like Julius Adler, Howard Berg, Daniel Koshland, to name a few. 

Perhaps the most instrumental in this revolution was Howard Berg's [tracking microscope](/pdf/1971Berg(How to track bacteria).pdf "Berg HC. How to track bacteria. Rev Sci Instrum. 1971 Jun;42(6):868-71."), 
which could track freely swimming *E.coli* cells in 3D. It allowed precize quantification of cell swimming trajectories 
in spatial gradients of chemicals and discovering that *E.coli* runs longer toward increasing concentrations of chemicals which attract her,
and tumble more frequntly when encountering lower concentration of attractant.

Even today in 2017, building a tracking microscope which keeps rapidly swimming bacterium in focus is not an easy task. 
The system must keep track of cell position in 3D within very small depth or field (high magnification) and accurately update servo positions with at least 50 Hz frequency (20 ms intervals). Fast CMOS cameras, real-time operating system, LabView, FPGA, and C/C++ were
unknown words in the late 1960-s. Computers were using punch cards and magnetic tapes. 

In a stunning *tour de force* Howard Berg created a
tracking microscope using optic fibers, photomultipliers, off-the-shelf analog electronic components, 
and electomagnetic coils on top of a Nikon upright microscope, at a cost below $10K (equivalent of ~60K in 2017). 
The tracking data were stored using an oscilloscope or magnetic tapes.

