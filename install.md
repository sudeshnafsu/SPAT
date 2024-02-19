To install the system:
- download the .tar.gz files and unzip them using the command: tar -xvzf "newfile" spat.tar.gz
  
- Adjust the path in the following files:
optional
Makefile.alpha11, Makefile.atest, Makefile.bander2u, Makefile.bander2v, Makefile.consolid, Makefile.datachecknew1, Makefile.datachecknew2, Makefile.epcsolv3u, Makefile.epcsolv3v, Makefile.epcsolv4u, Makefile.epcsolv4v, Makefile.epsilu, Makefile.epsilv, Makefile.narc, Makefile.newcheck, Makefile.sadie, Makefile.sadie13, Makefile.translate, Makefile.udev, Makefile.windowcheck.

- Adjust the dimensions in the parameter.h, see README.pdf.
Remark:
The system has been compiled with the Portland group compiler
Available at https://en.wikipedia.org/wiki/The_Portland_Group
  
optional:
gfortran with options:
-fdefault-real-8  -ftree-vectorize -static -save
Adjust the Makefiles accordingly.
