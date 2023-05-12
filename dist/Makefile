LHa_4U4A-i386-aros.lha: lha LHa_4U4A.guide LHa_4U4A.guide.info
	lha a $@ $^

lha: ../src/lha
	cp $< $@

.PHONY: ../src/lha
../src/lha:
	$(MAKE) -C ..

.PHONY: clean
clean:
	$(RM) lha *.lha
