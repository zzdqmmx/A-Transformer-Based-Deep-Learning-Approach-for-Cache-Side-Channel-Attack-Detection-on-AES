all: spy
clean:
	rm -f *.o spy
spy: spy.cpp ../../cacheutils.h
	g++ -std=gnu++11 -O0 -g-o $@ $< -I/home/dgruss/openssl -L/home/dgruss/openssl -lcrypto
