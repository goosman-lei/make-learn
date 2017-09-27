foo :
	@echo foo in makefile

% : force
	@echo Hi $@
	@$(MAKE) -f foo.mk $@

force : ;