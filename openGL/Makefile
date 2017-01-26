CC=gcc
LDFLAGS := -L/usr/lib/x86_64-linux-gnu/mesa/ -lGL 

TARGETS := gl-triangle


gl-triangle:
	$(CC) $@.c $(LDFLAGS) -o $@ 

all: $(TARGETS)

clean:
	rm $(TARGETS)
