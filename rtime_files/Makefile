.PHONY: clean

%.time: ../rlist_files/%.rlist
	git log -n 1 --pretty=%ci ../rlist_files/$*.rlist > $@

clean:
	@rm *.time
