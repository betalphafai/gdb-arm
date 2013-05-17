gdb for arm
===========

1.cd build/gdb/bin/
2.adb push gdb* /data/ 
3.chmod 777 gdb*
4.start APP
5.start gdbserver :PORT --attach APPPID
6.start gdb
7.gdb target remote :PORT
8.gdb set solib-search-path /path/to/solib/and/libc.so
9.gdb file /path/to/linker
10.gdb file /path/to/app_process
11.start debug so library
