sde_randr_CFLAGS = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	$(GTK_CFLAGS) \
	$(ADDITIONAL_FLAGS)

bin_PROGRAMS = sde-randr

sde_randr_SOURCES = \
	sde-randr.c 

sde_randr_LDADD = @GTK_LIBS@ $(INTLLIBS)

