# by Xianjun jiao. putaoshu@msn.com; xianjun.jiao@imec.be

obj-m += rx_intf.o

all:
	make -C $(KDIR) M=$(PWD) modules ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf-

clean:
	rm -f *.ko *.o *.mod.o *.mod.c *.symvers *.order
