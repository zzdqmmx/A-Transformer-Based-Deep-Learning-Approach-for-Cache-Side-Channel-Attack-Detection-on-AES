all: newspy
clean:
	rm -f *.o newspy
newspy:newspy.cpp
	export LD_LIBRARY_PATH=/usr/local/lib
	g++ -O3 -o $@ $< -I/usr/local/include/ssl -L/usr/local/lib -lcrypto
