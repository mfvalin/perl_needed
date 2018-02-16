
PERL5LIB = ../../PERL5LIB

all : URI.done PathTools.done

URI.done:
	cd URI* && perl Makefile.PL PREFIX=$(PERL5LIB) lib=$(PERL5LIB) && make && make install && touch ../URI.done && touch $(PERL5LIB)/.ignore

PathTools.done:
	cd PathTools* && perl Makefile.PL PREFIX=$(PERL5LIB) lib=$(PERL5LIB) && make && make install && touch ../PathTools.done && touch $(PERL5LIB)/.ignore

