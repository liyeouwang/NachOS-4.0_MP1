# NachOS-4.0_MP1
Instruction
Compile/Rebuild NachOS:
  cd NachOS-4.0_MP1/code/build.linux
  make clean
  make
Test NachOS:
  cd NachOS-4.0_MP1/code/test
  make clean
  make halt
  ../build.linux/nachos -e halt
