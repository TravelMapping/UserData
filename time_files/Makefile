.PHONY: clean

%.time: ../list_files/%.list
	git log -n 1 --pretty=%ci ../list_files/$*.list > $@

clean:
	@rm *.time
