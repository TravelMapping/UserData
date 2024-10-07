.PHONY: clean

%.time: ../list_files/$(*F)
	git log -n 1 --pretty=%ci ../`echo $(*F) | sed 's~.*\.~~'`_files/$(*F) > $@

clean:
	@rm *.time
