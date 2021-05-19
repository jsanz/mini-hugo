DEST := public
HUGO_OPTS := --minify --destination $(DEST)
.DEFAULT_GOAL := build

build:
	hugo $(HUGO_OPTS)

clean:
	rm -rf $(DEST)

serve:
	hugo serve --port 8080 $(HUGO_OPTS)