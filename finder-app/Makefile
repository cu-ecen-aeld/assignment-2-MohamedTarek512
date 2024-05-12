export CROSS_COMPILER=/home/mohamed/tools/gcc-arm-10.3-2021.07-x86_64-aarch64-none-linux-gnu/bin/aarch64-none-linux-gnu-gcc


 all:
	gcc writer.c -o writer
 	
 CROSS_COMPILE:
	$(CROSS_COMPILER) writer.c -o writer

 clean:
	rm -f writer
