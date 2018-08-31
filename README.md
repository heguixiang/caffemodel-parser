# caffemodel-parser
----
* installation：Just like caffe 
* function: Tranform caffemodel file to normal txt file both in CPU-ONLY and GPU model
* if you meet this error
'''
   blob.hpp:9:34: fatal error: caffe/proto/caffe.pb.h: No such file or directory
compilation terminated.
'''
    Then, you should do this step
'''
    protoc --cpp_out=/home/xxx/workspace/code/caffe/include/caffe/proto caffe.proto
'''

