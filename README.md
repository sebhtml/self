
This project was inspired by http://cm.bell-labs.com/who/ken/trust.html

Basically, if you compile self.c and execute it, you get back its own source code.


	gcc self.c -o self
	./self > self2.c
	gcc self2.c -o self2
	./self2 > self3.c
	gcc self3.c -o self3
	./self3 > self4.c


md5sum *.c
