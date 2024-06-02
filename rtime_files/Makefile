.PHONY: clean

%.time: ../rlist_files/%.list
	git log -n 1 --pretty=%ci ../rlist_files/$*.list > $@

clean:
	@rm *.time
