Currently using Google Protocol Buffers 3.0.0

The h and cc files for generated by the 3.0.0 compiler are included.  
If you wish to regenerate you must aquire the 3.0.0 proto buff compiler 
(https://code.google.com/p/protobuf/).  Also the protobuff library for 
win32 version 2.5.0 is included.  if you change versions or move to a 
different platform you must recompile and link to the project.

/include - header files.

/src - .cc files with class implementations

/lib - the libprotobuf library compiled for win32

protoc.exe - protocol buffer compiler for win32


NOTE:

To compile .proto file:

Navigate to current directory in command line
protoc --cpp_out=src/ autonomy.proto
move the generated header from /src to /include
