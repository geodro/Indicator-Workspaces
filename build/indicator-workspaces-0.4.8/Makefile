all:

clean:
	rm -fr build

pack:
	tar czvf indicator-workspaces.tgz indicator-workspaces install README INSTALL COPYING AUTHORS share debian make-deb Makefile

install:
	./install install 

uninstall:
	./install uninstall

.PHONY: install uninstall pack clean
