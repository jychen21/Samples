make:
	g++ -std=gnu++11 -I/usr/include/habanalabs -Wall -g -o softmax softmax.cpp -L/usr/lib/habanalabs/ -lSynapse -ldl
	mkdir -p ../../bin
	cp -rf softmax ../../bin
dev:
	g++ -std=gnu++11 -I/usr/include/habanalabs -Wall -g -o softmax softmax.cpp -L/usr/lib/habanalabs/ -lSynapse -ldl
	mkdir -p ../../bin
	cp -rf softmax ../../bin
clean:
	rm -rf ../../bin/softmax
	rm -rf softmax
