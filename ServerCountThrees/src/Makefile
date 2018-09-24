
MD := mkdir
RM := rm
CC := gcc
CP := cp
CD := cd

ServerCountThrees:
	$(CC) -o ServerCountThrees ServerCountThrees.c readInt32BitLE.c -I.

test:
	$(MD) ../build
	$(CP) ../data/threesData.bin ../build
	$(CP) ../src/ServerCountThrees ../build
	$(CD) ../build;./ServerCountThrees

clean:
	$(RM) -rf ../build
	$(RM) -f ../src/ServerCountThrees

