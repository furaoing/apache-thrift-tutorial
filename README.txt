Thrift Version In this Project: 0.9.3


1. Generate Thrift Interface Libs from Thrift file (IDL)
python (python2.7 only): thrift --gen py NlpService.thrift
python 3.4 use thriftpy
java: thrift --gen java NlpService.thrift

2. Define Service in IDL file, implement service as a service handler (class) in the server source code

3. Java: It is recommended that the thrift generated code to be deployed as a jar lib.
         However, introduce thrift generated code as source code is also available.
