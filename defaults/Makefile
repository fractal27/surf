# Browser style/js defaults
INSTDIR=~/.surf
SRCD=.

all:

install: $(SRCD)/styles $(SRCD)/scripts $(SRCD)/script.js
	mkdir -p $(INSTDIR)
	mkdir -p $(INSTDIR)/styles
	cp -r $(SRCD)/styles $(INSTDIR)/styles
	cp -r $(SRCD)/scripts $(INSTDIR)/scripts
	cp $(SRCD)/script.js $(INSTDIR)/script.js

clean:
	rm -rf $(INSTDIR)/styles/
	rm -f $(INSTDIR)/script.js


.PHONY: all install clean
