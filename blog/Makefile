BASE_URL := https://agres.online/
DEST := public
HUGO := hugo

build:
	$(HUGO) --cleanDestinationDir -b $(BASE_URL)

serve:
	$(HUGO) server -D

clean:
	rm -rf $(DEST)

.PHONY: build serve clean
