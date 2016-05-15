CC=gcc
CFLAGS=-lrados -g

all:rados_write rados_read rados_rm
rados_write:rados_write.c
	$(CC) $< $(CFLAGS) -o $@
rados_read:rados_read.c
	$(CC) $< $(CFLAGS) -o $@
rados_rm:rados_rm.c
	$(CC) $< $(CFLAGS) -o $@

clean:
	rm -rf rados_write rados_read rados_rm
