To install the system:
- download the .tar.gz files and unzip them using the command: tar -xvzf "newfile" spat.tar.gz
- Adjust the path in the following files:
optional
- Adjust the dimensions in the parameter.h, see README.pdf.
Remark:
The system has been compiled with the Portland group compiler
Available at https://en.wikipedia.org/wiki/The_Portland_Group
  
optional:
gfortran with options:
-fdefault-real-8  -ftree-vectorize -static -save
Adjust the Makefiles accordingly.
