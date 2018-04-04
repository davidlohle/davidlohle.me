LESS_DIR = ./static/less
LESS_FILE = style.less
CSS_DIR = ./static/css
CSS_FILE = style.min.css
CSS_TMP_FILE = tmp.css


.PHONY: build

build:
	lessc $(LESS_DIR)/$(LESS_FILE) > $(CSS_DIR)/$(CSS_TMP_FILE)
	uglifycss $(CSS_DIR)/$(CSS_TMP_FILE) > $(CSS_DIR)/$(CSS_FILE)
	rm -f $(CSS_DIR)/$(CSS_TMP_FILE)

