DEST := public
HUGO_OPTS := --minify --destination $(DEST)
.DEFAULT_GOAL := build

.PHONY: clean build serve serve-built

build:
	hugo $(HUGO_OPTS)

clean:
	rm -rf $(DEST)

serve:
	hugo serve --port 8080 $(HUGO_OPTS)

serve-dist: build
	python3 -m http.server 8080 --bind 127.0.0.1 --directory $(DEST)