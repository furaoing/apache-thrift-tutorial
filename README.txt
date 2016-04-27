Thrift Version In this Project: 0.9.3


1. Generate Thrift Interface Libs from Thrift file (IDL)
python (python2.7 only): thrift --gen py NlpService.thrift
python 3.4 use thriftpy
java: thrift --gen java NlpService.thrift

2. Define Service in IDL file, implement service as a service handler (class) in the server source code
