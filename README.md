# tensorflow_no_avx
If you install standard version tensorflow pip package in Intel ATOM platform (for example J1900). You can find coredump issue. It has been root-caused by avx instruciton set. The solution to solve the issue is simple: build a pip package without avx.


The folder has pre-built version for your quick test. It's only for python 3.6.

