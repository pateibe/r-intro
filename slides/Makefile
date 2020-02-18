# Convert all files in this directory that have a .md suffix
SOURCE_DOCS := $(wildcard *.md)

EXPORTED_DOCS= $(SOURCE_DOCS:.md=.html)

############## macOS ##############
# PANDOC_OPTIONS= -t revealjs \
#     --include-in-header=header.html \
#     --css=styles.css \
#     --variable center=false \
#     --variable revealjs-url="/Users/patric/reveal.js" \
#####################################

############## WIN BFH ##############
PANDOC_OPTIONS= -t revealjs \
    --include-in-header=header.html \
    --css=styles.css \
    --variable center=false \
    --variable revealjs-url="C:\local_data\reveal.js" \
######################################

##### use this for standalone html #####
# needs connection to the revealjs server!
#
# PANDOC_OPTIONS=-t revealjs \
#     --self-contained \
#     --include-in-header=header.html \
#     --css=styles.css \
#     --variable center=false \
#     --variable revealjs-url="https://revealjs.com" \
########################################

$(EXPORTED_DOCS): $(SOURCE_DOCS)
	pandoc $(PANDOC_OPTIONS) -o $@ $< 

clean:
	rm $(EXPORTED_DOCS)