TARGETS=main.pdf                       \
	proposition-undergrupper.pdf   \
	verksamhetsberättelse.pdf      \
	ekonomisk-berättelse.pdf       \
	budget.pdf

stormote.pdf: $(TARGETS)
	pdfunite $^ $@

verksamhetsberättelse.pdf: verksamhetsberättelse.typ
	typst compile $<

main.pdf: main.typ
	typst compile $<

budget.pdf: budget.typ
	typst compile $<
