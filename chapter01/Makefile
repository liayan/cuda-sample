APPS=hello

all: ${APPS}

%: %.cu
	nvcc -O2 -arch=sm_80 -o $@ $<
clean:
	rm -f ${APPS}
