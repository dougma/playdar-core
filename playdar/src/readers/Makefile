include ../../support/include.mk
EBIN_DIR := ../../ebin
DOC_DIR  := ../../doc
ERLC_FLAGS += -pa $(EBIN_DIR)

all: $(EBIN_FILES_NO_DOCS)

debug:
	$(MAKE) DEBUG=-DDEBUG

clean:
	rm -rf $(EBIN_FILES)
