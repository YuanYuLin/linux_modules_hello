#
## Makefile for kernel test
#
MODULE_NAME  = hello

obj-m      := $(MODULE_NAME).o

all:
	make CROSS_COMPILE=$(CROSS_COMPILE) ARCH=$(ARCH) -C $(LINUXKERNELROOT) M=$(KERNEL_MODULE_DIR)
clean:
	make CROSS_COMPILE=$(CROSS_COMPILE) ARCH=$(ARCH) -C $(LINUXKERNELROOT) M=$(KERNEL_MODULE_DIR) clean

