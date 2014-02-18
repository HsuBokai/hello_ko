$ make

$ sudo insmod ./hello.ko

$ dmesg
(/var/log/message)????
will see "Hello kernel"

$ sudo rmmod ./hello.ko

$ dmesg
(/var/log/message)????
will see "Goodbye"

$ make clean
