Snappy Molden 5.8

Molden is a package for displaying Molecular Density from the Ab Initio packages GAMESS-UK , GAMESS-US and GAUSSIAN and the Semi-Empirical packages Mopac/Ampac, it also supports a number of other programs via the Molden Format. Molden reads all the required information from the GAMESS / GAUSSIAN outputfile. Molden is capable of displaying Molecular Orbitals, the electron density and the Molecular minus Atomic density. Either the spherically averaged atomic density or the oriented ground state atomic density can be subtracted for a number of standard basis sets. Molden supports contour plots, 3-d grid plots with hidden lines and a combination of both. It can write a variety of graphics instructions; postscript, XWindows, VRML, povray, OpenGL, tekronix4014, hpgl, hp2392 and Figure. Both Xwindows and OpenGL versions of Molden are also capable of importing and displaying of chemx, PDB, and a variety of mopac/ampac files and lots of other formats. Molden also can animate reaction paths and molecular vibrations. It can calculate and display the true or Multipole Derived Electrostatic Potential and atomic charges can be fitted to the Electrostatic Potential calculated on a Connolly surface. Molden also features an stand alone forcefield program ambfor, which can optimise geometries with the combined Amber (protein) and GAFF (small molecules) force fields. Atom typing can be done automatically and interactively from within Molden, as well as firing optimisation jobs. Molden has a powerful Z-matrix editor which give full control over the geometry and allows you to build molecules from scratch, including polypeptides. Molden was also submitted to the QCPE (dead?) (QCPE619), allthough the Xwindows version is considerably running behind on the current one.


It consists of:

Nextcloud 13.0.6
      - g++
      - make
      - gfortran 
      - libx11-6 
      - libx11-dev
      - libgl1-mesa-glx 
#      - libgl1-mesa-dev 
#      - build-essential 
#      - mesa-common-dev 
#      - libglu1-mesa-dev 
#      - libxmu-dev
#      - xutils-dev

This Molden snap is available in the store for release series 16 (e.g. Ubuntu 16.04). Install via:

$ sudo snap install molden

There are a number of releases available. By default you'll get the newest stable one, but you may be interested in others.