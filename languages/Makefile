langs = lua python2 python3 forth bash cpp javascript php typescript golang haskell
.PHONY: $(langs)
all: $(langs)

$(langs):
	docker build -t openrepl/$@ $@

list:
	@echo $(langs)
