VERB ?= 0

.PHONY: clean all

# EPS=$(patsubst %.svg,%.eps,$(wildcard *.svg))
# EPS+=$(patsubst %.png,%.eps,$(wildcard *.png))
PNG = $(wildcard *.png)
JPG = $(wildcard *.jpg)
SVG = $(wildcard *.svg)


PNG_RESOLUTION=1024x1024

all: $(PNG) $(JPG) $(SVG) #$(EPS)

# Uses `svgexport` to convert svg to png. Install it using `npm`
%.eps: %.png
ifeq ($(VERB),1)
	@inkscape $< -E $@ -z --export-ignore-filters --export-ps-level=3
else
	@inkscape $< -E $@ -z --export-ignore-filters --export-ps-level=3 2> /dev/null
endif

%.eps: %.svg
ifeq ($(VERB),1)
	@inkscape $< -E $@ -z --export-ignore-filters --export-ps-level=3
else
	@inkscape $< -E $@ -z --export-ignore-filters --export-ps-level=3 2> /dev/null
endif


clean:
	@rm -rf $(EPS)
