.PHONY: all warning generate clean

all: warning generate

# fun: warning
# if(./README.md)
# do
# @echo "README.md is an existing file，you just covered it"
warning : README.md
	@echo "README.md is an existing file，you just covered it"

generate: 
	@echo "Creating a file named README.md ..."
	touch README.md

clean: 
	@echo "Cleaning up..."
	rm *.md
