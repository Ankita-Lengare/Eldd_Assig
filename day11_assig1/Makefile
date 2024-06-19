
obj-m = gpio-work_queue.o

modules:
	 make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C /home/sunbeam/Desktop/linux/ M=`pwd` modules

clean:
	make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C /home/sunbeam/Desktop/linux/ M=`pwd` modules clean

.phony : modules clean
