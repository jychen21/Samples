make:
	g++ -std=gnu++11 -I/usr/include/habanalabs -Wall -g -o reshape reshape.cpp -L/usr/lib/habanalabs/ -lSynapse -ldl
	mkdir -p ../../bin
	cp -rf reshape ../../bin
dev:
	g++ -std=gnu++11 -I/usr/include/habanalabs -Wall -g -o reshape reshape.cpp -L/usr/lib/habanalabs/ -lSynapse -ldl
	mkdir -p ../../bin
	cp -rf reshape ../../bin
clean:
	rm -rf ../../bin/reshape
	rm -rf reshape
